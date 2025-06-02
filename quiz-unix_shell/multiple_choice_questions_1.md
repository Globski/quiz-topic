# Question: What shell is commonly the default for many Linux distributions and macOS?

**Answer:**
Bash (Bourne Again SHell) is a common default shell among many Linux distributions and is also the default shell for macOS.

---

# Question: Which keyboard shortcut opens the terminal in most Linux desktop environments?

**Answer:**
Ctrl + Alt + T or Super + T opens the terminal.

---

# Question: What does the shortcut Ctrl + A do in the terminal?

**Answer:**
Ctrl + A moves the cursor to the beginning of the current line.

---

# Question: How can you move the cursor forward and backward by one word on the current line?

**Answer:**
Use Alt + F to move the cursor forward one word and Alt + B to move the cursor backward one word.

---

# Question: What is the function of Ctrl + K in text manipulation within the terminal?

**Answer:**
Ctrl + K cuts the line from the current cursor position to the end of the line, adding it to the clipboard. If the cursor is at the beginning of the line, it cuts the entire line.

---

# Question: How do you paste the last thing you cut from the command line in the terminal?

**Answer:**
Press Ctrl + Y to paste the last thing cut (undo the last delete) at the current cursor position.

---

# Question: What shortcut allows you to swap the last two words before the cursor?

**Answer:**
Alt + T swaps the last two words before the cursor.

---

# Question: Which shortcut is used to search through previously used commands in the terminal?

**Answer:**
Ctrl + R allows you to search through the command history.

---

# Question: What does pressing Ctrl + G do when you are searching command history?

**Answer:**
Ctrl + G leaves the history searching mode without running a command.

---

# Question: How do you capitalize from the cursor to the end of the current word?

**Answer:**
Use Alt + U to make uppercase from the cursor to the end of the word.

---

# Question: What does Alt + . print in the terminal?

**Answer:**
Alt + . prints the last word written in the previous command.

---

# Question: What does the shortcut Alt + R do when editing a command pulled from history?

**Answer:**
Alt + R reverts any changes made to a command pulled from the history, restoring it to its original form.

---

# Question: Which shortcuts allow you to navigate backward and forward through the command history?

**Answer:**
Ctrl + P shows the last executed command (walk back), and Ctrl + N shows the next executed command (walk forward), similar to the up and down arrow keys.

---

# Question: How do you clear the terminal screen using a keyboard shortcut?

**Answer:**
Press Ctrl + L to clear the screen, similar to running the clear command.

---

# Question: What is the function of Ctrl + S and Ctrl + Q in the terminal?

**Answer:**
Ctrl + S stops all output to the screen (does not stop the running command), and Ctrl + Q resumes the output after it has been stopped by Ctrl + S.

---

# Question: How do you stop a currently running process and return to the shell prompt?

**Answer:**
Press Ctrl + C to end the currently running process and return to the prompt.

---

# Question: Which shortcut logs out of the current shell session or acts as an End of File signal?

**Answer:**
Ctrl + D logs out of the current shell session or acts as an End of File (EOF) signal in some commands.

---

# Question: What does Ctrl + Z do to the currently running foreground process?

**Answer:**
Ctrl + Z suspends (pauses) the currently running foreground process and returns the shell prompt. The process can then be resumed in the background with the bg command or brought back to the foreground with fg.

---

# Question: How can you auto-complete file and directory names in the terminal?

**Answer:**
Press Tab to auto-complete files and directory names. Pressing Tab twice shows all possible completions if the typed characters are ambiguous.

---

# Question: What are the functions of Ctrl + H, Ctrl + J, Ctrl + M, and Ctrl + I in the terminal?

**Answer:**
Ctrl + H acts as Backspace, Ctrl + J is Return (Line Feed), Ctrl + M is Return (Carriage Return), and Ctrl + I is Tab.

---

# Question: How do you close a terminal tab and how do you close the entire terminal window using shortcuts?

**Answer:**
Ctrl + Shift + W closes the terminal tab, and Ctrl + Shift + Q closes the entire terminal window.

---

# Question: What is the difference between the directories represented by `.` and `..` in Linux?

**Answer:**
`.` represents the current directory, while `..` represents the parent directory.

---

# Question: If your current directory is `/home/user/somedir`, what will the command `cd ../somedir` do?

