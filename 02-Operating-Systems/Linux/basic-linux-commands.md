# Basic Linux Commands



This document covers essential Linux commands used for navigating the system, managing files, and viewing system information. These commands form the foundation for working in Linux environments and are widely used in cybersecurity roles.



---



## Navigation Commands



### pwd

Displays the current working directory.



### ls

Lists files and directories in the current location.



Common options:

- `ls -l` → Detailed list

- `ls -a` → Show hidden files



### cd

Changes directories.



Examples:

- `cd /home`

- `cd ..` (move up one directory)



---



## File and Directory Management



### mkdir

Creates a new directory.



Example:

`mkdir testfolder`



### rmdir

Removes an empty directory.



### rm

Deletes files or directories.



Examples:

- `rm file.txt`

- `rm -r foldername` (delete folder and contents)



---



## File Viewing Commands



### cat

Displays the contents of a file.



### less

Views file content one page at a time.



### head

Shows the first lines of a file.



### tail

Shows the last lines of a file (useful for log monitoring).



---



## File Permissions Commands



### chmod

Changes file permissions.



Example:

`chmod 755 script.sh`



### chown

Changes file ownership.



Example:

`chown user:group file.txt`



---



## System Information Commands



### whoami

Shows the current logged-in user.



### uname -a

Displays system information.



### top

Shows running processes in real time.



### ps

Displays currently running processes.



---



## Why These Commands Matter in Cybersecurity



These commands help security professionals:

- Investigate compromised systems

- Analyze logs

- Identify suspicious processes

- Manage file permissions

- Navigate servers during incident response



Strong command line skills are essential for working in Linux-based environments.

