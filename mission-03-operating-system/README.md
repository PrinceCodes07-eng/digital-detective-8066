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

## 10. Conclusion

This mission helped me understand how an operating system manages processes, memory, files and hardware devices. I also learned how to inspect processes and memory statistics using macOS Terminal commands.