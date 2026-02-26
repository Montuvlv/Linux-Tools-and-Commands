# Linux Tools and Commands

A repository for basic Linux tools and commands.

## Basic Linux Commands

### File and Directory Management

- **`ls`**: List files and directories in the current directory.
  - `ls -l`: Long format (shows permissions, owner, size).
  - `ls -a`: Show hidden files.
- **`cd [dir]`**: Change directory to `[dir]`.
  - `cd ..`: Move up one directory level.
  - `cd ~`: Go to home directory.
- **`pwd`**: Print working directory (shows your current location).
- **`mkdir [dir]`**: Create a new directory named `[dir]`.
- **`rmdir [dir]`**: Remove an empty directory.
- **`touch [file]`**: Create an empty file named `[file]`.
- **`cp [source] [dest]`**: Copy a file from `[source]` to `[dest]`.
  - `cp -r [dir1] [dir2]`: Recursively copy a directory.
- **`mv [source] [dest]`**: Move or rename a file/directory.
- **`rm [file]`**: Remove a file.
  - `rm -r [dir]`: Recursively remove a directory and its contents.
- **`cat [file]`**: Display the contents of a file.

### System and Information

- **`man [command]`**: Display the manual page for `[command]`.
- **`grep "[text]" [file]`**: Search for `[text]` inside `[file]`.
- **`chmod [mode] [file]`**: Change permissions of a file.
- **`chown [owner]:[group] [file]`**: Change owner and group of a file.
- **`sudo [command]`**: Run `[command]` with superuser (root) privileges.
- **`top`**: Display real-time system process information.
- **`df -h`**: Show disk space usage in human-readable format.
- **`free -m`**: Show memory usage in MB.
- **`history`**: See a list of commands you've run previously.
