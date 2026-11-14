# Mission 2 – Terminal and File Management

## Objective

Learn basic terminal commands and understand file and directory management using the command line.

## 1. Directory Navigation

- `pwd` – Displays the current working directory.
- `ls` – Lists files and folders.
- `ls -la` – Shows all files, including hidden files.
- `cd folder-name` – Changes the current directory.
- `cd ..` – Moves to the parent directory.

## 2. File and Directory Management

- `mkdir folder-name` – Creates a new directory.
- `touch file.txt` – Creates an empty file.
- `cp file.txt backup.txt` – Copies a file.
- `mv old.txt new.txt` – Moves or renames a file.
- `rm file.txt` – Removes a file.

**Safety:** Always check the file name before using `rm`, because it deletes files.

## 3. Finding and Searching

- `find . -name "sharma"` – Finds files or folders named sharma.
- `grep "piece" file.txt` – Searches for the word piece inside a file.
- `grep -r "piece" folder/` – Searches for the word piece recursively inside a directory.

### Difference Between find and grep

`find` searches for files and directories by their names or other file properties.

`grep` searches for specific text inside files.

## 4. File Permissions

The `chmod` command changes file permissions.

- `r` – Read permission (4).
- `w` – Write permission (2).
- `x` – Execute permission (1).

Examples:

- `chmod 644 file.txt` – Gives the owner read and write permission, and others read permission.
- `chmod 755 script.sh` – Gives the owner full permissions and others read and execute permissions.

## 5. Redirection and Pipes

- `>` – Writes output to a file, replacing its previous content.
- `>>` – Appends output to a file.
- `|` – Passes the output of one command to another.
- `cat file.txt` – Displays file contents.
- `echo "Hello"` – Prints text.

Examples:

```bash
echo "Hello World" > notes.txt
echo "New line" >> notes.txt
cat notes.txt
ls | grep ".txt"
```

## 6. Practical Exercises

During this mission, I practised:

1. Creating directories and files using `mkdir` and `touch`.
2. Copying and moving files using `cp` and `mv`.
3. Finding files by name using `find`.
4. Searching for text inside files using `grep`.
5. Changing file permissions using `chmod`.
6. Using pipes and redirection to manage command output.

## 7. Difficulties Faced and How I Resolved Them

Initially, I was confused about the difference between finding a file by its name and searching for text inside a file.

I understood that `find` is used to locate files by name, while `grep` searches for text inside files.

I also practised navigating between directories and learned to check my current location using `pwd`.

## 8. Evidence and Practice Files

The following files were created during my terminal practice:

- `practice/demo.txt`
- `practice/notes.txt`
- `practice/test.sh`
- `practice/backup/notes.txt`
- `practice/backup/terminal.txt`

These files and directories were used to practise file creation, copying, moving, searching and permissions.

## 9. Key Learnings

- Learned how to navigate directories using terminal commands.
- Understood file and directory management.
- Learned the difference between `find` and `grep`.
- Understood read, write and execute permissions.
- Practised pipes and output redirection.

## Conclusion

In this mission, I learned how to use terminal commands to manage files and directories, search for information, change permissions and redirect command output. These skills helped me understand how to work more efficiently using the command line.

## Commit Details

Commit message: `Complete Mission 2 README`