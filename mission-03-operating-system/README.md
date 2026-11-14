# Mission 3 – Operating Systems

## 1. Objective

To understand operating systems, their functions, and how they manage computer resources.

## 2. What is an Operating System?

An Operating System (OS) is system software that manages computer hardware and software resources and provides services to applications.

Examples:
- Windows
- macOS
- Linux
- Android
- iOS

## 3. Main Functions of an Operating System

1. **Process Management:** Manages running programs and CPU time.
2. **Memory Management:** Allocates and releases memory for programs.
3. **File Management:** Manages files and folders.
4. **Device Management:** Controls hardware devices.
5. **Security Management:** Protects system resources and data.
6. **User Interface:** Allows users to interact with the computer.

## 4. Kernel vs Shell

- **Kernel:** The core component of an OS. It manages hardware, memory and processes.
- **Shell:** An interface that accepts user commands and communicates requests to the OS.

Examples of shells: Bash and Zsh.

## 5. Process Management

A process is a program that is currently executing.

### Program vs Process

A program is a set of instructions stored in a file. A process is an instance of that program while it is running.

Important terms:

- **PID:** Unique Process ID.
- **Multitasking:** Managing multiple processes seemingly at the same time.
- **Scheduling:** Selecting which process gets CPU time.
- **Context Switching:** Switching CPU execution between processes.

### Practical Commands

```bash
ps
ps aux
echo $$
top
```

- `ps` displays processes associated with the current terminal.
- `ps aux` displays a broader list of running processes.
- `echo $$` displays the current shell's PID.
- `top` displays live process information.
- Press `q` to exit `top`.

### Understanding Multitasking

An operating system manages multiple running processes by scheduling their use of the CPU. Context switching allows the CPU to switch between processes so they can make progress.

## 6. Memory Management

- **RAM:** Temporary (volatile) memory used by running programs.
- **Memory Allocation:** Assigning memory to processes.
- **Memory Deallocation:** Releasing memory when it is no longer needed.
- **Virtual Memory:** A memory management technique that uses storage to support the system's memory needs.

### Practical Command

```bash
vm_stat
```

Displays memory statistics on macOS.

## 7. File Management

File Management handles creating, reading, writing, deleting and organizing files and folders.

## 8. Device Management

Device Management controls hardware devices such as keyboards, printers, speakers and USB drives.

### Device Driver

A device driver is software that helps the operating system communicate with and control a hardware device.

## 9. Practical Learning

During this mission, I:

- Used `ps` to view terminal processes.
- Used `ps aux` to view running processes.
- Used `echo $$` to identify my shell PID.
- Explored `top` for live process monitoring.
- Used `vm_stat` to view memory statistics.

## 10. Difficulties Faced and How I Resolved Them

Initially, I found it difficult to understand the difference between a program and a process.

I understood that a program is stored instructions, while a process is a running instance of a program.

I also learned how to exit the `top` command by pressing `q`.

## 11. Evidence and Files

The practical work for this mission was performed using macOS Terminal commands:

- `ps`
- `ps aux`
- `echo $$`
- `top`
- `vm_stat`

## 12. Key Learnings

- Understood the purpose and functions of an operating system.
- Learned the difference between a kernel and a shell.
- Understood process management and memory management.
- Learned about multitasking, scheduling and context switching.
- Understood file management, device management and device drivers.

## 13. Conclusion

This mission helped me understand how an operating system manages processes, memory, files and hardware devices. I also learned how to inspect processes and memory statistics using macOS Terminal commands.

## Commit Details

Commit message: `Complete Mission 3 operating systems documentation`