# Mission 2 — Terminal and File Management

## Objective

Practise navigating the file system, creating and managing files, searching, using permissions, and understanding package managers.

## 1. Navigation

| Command | Purpose |
|---|---|
| `pwd` | Show the current directory |
| `ls` | List files and folders |
| `ls -la` | Include hidden files and details |
| `cd folder` | Enter a directory |
| `cd ..` | Move to the parent directory |

## 2. Files and Directories

| Command | Purpose |
|---|---|
| `mkdir practice` | Create a directory |
| `touch notes.txt` | Create an empty file |
| `cp notes.txt backup/` | Copy a file |
| `mv old.txt new.txt` | Move or rename a file |
| `rm notes.txt` | Delete a file |
| `cat notes.txt` | Display file contents |
| `echo "Hello" > notes.txt` | Write or replace file contents |
| `echo "More" >> notes.txt` | Append to a file |

Check paths with `pwd` and `ls` before moving or deleting files. The `rm` command does not normally move files to the Trash.

## 3. Finding Files and Searching Text

- `find . -name "notes.txt"` searches for a file or directory by name.
- `grep "Hello" notes.txt` searches for text inside a file.
- `grep -r "Hello" practice/` searches recursively inside files.
- `ls | grep ".txt"` sends the output of `ls` to `grep` through a pipe.

A pipe (`|`) passes one command's output to another command.

## 4. File Permissions

Permissions are represented by read, write and execute:

| Permission | Symbol | Value |
|---|---|---:|
| Read | r | 4 |
| Write | w | 2 |
| Execute | x | 1 |

Examples:
- `chmod 644 notes.txt` gives the owner read/write and others read access.
- `chmod 755 test.sh` gives the owner full access and others read/execute access.
- `ls -l` displays file permissions.

The practice script is `practice/test.sh`. It prints a short message and can be used to practise executable permissions.

## 5. Package Managers

A package manager helps install, update, search for and remove software.

On macOS, Homebrew is a commonly used package manager. If Homebrew is installed, these commands can be used:

| Command | Purpose |
|---|---|
| `brew --version` | Check whether Homebrew is available |
| `brew search tree` | Search for a package |
| `brew info tree` | Read package information |
| `brew list` | List installed packages |
| `brew install tree` | Install a package |

The install command changes the computer, so it should only be run when the package is actually needed. The commands above are examples for the package-manager task.

## 6. Practice Files

The `practice/` directory contains text files and a backup copy. They provide a safe place to practise `touch`, `cp`, `mv`, `find`, `grep`, pipes, redirection and permissions.

## What I Learned

I learned the difference between searching for a filename and searching inside file contents. I also learned that permissions control what users can do with files, pipes connect commands, and package managers make software installation and updates easier.

## Conclusion

This mission covers navigation, file management, searching, permissions, pipes, redirection and package-manager basics.