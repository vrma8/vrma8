# Basic Linux Commands

A quick reference guide for essential Linux command-line utilities.

---

## 1. `pwd`
**Print Working Directory**: Displays the current directory.

```bash
$ pwd
/home/student
```

---

## 2. `ls`
**List Directory Contents**: Shows files and folders in a directory.

```bash
$ ls
Documents Downloads Pictures
```

---

## 3. `cd`
**Change Directory**: Navigate between directories.

```bash
$ cd Downloads
```

---

## 4. `mkdir`
**Make Directory**: Creates a new folder.

```bash
$ mkdir projects
```

---

## 5. `rmdir`
**Remove Directory**: Deletes an empty folder.

```bash
$ rmdir projects
```

---

## 6. `touch`
**Create File**: Creates an empty file.

```bash
$ touch file.txt
```

---

## 7. `rm`
**Remove File/Folder**: Deletes files or directories.

```bash
$ rm file.txt
$ rm -r folder_name
```

---

## 8. `cp`
**Copy Files/Directories**: Copies files or directories.

```bash
$ cp file1.txt file2.txt
$ cp -r dir1 dir2
```

---

## 9. `mv`
**Move/Rename**: Moves or renames files and folders.

```bash
$ mv file.txt new_name.txt
$ mv file.txt /home/student/Documents
```

---

## 10. `cat`
**Concatenate and View Files**: Displays file content.

```bash
$ cat file.txt
Hello, Linux!
```

---

## 11. `nano`
**Edit Files**: Opens a text file in the nano editor.

```bash
$ nano file.txt
```

---

## 12. `vi`
**Edit Files**: Opens a text file in the vi editor.

```bash
$ vi file.txt
```

---

## 13. `echo`
**Display Text**: Prints text or writes to a file.

```bash
$ echo "Hello, World!"
$ echo "This is a test" > test.txt
```

---

## 14. `clear`
**Clear Terminal**: Clears the terminal screen.

```bash
$ clear
```

---

## 15. `history`
**Command History**: Shows a list of recently executed commands.

```bash
$ history
```

---

## 16. `find`
**Search for Files**: Locates files in the system.

```bash
$ find /home -name file.txt
```

---

## 17. `grep`
**Search in Files**: Searches for patterns in files.

```bash
$ grep "Linux" file.txt
```

---

## 18. `chmod`
**Change Permissions**: Modifies file permissions.

```bash
$ chmod 755 file.txt
```

---

## 19. `chown`
**Change Ownership**: Changes file ownership.

```bash
$ chown user:group file.txt
```

---

## 20. `man`
**Manual Pages**: Displays command documentation.

```bash
$ man ls
```

---

## 21. `uname`
**System Information**: Displays system details.

```bash
$ uname -a
```

---

## 22. `df`
**Disk Usage**: Shows available and used disk space.

```bash
$ df -h
```

---

## 23. `du`
**Directory Usage**: Displays the size of a directory.

```bash
$ du -sh folder_name
```

---

## 24. `top`
**Process Monitoring**: Displays running processes.

```bash
$ top
```

---

## 25. `ps`
**Process Status**: Lists active processes.

```bash
$ ps
```

---

## 26. `kill`
**Terminate Process**: Stops a running process.

```bash
$ kill 1234
```

---

## 27. `ping`
**Network Test**: Checks connectivity to a host.

```bash
$ ping google.com
```

---

## 28. `curl`
**HTTP Requests**: Fetches data from URLs.

```bash
$ curl https://example.com
```

---

## 29. `wget`
**Download Files**: Downloads files from the internet.

```bash
$ wget https://example.com/file.zip
```

---

## 30. `zip`
**Compress Files**: Creates a ZIP archive.

```bash
$ zip archive.zip file1.txt file2.txt
```

---

## 31. `unzip`
**Extract Files**: Extracts a ZIP archive.

```bash
$ unzip archive.zip
```

---

## 32. `tar`
**Archive Files**: Archives and extracts files.

```bash
$ tar -cvf archive.tar folder
$ tar -xvf archive.tar
```

---

## 33. `df`
**Check Disk Space**: Displays disk usage information.

```bash
$ df -h
```

---

## 34. `free`
**Check Memory**: Shows RAM and swap usage.

```bash
$ free -h
```

---

## 35. `hostname`
**Display Hostname**: Shows the system’s hostname.

```bash
$ hostname
```

---

## 36. `ifconfig`
**Network Configuration**: Displays network settings.

```bash
$ ifconfig
```

---

## 37. `ssh`
**Secure Shell**: Connects to a remote machine.

```bash
$ ssh user@192.168.1.1
```

---

## 38. `scp`
**Secure Copy**: Transfers files between machines.

```bash
$ scp file.txt user@192.168.1.1:/home/user
```

---

## 39. `passwd`
**Change Password**: Updates the user password.

```bash
$ passwd
```

---

## 40. `whoami`
**Current User**: Displays the current username.

```bash
$ whoami
```

---

## 41. `uptime`
**System Uptime**: Shows how long the system has been running.

```bash
$ uptime
```

---

## 42. `shutdown`
**Power Off**: Schedules a system shutdown.

```bash
$ shutdown -h now
```

---

## 43. `reboot`
**Restart System**: Reboots the system.

```bash
$ reboot
```

---

## 44. `alias`
**Shortcut Commands**: Creates a custom command alias.

```bash
$ alias ll='ls -la'
```

---

## 45. `unalias`
**Remove Alias**: Deletes a custom alias.

```bash
$ unalias ll
```

---

## 46. `wc`
**Word Count**: Counts words, lines, and characters in a file.

```bash
$ wc file.txt
```

---

## 47. `head`
**View File Start**: Displays the first lines of a file.

```bash
$ head file.txt
```

---

## 48. `tail`
**View File End**: Displays the last lines of a file.

```bash
$ tail file.txt
```

---

## 49. `sort`
**Sort Lines**: Arranges lines in a file.

```bash
$ sort file.txt
```

---

## 50. `uniq`
**Remove Duplicates**: Filters unique lines in a file.

```bash
$ uniq file.txt
```