## 1. Change Directory

```bash
cd
```

The `cd` command, short for "change directory," is used to navigate between directories in the command line. By using `cd` followed by a specific path, you move to that directory.

- **Syntax**: `cd [directory-path]`
- **Example**: `cd /home/ubuntu` moves to the `/home/ubuntu` directory.

## 2. List Directory Contents

```bash
ls -la
```

The `ls` command lists the files and directories in the current directory.

- **Options**:
  - `-l`: Displays detailed information (permissions, owner, size, date modified).
  - `-a`: Shows hidden files.
- **Example**: `ls -la` displays all files, including hidden ones, with detailed information.

## 3. Create a New Directory

```bash
mkdir new_directory
```

The `mkdir` command creates a new directory.

- **Syntax**: `mkdir [directory-name]`
- **Example**: `mkdir projects` creates a directory named "projects."

## 4. Copy Files

```bash
cp source.txt destination.txt
```

The `cp` command copies files or directories.

- **Syntax**: `cp [source] [destination]`
- **Example**: `cp file1.txt file2.txt` copies `file1.txt` to `file2.txt`.

## 5. Move or Rename Files

```bash
mv old_name.txt new_name.txt
```

The `mv` command moves or renames files and directories.

- **Syntax**: `mv [source] [destination]`
- **Example**: `mv file1.txt file2.txt` renames `file1.txt` to `file2.txt`.

## 6. Remove Files or Directories

```bash
rm file.txt
```

The `rm` command deletes files or directories.

- **Options**:
  - `-r`: Removes directories and their contents.
  - `-f`: Forces deletion without confirmation.
- **Example**: `rm -rf directory_name` deletes a directory and all its contents.

## 7. Display File Contents

```bash
cat file.txt
```

The `cat` command displays the contents of a file.

- **Syntax**: `cat [filename]`
- **Example**: `cat notes.txt` displays the contents of `notes.txt`.

## 8. Redirect Output to a File

```bash
echo "Hello, World!" > file.txt
```

The `>` operator redirects command output to a file, creating or overwriting the file.

- **Syntax**: `[command] > [filename]`
- **Example**: `echo "Sample text" > sample.txt` writes "Sample text" to `sample.txt`.

## 9. Append Output to a File

```bash
echo "Additional text" >> file.txt
```

The `>>` operator appends output to an existing file without overwriting it.

- **Syntax**: `[command] >> [filename]`
- **Example**: `echo "More text" >> sample.txt` adds "More text" to `sample.txt`.

## 10. Print Working Directory

```bash
pwd
```

The `pwd` command displays the current working directory's absolute path.

- **Syntax**: `pwd`
- **Example**: Running `pwd` in `/home/ubuntu` outputs `/home/ubuntu`.

## 11. Display Command History

```bash
history
```

The `history` command displays a list of previously used commands.

- **Syntax**: `history`
- **Example**: `history` shows a list of recently executed commands.

## 12. Clear Terminal Screen

```bash
clear
```

The `clear` command clears the terminal screen.

- **Syntax**: `clear`
- **Example**: Running `clear` removes all current text from the terminal display.

## 13. View Active Processes

```bash
ps aux
```

The `ps` command displays active processes.

- **Options**:
  - `aux`: Shows detailed information on all running processes for all users.
- **Example**: `ps aux` lists all active processes with detailed info.

## 14. Terminate a Process

```bash
kill [process_id]
```

The `kill` command terminates a process using its Process ID (PID).

- **Syntax**: `kill [PID]`
- **Example**: `kill 1234` ends the process with PID 1234.

## 15. Display Disk Usage

```bash
df -h
```

The `df` command shows file system disk space usage.

- **Options**:
  - `-h`: Shows sizes in human-readable format.
- **Example**: `df -h` displays disk usage in human-readable format.

## 16. Display Memory Usage

```bash
free -h
```

The `free` command shows memory usage.

- **Options**:
  - `-h`: Displays memory usage in a human-readable format.
- **Example**: `free -h` shows memory usage in MB or GB.