**Answer:**
It will keep the current working directory as `/home/user/somedir` because `..` moves up to `/home/user`, and then `/somedir` moves back into `/home/user/somedir`.

---

# Question: What command shows the full path of the current working directory?

**Answer:**
`pwd` shows the full path of the current working directory.

---

# Question: How do you navigate to the last directory you were working in?

**Answer:**
Use the command `cd -` to navigate to the last directory you were working in.

---

# Question: What is the difference between `cd ~` and `cd ..`?

**Answer:**
`cd ~` navigates to the current user's home directory, while `cd ..` moves to the parent directory of the current directory.

---

# Question: Which command lists all files including hidden ones in the current directory?

**Answer:**
`ls -a` lists all files including hidden files (those starting with a dot).

---

# Question: What does the `-F` option do when used with the `ls` command?

**Answer:**
`ls -F` appends a symbol at the end of each file name indicating its type, such as `*` for executables, `/` for directories, `@` for symbolic links, and others.

---

# Question: How do you list files sorted by last modified time with the most recently modified files at the top?

**Answer:**
Use `ls -lt` to list files sorted by last modified time, most recent first.

---

# Question: What command will recursively show all subdirectories and their contents?

**Answer:**
`ls -lR` shows all subdirectories recursively.

---

# Question: What is the function of the `tree` command?

**Answer:**
The `tree` command generates a tree representation of the file system starting from the current directory.

---

# Question: How do you copy a file preserving its attributes like ownership and timestamps?

**Answer:**
Use `cp -p source destination` to copy a file preserving its original attributes.

---

# Question: Which command is used to copy directories recursively?

**Answer:**
`cp -R source_dir destination_dir` copies a directory and its contents recursively.

---

# Question: How do you rename or move a file in Linux?

**Answer:**
Use `mv file1 file2` to move or rename a file.

---

# Question: What does `rm -i filename` do?

**Answer:**
`rm -i filename` asks for confirmation before removing each file. It is recommended for new users.

---

# Question: What is the difference between `rm -R` and `rm -rf` when removing directories?

**Answer:**
`rm -R` removes directories recursively but asks for confirmation if needed. `rm -rf` removes directories recursively, ignoring non-existent files and never prompts for confirmation.

---

# Question: How do you create a directory hierarchy, including parent directories if they don’t exist?

**Answer:**
Use `mkdir -p dir-name/dir-name` to create a directory hierarchy, creating parent directories as needed.

---

# Question: How do you create a file or update its timestamp if it already exists?

**Answer:**
Use the `touch filename` command.

---

# Question: What is the syntax to change file permissions for user, group, and others?

**Answer:**
Use `chmod <specification> filename`, where specification includes `u` for user, `g` for group, `o` for others, and operators like `+` to add or `-` to remove permissions (r, w, x).

---

# Question: How do you change permissions of a directory and all its contents recursively?

**Answer:**
Use `chmod -R <specification> dirname`.

---

# Question: How do you change the ownership of a file to a specific user?

**Answer:**
Use `chown owner1 filename` to change file ownership to user `owner1`.

---

# Question: Which command changes the group ownership of a file or directory?

**Answer:**
`chgrp grp_owner filename` changes the primary group ownership of a file, and `chgrp -R grp_owner dir-name` changes group ownership recursively for a directory.

---

# Question: What command prints "Hello World" in the terminal?

**Answer:**
`echo "Hello World"` prints the text Hello World to the terminal.

---

# Question: How do you read the manual page for a command called `name`?

**Answer:**
Use `man name` to read the manual page for the command `name`.

---

# Question: Which command lets you search for man pages containing a specific keyword?

**Answer:**
`man -k <keyword>` outputs all man pages containing the specified keyword.

---

# Question: How can you get a list of all available bash commands?

**Answer:**
In Bash shell, use the `help` command to display all available bash commands.

---

# Question: What does `apropos editor` do?

**Answer:**
It outputs all applications whose one-line descriptions match the word "editor," useful if you don’t remember the exact command name.

---

# Question: Which command lists all installed packages on a Debian-based system?

**Answer:**
`dpkg -l` outputs a list of all installed packages.

---

# Question: How can you display the files installed by a specific Debian package?

**Answer:**
Use `dpkg -L packageName` to list all files and their paths installed by the package.

---

# Question: What command displays the hostname of the system?

