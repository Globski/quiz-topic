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

