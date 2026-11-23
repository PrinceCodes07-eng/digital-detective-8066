# Mission 4 — Programs and How They Run

## Objective

Understand what a program is, how source code is run, and the difference between a compiler and an interpreter.

## 1. What Is a Program?

A program is a set of instructions that tells a computer what to do. A program is stored as code; when it is started, the operating system creates and manages a running process.

## 2. Source Code and Machine Instructions

- **Source code** is written by a programmer in a programming language.
- A **compiler** translates source code into another form, commonly machine code or an intermediate form, before execution.
- An **interpreter/runtime** reads or executes program instructions while the program runs.

## 3. Compiler vs Interpreter

| Feature | Compiler | Interpreter |
|---|---|---|
| When translation happens | Usually before the program runs | During program execution |
| Output | Often creates a separate executable or intermediate file | Usually runs through an interpreter/runtime |
| Error reporting | Many errors are reported during compilation | Many errors appear when the relevant instruction is executed |
| Typical use | Common in compiled-language workflows | Common in interpreted-language workflows |
| Example | A compiled C program | A Python program run with Python 3 |

The distinction is a useful general model. Real language implementations can combine compilation and interpretation. For example, Python commonly compiles source into bytecode and executes it using a virtual machine.

## 4. Required Python Program

The required file is `hello.py` in this folder.

Run it from this directory:

```bash
python3 hello.py
```

Expected output:

```text
Hello from Python
```

## 5. How the Operating System Runs a Program

1. The user starts a program.
2. The OS creates a process and assigns it resources.
3. The program's instructions are executed by the CPU.
4. The OS schedules CPU time and manages memory.
5. When the program finishes, the OS releases its resources.

## What I Learned

A program is stored instructions, while a process is a running instance. Compilers and interpreters are different ways of translating or executing code. The operating system manages the process and the resources it needs.

## Files

- `hello.py` — the required Python program.

## Conclusion

This mission covers the required Python run and the comparison between compilers and interpreters. It does not require a C++ source file or a C++ compiler installation.