**Answer:**
`hostname` displays the system's hostname.

---

# Question: How do you change the password of the current user?

**Answer:**
Use the `passwd` command to change the current user’s password.

---

# Question: What command shows the username of the user currently logged into the terminal?

**Answer:**
`whoami` shows the username of the current user.

---

# Question: Which command lists all users currently logged into the system?

**Answer:**
`who` lists all users currently logged in.

---

# Question: What command shows current system status, including time, user list, and other info?

**Answer:**
`w` displays the current system status, including logged-in users.

---

# Question: How can you view bad login attempts on the system?

**Answer:**
Use `lastb` to show all bad login attempts.

---

# Question: Which command lists all processes sorted by system resource usage, updating every few seconds?

**Answer:**
`top` lists all processes sorted by current system resource usage and updates dynamically.

---

# Question: How do you list all processes running under the user root?

**Answer:**
Use `ps -u root` to list all processes and commands run by root.

---

# Question: What does `ps aux` show?

**Answer:**
`ps aux` lists all processes running on the system by all users.

---

# Question: How do you find all files under `/var/www` that have a `.css` extension?

**Answer:**
Use the command `find /var/www -name '*.css'` to print the full paths of all `.css` files under `/var/www`.

---

# Question: What does the command `grep font /var/www/html/style.css` do?

**Answer:**
It prints all lines in the file `/var/www/html/style.css` that contain the pattern "font".

---

# Question: Why does `grep font /var/www/html/` return an error, and how do you fix it?

**Answer:**
It returns an error because `/var/www/html/` is a directory. To search recursively inside directories, use `grep -R font /var/www/html/`.

---

# Question: What does the `-R` option do in the grep command?

**Answer:**
The `-R` option makes `grep` search recursively through all files in the specified directory and its subdirectories.

---

# Question: When `grep` matches patterns in multiple files, how can you prevent it from showing filenames before matched lines?

**Answer:**
Use the `-h` option with `grep` to suppress the filename prefix before matched lines.

---

# Question: Where can you find more detailed information about the `find` and `grep` commands?

**Answer:**
Use `man find` and `man grep` to read the manual pages for these commands.

---

# Question: How do you create an empty text file named `myFile`?

**Answer:**
Use the command `touch myFile` to create an empty file called `myFile`.

---

# Question: Which command renames `myFile` to `myFirstFile`?

**Answer:**
`mv myFile myFirstFile` renames the file from `myFile` to `myFirstFile`.

---

# Question: How can you view the entire contents of a file called `myFirstFile`?

**Answer:**
Use `cat myFirstFile` to view the whole contents of the file.

---

# Question: Which command lets you view a file one screen at a time?

**Answer:**
`less myFirstFile` allows you to view the file contents one screenful at a time.

---

# Question: How do you view the first few lines of a file?

**Answer:**
Use `head myFirstFile` to view the first several lines of the file.

---

# Question: How do you view the last few lines of a file?

**Answer:**
Use `tail myFirstFile` to view the last several lines.

---

# Question: What command opens `myFirstFile` for editing using the vi editor?

**Answer:**
`vi myFirstFile` opens the file in the vi text editor.

---

# Question: How do you list the files in the current working directory?

**Answer:**
Use `ls` to list files in the current directory.

---

# Question: How do you create an empty directory named `myFirstDirectory`?

**Answer:**
Use `mkdir myFirstDirectory` to create the directory.

---

# Question: How do you create nested directories `src/myFirstDirectory` in one command?

**Answer:**
Use `mkdir -p src/myFirstDirectory` to create the directory hierarchy.

---

# Question: How do you move `myFirstFile` into the directory `myFirstDirectory`?

**Answer:**
Use `mv myFirstFile myFirstDirectory/` to move the file.

---

# Question: How do you change the current directory to `myFirstDirectory`?

**Answer:**
Use `cd myFirstDirectory` to change into that directory.

---

# Question: How do you delete a file named `myFirstFile`?

**Answer:**
Use `rm myFirstFile` to delete the file.

---

# Question: How do you move back to the parent directory?

**Answer:**
Use `cd ..` to move to the parent directory.

---

# Question: How do you delete an empty directory named `myFirstDirectory`?

**Answer:**
Use `rmdir myFirstDirectory` to remove an empty directory.

---

