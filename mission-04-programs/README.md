# Mission 4 – Programs

## Objective

To understand how programs work, the difference between compilers and interpreters, and how an operating system manages program execution.

## 1. What is a Program?

A program is a set of instructions that tells a computer what tasks to perform.

Examples: Python programs, C++ programs, web browsers and games.

## 2. Source Code and Executable

- **Source Code:** Human-readable instructions written by a programmer.
- **Executable:** A file or program that the computer can run.

Examples:
- `hello.py` contains Python source code.
- `hello.cpp` contains C++ source code.
- `hello` is the compiled executable created from the C++ program.

## 3. Compiler vs Interpreter

### Compiler

A compiler translates source code into a form that can be executed, often producing an executable file.

Example: C++ uses a compiler such as `g++`.

### Interpreter

An interpreter executes a program using a language runtime.

Example: Python is commonly described as an interpreted language. Python implementations typically compile source code into bytecode, which the Python Virtual Machine executes.

## 4. Role of Operating System in Program Execution

When a program starts:

1. The OS loads the program into memory.
2. The OS creates a process.
3. The OS manages memory and other resources.
4. The CPU executes the program's instructions.
5. The OS schedules CPU time for processes.
6. When the process terminates, the OS releases its resources.

## 5. Practical Work

### Python Program

File: `practice/hello.py`

```python
print("Hello, Digital Detective!")
print("I am learning how computers execute programs.")
```

Run from the project root:

```bash
python3 mission-04-programs/practice/hello.py
```

Output:

```text
Hello, Digital Detective!
I am learning how computers execute programs.
```

### C++ Program

File: `practice/hello.cpp`

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello from C++!" << endl;
    return 0;
}
```

Compile from the project root:

```bash
g++ mission-04-programs/practice/hello.cpp -o mission-04-programs/practice/hello
```

Execute:

```bash
./mission-04-programs/practice/hello
```

Output:

```text
Hello from C++!
```

### Observing a Running Process

File: `practice/wait.py`

```python
import time

print("Program is running...")

time.sleep(30)

print("Program finished!")
```

Run in Terminal 1:

```bash
python3 mission-04-programs/practice/wait.py
```

While it is running, use Terminal 2:

```bash
ps aux | grep '[w]ait.py'
```

Observation:

- The command displayed the running Python process.
- The process had a Process ID (PID).
- After the 30-second wait, the program finished and its process terminated.

## 6. Important Commands

- `python3 mission-04-programs/practice/hello.py` – Runs a Python program.
- `g++ mission-04-programs/practice/hello.cpp -o mission-04-programs/practice/hello` – Compiles a C++ program.
- `./mission-04-programs/practice/hello` – Executes the compiled program.
- `ps aux` – Displays running processes.
- `ps aux | grep '[w]ait.py'` – Searches for the wait.py process.

## 7. Key Learnings

- A program is a set of instructions.
- A process is a running instance of a program.
- The OS manages processes and memory.
- The CPU executes instructions.
- RAM temporarily stores programs and data.
- The OS releases process resources when a process terminates.

## 8. Difficulty Faced

Initially, I used incorrect file paths when running Python and C++ programs from the project root.

I resolved this by checking the directory structure and using the correct relative paths.

I also learned how to observe a running process using the `ps` command.

## Conclusion

In this mission, I learned about programs, source code, compilers, interpreters and the role of an operating system in program execution. I also compiled and executed a C++ program, ran a Python program and observed a running process using the `ps` command.