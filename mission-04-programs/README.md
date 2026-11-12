# Mission 4 – Programs

## Objective
To understand how programs work, the difference between compilers and interpreters, and how an operating system manages program execution.

## 1. What is a Program?
A program is a set of instructions that tells a computer what tasks to perform.

Examples: Python programs, C++ programs, web browsers and games.

## 2. Source Code and Executable

- **Source Code:** Human-readable instructions written by a programmer.
- **Executable:** A file or program that the computer can run.

Example:
- `hello.py` contains Python source code.
- `hello.cpp` contains C++ source code.
- `hello` is the compiled executable created from the C++ program.

## 3. Compiler vs Interpreter

### Compiler
A compiler translates source code into a form that can be executed, often producing an executable file.

Example: C++ uses a compiler such as `g++`.

Command:
```bash
g++ hello.cpp -o hello
```

Run the executable:
```bash
./hello
```

### Interpreter
An interpreter executes a program using a language runtime.

Example: Python is commonly described as an interpreted language. Python implementations typically compile source code into bytecode, which the Python Virtual Machine executes.

Command:
```bash
python3 hello.py
```

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
print("Hello from Python!")
```

Run:
```bash
python3 hello.py
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

Compile:
```bash
g++ hello.cpp -o hello
```

Execute:
```bash
./hello
```

### Observing a Running Process

File: `practice/wait.py`

```python
import time

print("Program is running...")

time.sleep(30)

print("Program finished!")
```

Run the program in Terminal 1:
```bash
python3 wait.py
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

| Command | Purpose |
|---|---|
| `python3 hello.py` | Runs a Python program |
| `g++ hello.cpp -o hello` | Compiles a C++ program |
| `./hello` | Executes the compiled program |
| `ps aux` | Displays running processes |
| `ps aux | grep '[w]ait.py'` | Searches for the wait.py process |

## 7. Key Learnings

- A program is a set of instructions.
- A process is a running instance of a program.
- The OS manages processes and memory.
- The CPU executes instructions.
- RAM temporarily stores programs and data.
- The OS releases process resources when a process terminates.

## Conclusion

In this mission, I learned about programs, source code, compilers, interpreters and the role of an operating system in program execution. I also compiled and executed a C++ program, ran a Python program and observed a running process using the `ps` command.