# Question: How do you delete a directory and all its contents recursively?

**Answer:**
Use `rm -rf myFirstDirectory` to delete the directory and everything inside it.

---

# Question: What important caution is given about deleting directories?

**Answer:**
Be careful not to delete `/` (root directory), as that will wipe the whole filesystem. Always use `./` for current directory paths.

---

# Question: What does the `ls -l` command display?

**Answer:**
It lists files and directories in long format, showing file permissions, number of links, owner, group, size, last modified date, and file/directory name.

---

# Question: In the permissions string `drwxrwxrwx`, what does the first character represent?

**Answer:**
The first character represents the file type: `d` means directory, `-` means regular file.

---

# Question: What do the groups of `rwx` in the permissions string indicate?

**Answer:**
The first `rwx` are permissions for the user (owner), the second `rwx` are for the group, and the third `rwx` are for others (everyone else).

---

# Question: What do the letters `r`, `w`, and `x` stand for in file permissions?

**Answer:**
`r` stands for read permission, `w` for write (modify) permission, and `x` for execute permission.

---

# Question: How is the permission to modify a file represented numerically when using `chmod`?

**Answer:**
Write permission `w` is represented by the number 2.

---

# Question: How would you set permissions so the owner has full permissions (read, write, execute), and the group and others have read and execute permissions on a directory called `test`?

**Answer:**
Use `chmod 755 test`. This sets permissions as owner: 7 (rwx), group: 5 (r-x), others: 5 (r-x).

---

# Question: What does the `ls -lh` command do?

**Answer:**
It lists files with detailed info (`-l`) and displays file sizes in a human-readable format (`-h`), like KB, MB.

---

# Question: How do you list hidden files in the current directory?

**Answer:**
Use `ls -a` to list all files including hidden ones (those starting with a dot).

---

# Question: What does the `ls -s` command show?

**Answer:**
It shows the size (in blocks) of each file/directory in the current directory.

---

# Question: How can you list all files and directories recursively, including subdirectories and their contents?

**Answer:**
Use `ls -R` to display files and directories recursively.

---

# Question: What command is commonly used to detect the Debian-based Linux distribution name and version?

**Answer:**
`lsb_release -a` displays detailed information about the distribution including Distributor ID, Description, Release, and Codename.

---

# Question: What is an alternative file to check if `lsb_release` is not installed for guessing the Linux distribution?

**Answer:**
You can check the contents of `/etc/issue` to get the distribution name and version.

---

# Question: Why should you avoid using `/etc/debian_version` to detect the Linux distribution name?

**Answer:**
Because `/etc/debian_version` only contains Debian version info and does not accurately represent the distribution name, especially on derivatives like Ubuntu.

---

# Question: What is the preferred method to detect the Linux distribution on modern systemd-based systems?

**Answer:**
Look at the file `/etc/os-release` which contains variables like `NAME`, `VERSION`, `ID`, `VERSION_ID`, and `PRETTY_NAME`.

---

# Question: How can you display the pretty name of your Linux distribution from the `/etc/os-release` file in bash?

**Answer:**
By running:
`( source /etc/os-release && echo "$PRETTY_NAME" )`

---

# Question: Name two Linux distributions where `/etc/os-release` contains detailed distribution information.

**Answer:**
Fedora and CentOS.

---

# Question: Is `/etc/os-release` exclusive to systemd-based systems?

**Answer:**
No, it is documented to exist on all systemd-based distributions but it is not systemd-specific and can be present on other systems too.

---

# Question: How can you detect which RHEL, CentOS, or Fedora distribution you are working in?

**Answer:**
You can look at the contents of the file `/etc/redhat-release` by running `cat /etc/redhat-release`. For example, on a Fedora 24 machine, it outputs:
`Fedora release 24 (Twenty Four)`.

---

# Question: Which command can also be used to detect the Linux distribution and provides detailed information including Distributor ID, Description, Release, and Codename?

**Answer:**
The `lsb_release -a` command can be used to detect the distribution and provides detailed info such as Distributor ID, Description, Release, and Codename. For example, on Fedora 24, it outputs:

```
Distributor ID: Fedora  
Description: Fedora release 24 (Twenty Four)  
Release: 24  
Codename: TwentyFour  
```

---

# Question: What is the purpose of the `uname` command in Linux?

