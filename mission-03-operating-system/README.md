# Mission 3 — Operating Systems

## Objective

Understand how an operating system manages processes, memory, storage, files, paths, permissions and connected devices.

## 1. What Is an Operating System?

An operating system (OS) is system software that manages computer hardware and software resources and provides services to applications.

Examples include macOS, Windows, Linux, Android and iOS.

## 2. Main Responsibilities

- **Process management:** starts, schedules and stops processes
- **Memory management:** allocates and releases RAM
- **File management:** organises files and directories
- **Storage management:** keeps track of data on storage devices
- **Device management:** coordinates hardware through device drivers
- **Security and permissions:** controls access to files and system resources
- **User interface:** provides graphical or command-line ways to use the computer

## 3. Kernel and Shell

- **Kernel:** the core of the OS; manages CPU time, memory and devices.
- **Shell:** a command interpreter through which a user can request operations.

Examples of shells include Bash and Zsh.

## 4. Programs and Processes

A program is a set of stored instructions. A process is an instance of a program that is currently running.

Important terms:
- **PID:** the process identifier
- **Scheduling:** deciding which process receives CPU time
- **Multitasking:** managing several active processes
- **Context switching:** changing the CPU from one process to another

Useful macOS Terminal commands:

```bash
ps
ps aux
echo $$
top
```

- `ps` lists processes associated with the current terminal.
- `ps aux` displays a broader process list.
- `echo $$` prints the current shell's PID.
- `top` shows live process and resource information. Press `q` to exit.

## 5. Memory

- **RAM** is fast, temporary memory used by running programs.
- **Allocation** assigns memory to a process.
- **Deallocation** releases memory that is no longer needed.
- **Virtual memory** is an OS memory-management technique that uses storage to support memory demands.

On macOS, `vm_stat` displays virtual-memory statistics:

```bash
vm_stat
```

## 6. Storage

Storage keeps files and applications when the computer is turned off. Unlike RAM, SSD or hard-drive storage is non-volatile.

Useful commands:

```bash
df -h
du -sh .
```

- `df -h` shows available and used space on mounted file systems.
- `du -sh .` estimates the total size of the current directory.

## 7. Paths and Directories

- An **absolute path** starts from the root of the file system.
- A **relative path** is interpreted from the current working directory.
- `pwd` prints the current path.
- `ls -la` lists files, including hidden files, with details.

## 8. File Permissions

The basic permissions are read (`r`), write (`w`) and execute (`x`). On Unix-like systems, these permissions can be set for the owner, group and others.

Examples:

```bash
ls -l
chmod 644 notes.txt
chmod 755 test.sh
```

The numeric values are read = 4, write = 2 and execute = 1. For example, 755 means owner read/write/execute and group/others read/execute.

## 9. Device Management and Drivers

The OS coordinates devices such as keyboards, displays, speakers and USB drives. A device driver is software that allows the OS to communicate with a particular device.

## What I Learned

I learned the difference between a program and a process, the roles of the kernel and shell, and how the OS manages memory, storage, files, permissions and devices. The commands in this mission provide ways to inspect processes, memory and disk usage from Terminal.

## Conclusion

An operating system is the manager between applications and computer hardware. It keeps processes organised, allocates resources and provides a structured way to store and access information.