**Answer:**
The `uname` command prints information about the current system, including the kernel name, version, hardware, and operating system details.

---

# Question: What happens when you run `uname` without any options?

**Answer:**
If no option is specified, `uname` assumes the `-s` option and prints the kernel name.

---

# Question: What information does the command `uname -a` provide?

**Answer:**
`uname -a` prints all available system information including kernel name, nodename (hostname), kernel release, kernel version, machine hardware name, processor type, hardware platform, and operating system.

---

# Question: List some of the options available with the `uname` command and what they print.

**Answer:**

* `-s` or `--kernel-name`: Prints the kernel name.
* `-n` or `--nodename`: Prints the network node hostname.
* `-r` or `--kernel-release`: Prints the kernel release.
* `-v` or `--kernel-version`: Prints the kernel version.
* `-m` or `--machine`: Prints the machine hardware name.
* `-p` or `--processor`: Prints the processor type or "unknown".
* `-i` or `--hardware-platform`: Prints the hardware platform or "unknown".
* `-o` or `--operating-system`: Prints the operating system.

---

# Question: Give an example output of `uname -a` on an Arch Linux system.

**Answer:**
An example output of `uname -a` on Arch Linux is:
`Linux nokia 4.6.4-1-ARCH #1 SMP PREEMPT Mon Jul 11 19:12:32 CEST 2016 x86_64 GNU/Linux`

---

# Question: Why is GNU coreutils important in the context of detecting system information?

**Answer:**
GNU coreutils provides fundamental utilities like `uname` which are available on nearly all Linux systems, making it a reliable first tool to gather system information even if you don't know which Linux distribution you are running.

---

# Question: Where can you find the Linux OS name and release number on most Debian and RPM-based distributions?

**Answer:**
Most Linux distributions store their version information in the `/etc/lsb-release` file for Debian-based systems and `/etc/redhat-release` for RPM-based systems. You can use a generic command like `cat /etc/*release` to view this information across most distributions.

---

# Question: What is an example output of the `cat /etc/*release` command on an Ubuntu machine?

**Answer:**
An example output on Ubuntu 14.04 is:

```
DISTRIB_ID=Ubuntu  
DISTRIB_RELEASE=14.04  
DISTRIB_CODENAME=trusty  
DISTRIB_DESCRIPTION="Ubuntu 14.04 LTS"  
```

---

# Question: How can you get complete details of the running Linux kernel?

**Answer:**
Use the command `uname -a` to get complete details of the running Linux kernel, including kernel name, hostname, kernel release, version, machine hardware, processor, hardware platform, and operating system.

---

# Question: What does the `uname -s` option print?

**Answer:**
`uname -s` prints the kernel name.

---

# Question: What is the purpose of the `chsh` command in Linux?

**Answer:**
The `chsh` (change shell) command is used to change the default login shell for a user.

---

# Question: How can you list all the shells installed and configured on your system using `chsh`?

**Answer:**
Run `chsh -l` to list all installed shells. If this option is not valid, you can check the file `/etc/shells` by running `cat /etc/shells`.

---

# Question: How do you change your default shell to `fish`?

**Answer:**
Use the command `chsh -s /usr/bin/fish`, enter your password when prompted, then log off and log back in to use the new shell.

---

# Question: How can an administrator change the default shell for another user named `user_2`?

**Answer:**
The administrator can run `chsh -s /usr/bin/fish user_2` to change the default shell for `user_2`.

---

# Question: How can you check what your current default shell is?

**Answer:**
You can check your current default shell by echoing the `$SHELL` environment variable using `echo $SHELL`.

---

# Question: What are the common options available with the `chsh` command?

**Answer:**

* `-s shell`: Sets the login shell to `shell`.
* `-l` or `--list-shells`: Lists available shells.
* `-h` or `--help`: Displays usage information.
* `-v` or `--version`: Displays version information.

---

# Question: How can you customize the shell prompt to show only the current directory?

**Answer:**
Set `PS1='\w $ '` to make the shell prompt show the current directory name followed by `$`. For example, it will display `~ $` if in the home directory.

---

# Question: What does the prompt `PS1='\h $ '` display?

**Answer:**
It displays the hostname followed by `$`. For example, `gotham $`.

---

# Question: How do you set the shell prompt to show the username only?

**Answer:**
Use `PS1='\u $ '` to display the username followed by `$`, e.g., `bruce $`.

---

# Question: What does `PS1='\t $ '` show in the shell prompt?

**Answer:**
It shows the current time in 24-hour format, like `22:37:31 $`.

---

# Question: Which PS1 value shows the shell prompt with the history number of the command?

**Answer:**
`PS1='! $ '` will display the command history number before the prompt.

---

# Question: What keyboard shortcut cuts or kills the text from the cursor to the end of the line in the shell?

**Answer:**
`Ctrl-k` cuts or kills text from the cursor to the end of the line.

---

# Question: How do you paste the last cut text in the shell?

**Answer:**
Use `Ctrl-y` to yank (paste) the last cut text.

---

# Question: What does pressing `Ctrl-a` do in the shell command line?

**Answer:**
`Ctrl-a` moves the cursor to the start of the line.

---

# Question: How can you clear the terminal screen using a keyboard shortcut?

**Answer:**
Press `Ctrl-l` to clear the screen or terminal.

---

# Question: How can you search your command history in reverse?

**Answer:**
Press `Ctrl-r` to start a reverse search through command history.

---

# Question: Where are the last 500 commands stored in the shell?

**Answer:**
They are stored in the `~/.bash_history` file.

---

# Question: How can you filter your command history to find commands containing a specific keyword?

**Answer:**
Use `history | grep <keyword>` to search the history for commands containing `<keyword>`.

---

# Question: How do you create a command alias in bash?

**Answer:**
You create a command alias by adding a line like `alias command_alias='actual_command'` to your `.bash_aliases` file in your home directory. For example, `alias install='sudo apt-get -y install'` maps the alias `install` to run `sudo apt-get -y install`.

---

# Question: Where should you place your bash command aliases so they load automatically?

**Answer:**
Command aliases should be placed in the `.bash_aliases` file located in your home directory.

---

# Question: How can you quickly locate a file named `mykey.pem` on your system?

**Answer:**
Use the command `locate mykey.pem` to quickly find the file using a cached database.

---

# Question: How can you combine `locate` and `grep` to find files containing both "mykey" and "pem" in their names?

**Answer:**
Use a pipe to combine the commands: `locate pem | grep mykey`.

---

# Question: What should you do if the `locate` command is not available or not enabled on your system?

**Answer:**
You can manually update the locate database with `updatedb`, or use the `find` command like `find / -name mykey.pem -print` to search the filesystem directly.

---

# Question: What is the main difference between `locate` and `find` commands?

**Answer:**
`locate` uses a cached database to quickly find files but may not reflect recent changes unless updated. `find` scans the filesystem in real-time, which is slower but always up-to-date.

---

# Question: What does the `du -sh *` command do?

**Answer:**
It summarizes and displays the disk usage of all files and directories in the current directory in a human-readable format, showing only total sizes for each.

---

# Question: How do you include hidden files when checking disk usage with `du`?

**Answer:**
Use `du -sh .[!.]* *` to include hidden files (those starting with a dot) along with regular files.

---

# Question: What option can you add to `du` to show a total summary at the end of the output?

**Answer:**
Add the `-c` option to `du`, like `du -sch .[!.]* *`, to display a grand total of disk usage.

---

# Question: Why is using `du` on the root directory useful?

**Answer:**
It helps identify which directories or applications are consuming the most disk space, which is essential for troubleshooting disk space issues on critical servers.

---

# Question: How can you list directories under root that consume more than 1GB of disk space?

**Answer:**
Use the command `sudo du --threshold=1G -ch /.[!.]* /*` to display directories larger than 1GB with a total at the end.

---

# Question: What is the meaning of the `-s` and `-h` options in `du`?

**Answer:**
`-s` summarizes disk usage for each argument (instead of showing usage for each file inside directories), and `-h` formats the output in human-readable units (e.g., K, M, G).

---

# Question: What does the error "du: cannot access ..." during a disk usage scan usually indicate?

**Answer:**
It indicates permission issues or that some special or transient files (like those in `/proc`) are inaccessible or no longer exist during the scan.

---

# Question: Which command is commonly used to check disk space usage on partitions and mounted drives?

**Answer:**
The `df -h` command is used to display disk space usage in a human-readable format for all mounted filesystems.

---

# Question: What does the `-h` option do in the `df` command?

**Answer:**
The `-h` option formats the output sizes into human-readable units such as KB, MB, or GB.

---

# Question: In the output of `df -h`, what does the "Use%" column represent?

**Answer:**
The "Use%" column shows the percentage of disk space used on each filesystem or partition.

---

# Question: What information does the "Mounted on" column in `df -h` output provide?

**Answer:**
It shows the directory path where the filesystem or partition is mounted in the directory tree.

---

# Question: How can you identify from `df -h` output if a partition is almost full?

**Answer:**
If the "Use%" value is high (close to 100%), such as 95%, it indicates the partition is nearly full.

---

# Question: What types of filesystems or mounts might appear in `df -h` output besides physical partitions?

**Answer:**
You might see tmpfs (RAM disks), network mounts (like NFS or CIFS), and logical volume manager (LVM) partitions.

---

# Question: Which command provides real-time CPU statistics with intervals and counts?

**Answer:**
The `mpstat` command provides CPU statistics in real time, e.g., `mpstat 2 10` shows stats every 2 seconds, 10 times.

---

# Question: What command can you use to get detailed memory and I/O statistics over time?

**Answer:**
The `vmstat` command shows memory, CPU, and I/O statistics, e.g., `vmstat 2 10` updates every 2 seconds for 10 iterations.

---

# Question: Which tool is used to display real-time disk I/O statistics?

**Answer:**
`iostat` with options like `-kx` shows detailed disk I/O statistics, e.g., `iostat -kx 2` updates every 2 seconds.

---

# Question: How can you list all open TCP sockets on your system?

**Answer:**
Using the command `netstat -ntlp` will show all open TCP sockets with listening ports and associated processes.

---

# Question: What command can be used to monitor network traffic in real-time interactively?

**Answer:**
`iftop` is used for interactive real-time network traffic monitoring.

---

# Question: What is the purpose of the `dstat` command?

**Answer:**
`dstat` is a versatile monitoring tool that can replace vmstat, iostat, and ifstat by generating combined real-time statistics on CPU, disk, network, and I/O.

---

# Question: Which command provides detailed CPU architecture and configuration information?

**Answer:**
The `lscpu` command shows CPU details such as architecture, number of cores, threads, vendor ID, and cache sizes.

---

# Question: How do you extract CPU information using `lshw`?

**Answer:**
You can run `lshw | grep cpu` to filter out CPU-related hardware details from the full hardware listing.

---

# Question: What kind of information does `lscpu` output include about the CPU?

**Answer:**
`lscpu` outputs architecture, CPU modes (32-bit/64-bit), CPU count, cores per socket, threads per core, CPU MHz, cache sizes, virtualization support, and vendor info.

---

# Question: How does `lshw` report CPU speed and vendor?

**Answer:**
`lshw` outputs lines such as `product: Intel(R) Pentium(R) CPU G3220 @ 3.00GHz` and `vendor: Intel Corp.` along with size (speed) and width (bitness).

---

# Question: What command on Ubuntu lists detailed hardware configuration, including CPU, memory, firmware, and bus speed?

**Answer:**
`sudo lshw` lists detailed hardware configuration.

---

# Question: How can you generate an HTML report of your hardware using `lshw`?

**Answer:**
`sudo lshw -html > myhardware.html`

---

# Question: Which command displays PCI device information in a tree view?

**Answer:**
`lspci -tv`

---

# Question: How do you list detailed USB device information?

**Answer:**
`lsusb -tv`

---

# Question: What command can you use to view BIOS information?

**Answer:**
`dmidecode -q | less`

---

# Question: How can you find disk-specific information for `/dev/sda`?

**Answer:**
`hdparm -i /dev/sda`

---

# Question: What command shows how long a disk has been powered on?

**Answer:**
`smartctl -A /dev/sda | grep Power_On_Hours`

---

# Question: How do you perform a read speed test on disk `/dev/sda`?

**Answer:**
`hdparm -tT /dev/sda`

---

# Question: Which command tests for unreadable blocks on a disk?

**Answer:**
`badblocks -s /dev/sda`

---

# Question: How do you get CPU model and speed info from the `/proc` filesystem?

**Answer:**
`cat /proc/cpuinfo`

---

# Question: What command counts the number of processors or cores on a system?

**Answer:**
`grep -c processor /proc/cpuinfo`

---

