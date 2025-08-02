# Question: What is Git primarily used for?

**Answer:** Git is used to save and manage different versions of files and code, work with others, keep track of changes, and undo mistakes.

---

# Question: What is a remote repository in Git?

**Answer:** A remote repository is an online service like GitHub, GitLab, or Bitbucket where Git projects can be shared and collaborated on.

---

# Question: Where can Git be used?

**Answer:** Git can be used on a local computer and with online services like GitHub, GitLab, or Bitbucket.

---

# Question: What does the command `git --version` do?

**Answer:** The command `git --version` checks and displays the currently installed Git version on your system.

---

# Question: What is the output of the command `git --version` if Git version 2.30.2.windows.1 is installed?

**Answer:** The output is `git version 2.30.2.windows.1`.

---

# Question: Who created Git, and who maintains it now?

**Answer:** Git was created by Linus Torvalds in 2005 and has been maintained by Junio Hamano since then.

---

# Question: What type of system is Git?

**Answer:** Git is a version control system.

---

# Question: What are the three main uses of Git?

**Answer:** Tracking code changes, tracking who made changes, and supporting coding collaboration.

---

# Question: What is a repository in Git?

**Answer:** A repository is a folder where Git tracks your project and its history.

---

# Question: What does the `clone` action in Git do?

**Answer:** It creates a copy of a remote repository on your computer.

---

# Question: What does it mean to "stage" changes in Git?

**Answer:** Staging means telling Git which changes you want to save in the next commit.

---

# Question: What is a commit in Git?

**Answer:** A commit is a snapshot of the staged changes that is saved permanently.

---

# Question: What is a branch in Git?

**Answer:** A branch allows you to work on different versions or features of a project at the same time.

---

# Question: What does the `merge` command do in Git?

**Answer:** Merge combines changes from different branches into a single branch.

---

# Question: What does `pull` mean in Git?

**Answer:** Pull means downloading the latest changes from a remote repository to your local machine.

---

# Question: What does `push` do in Git?

**Answer:** Push uploads your local commits to a remote repository.

---

# Question: What does initializing Git on a folder do?

**Answer:** It makes the folder a Git repository and creates a hidden `.git` folder to track changes.

---

# Question: What happens when you change, add, or delete a file in a Git-tracked folder?

**Answer:** The file is considered modified.

---

# Question: What must happen before committing changes in Git?

**Answer:** Modified files must be staged.

---

# Question: What does committing staged files do?

**Answer:** It stores a permanent snapshot of the staged files.

---

# Question: Can you view the full history of commits in Git?

**Answer:** Yes, Git allows viewing the full history of every commit.

---

# Question: Can Git revert to any previous commit?

**Answer:** Yes, Git allows reverting to any previous commit.

---

# Question: Does Git store separate copies of every file in each commit?

**Answer:** No, Git tracks the changes made in each commit rather than storing full copies of files.

---

# Question: What are the benefits of Git for developers working remotely?

**Answer:** Developers can collaborate from anywhere, view full project history, and revert to earlier versions.

---

# Question: Which Git operations interact with remote repositories?

**Answer:** Only `push` and `pull` interact with remote servers like GitHub, GitLab, or Bitbucket.

---

# Question: Where do most Git actions take place?

**Answer:** Most Git actions like staging, committing, and viewing history happen locally on your own computer.

---

# Question: Is Git the same as GitHub?

**Answer:** No, Git is a version control system, while GitHub is a platform that provides tools built around Git.

---

# Question: What is GitHub?

**Answer:** GitHub is the largest host of source code in the world, and it provides tools for working with Git.

---

# Question: Who owns GitHub, and since when?

**Answer:** Microsoft owns GitHub, since 2018.

---

# Question: Where can you download Git for free?

**Answer:** Git can be downloaded for free from [https://git-scm.com](https://git-scm.com).

---

# Question: How do you install Git on Windows?

**Answer:** Download and run the installer from git-scm.com, then click "Next" to accept the recommended settings. This installs Git and Git Bash.

---

# Question: What does the Git installer include on Windows?

**Answer:** It installs both Git and Git Bash.

---

# Question: How do you install Git on macOS using Homebrew?

**Answer:** Open Terminal and type:
`brew install git`

---

# Question: What is an alternative method to install Git on macOS if not using Homebrew?

**Answer:** Download the `.dmg` file from git-scm.com and drag Git to the Applications folder.

---

# Question: How do you install Git on Ubuntu Linux?

**Answer:** Use the terminal and type:
`sudo apt-get install git`

---

# Question: What can you do after installing Git?

**Answer:** You can use Git from your terminal or command prompt.

---

# Question: What is Git Bash?

**Answer:** Git Bash is a terminal for Windows that lets you use Git commands and additional Unix commands.

---

# Question: Where can you find Git Bash after installing Git on Windows?

**Answer:** In the Start menu under "Git Bash".

---

# Question: What command do you use to verify that Git is installed?

**Answer:**
`git --version`

---

# Question: What is the expected output if Git is installed correctly?

**Answer:** A version message like `git version 2.43.0.windows.1`.

---

# Question: What should you do if `git --version` gives an error after installation?

**Answer:** Try closing and reopening your terminal, or check if Git is in your system’s PATH.

---

# Question: What does Git ask you to select during installation?

**Answer:** A default text editor for writing messages such as commit messages.

---

# Question: What is the command to set VS Code as your default Git editor?

**Answer:**
`git config --global core.editor "code --wait"`

---

# Question: What is the command to set Notepad as the default Git editor?

**Answer:**
`git config --global core.editor "notepad"`

---

# Question: What does it mean to add Git to your PATH?

**Answer:** It means you can run Git commands from any terminal window, not just Git Bash or Terminal.

---

# Question: What happens if Git is not added to your PATH during installation?

**Answer:** You can only use Git in Git Bash (on Windows) or Terminal (on macOS/Linux).

---

# Question: How can you check if Git is in your PATH?

**Answer:** Run `git --version`; if it works, Git is in your PATH.

---

# Question: How do you manually add Git to the PATH on Windows after installation?

**Answer:**

1. Open "Environment Variables" from the Start menu.
2. Click "Environment Variables..." → Find "Path" under "System variables".
3. Click "Edit" → "New" → Add paths like `C:\Program Files\Git\bin` and `C:\Program Files\Git\cmd`.
4. Click OK and restart your terminal.

---

# Question: How do you add Git to your PATH on macOS if not set automatically?

**Answer:**
Add the line `export PATH="/usr/local/bin:$PATH"` to `~/.zshrc` or `~/.bash_profile`, then run `source ~/.zshrc` or `source ~/.bash_profile`.

---

# Question: How do you add Git to PATH on Linux if it's not added by default?

**Answer:**
Add `export PATH="/usr/bin:$PATH"` to your `~/.bashrc` or `~/.profile`, then run `source ~/.bashrc` or `source ~/.profile`.

---

# Question: What should you do after updating the PATH variable?

**Answer:** Open a new terminal window and run `git --version` to verify it works.

---

# Question: What are line endings, and how should they be configured on Windows?

**Answer:** Line endings are character sequences that mark the end of a line in text files. On Windows, it's best to select "Checkout Windows-style, commit Unix-style line endings" to avoid cross-platform issues.

---

# Question: How do you update Git?

**Answer:** Download and run the latest installer or use a package manager like `brew upgrade git` or `sudo apt-get upgrade git`.

---

# Question: How do you uninstall Git on Windows?

**Answer:** Use "Add or Remove Programs" from the Windows Control Panel.

---

# Question: How do you uninstall Git on macOS or Linux?

**Answer:** Use your system’s package manager.

---

# Question: What should you try if Git doesn’t work after installing?

**Answer:** Close and reopen your terminal, or restart your computer.

---

# Question: What causes the error “git is not recognized as an internal or external command”?

**Answer:** Git is not in your system’s PATH.

---

# Question: What is the solution for the "git is not recognized" error?

**Answer:** Ensure Git is installed, add Git’s `bin` folder to your PATH, and restart your terminal or computer.

---

# Question: What should you do if you get a "Permission denied" error?

**Answer:** Run Git Bash as administrator on Windows, or use `sudo` on macOS/Linux.

---

# Question: What can cause SSL or HTTPS errors when cloning or pushing?

**Answer:** A poor internet connection or outdated Git version.

---

# Question: What should you do if you have the wrong version of Git installed?

**Answer:** Check your version with `git --version` and download the latest version from git-scm.com.

---

# Question: Why is configuring Git important?

**Answer:** Git uses your name and email to label your commits, allowing version control systems to track who made each change.

---

# Question: What command sets your Git username globally?

**Answer:**
`git config --global user.name "Your Name"`

---

# Question: What command sets your Git email address globally?

**Answer:**
`git config --global user.email "you@example.com"`

---

# Question: What does the `--global` flag do in Git configuration?

**Answer:** It sets the configuration value for all repositories of the current user.

---

# Question: What happens if you make a typo in your Git username or email?

**Answer:** You can re-run the `git config` command with the correct value to overwrite the old one.

---

# Question: What will Git do if you try to commit without setting your name or email?

**Answer:** Git will prompt you to set them before allowing the commit.

---

# Question: Can you change your Git name and email later?

**Answer:** Yes, and previous commits will still show the old name and email.

---

# Question: What is the difference between `--global` and `--local` in Git config?

**Answer:** `--global` sets the value for every repository on the computer, while `--local` sets it only for the current repository.

---

# Question: What is the default configuration level if no flag is specified in `git config`?

**Answer:** Local (`--local`) is the default.

---

# Question: What command lists all Git configuration settings?

**Answer:**
`git config --list`

---

# Question: What is the output format of `git config --list`?

**Answer:** A list of key-value pairs like `user.name=Your Name`.

---

# Question: What command displays only the configured Git user name?

**Answer:**
`git config user.name`

---

# Question: How do you unset a global configuration value in Git?

**Answer:**
`git config --global --unset <key>`

Example:
`git config --global --unset code.editor`

---

# Question: How do you set the default branch name for new repositories in Git?

**Answer:**
`git config --global init.defaultBranch main`

---

# Question: What are the three Git configuration levels?

**Answer:**

* System (`--system`)
* Global (`--global`)
* Local (`--local`)

---

# Question: What is the order of precedence for Git config levels (highest to lowest)?

**Answer:**

1. Local
2. Global
3. System

---

# Question: Why would you use different Git config levels?

**Answer:** To set different values for different users, projects, or repositories—for example, different default branches or user identities.

---

# Question: How do you set a Git user name for just one repository?

**Answer:**
`git config user.name "Project Name"`

---

# Question: How do you set a Git user name for all repositories of the current user?

**Answer:**
`git config --global user.name "Global Name"`

---

# Question: How do you set a Git user name for all users on the system?

**Answer:**
`git config --system user.name "System Name"`

---

# Question: What are the three key steps to getting started with Git?

**Answer:** Create a project folder, navigate to the folder, and initialize a Git repository.

---

# Question: How do you open Git Bash in a specific folder on Windows?

**Answer:** Right-click the folder in File Explorer and select "Git Bash Here".

---

# Question: What does the command `git init` do?

**Answer:** It initializes a new Git repository in the current folder by creating a `.git` directory.

---

# Question: What is the output message after running `git init`?

**Answer:**
`Initialized empty Git repository in /Users/user/myproject/.git/`

---

# Question: What is a Git repository?

**Answer:** A Git repository is a folder that Git tracks for changes, storing the project’s history and versions.

---

# Question: What happens behind the scenes when you run `git init`?

**Answer:** Git creates a hidden folder called `.git` that stores all the tracking and history data.

---

# Question: What command shows hidden folders like `.git` on Linux or macOS?

**Answer:**
`ls -a`

---

# Question: How do you view the `.git` folder on Windows?

**Answer:** Enable "Show hidden files" in File Explorer.

---

# Question: What is the cause of the error `git: command not found`?

**Answer:** Git is either not installed or not added to the system’s PATH.

---

# Question: What is the solution to `git: command not found`?

**Answer:** Make sure Git is installed, added to your PATH, and restart your terminal if needed.

---

# Question: What causes a "Permission denied" error when using Git?

**Answer:** Insufficient privileges to perform Git operations in the terminal.

---

# Question: How can you fix a "Permission denied" error in Git?

**Answer:** Run the terminal as administrator (on Windows) or use `sudo` on macOS/Linux.

---

# Question: What is a "new file" in the context of Git?

**Answer:** A new file is one that has been created or copied into the project folder but has not yet been added to Git's tracking system.

---

# Question: What command checks which files Git is tracking?

**Answer:** `git status`

---

# Question: What does it mean when a file is listed as "untracked" in `git status`?

**Answer:** It means the file exists in the project folder, but Git is not tracking changes to it because it hasn't been added to the repository.

---

# Question: What does Git suggest when it finds untracked files?

**Answer:** Git suggests using `git add ...` to include the files in what will be committed.

---

# Question: How does Git label the first file when `git status` is run before any commits?

**Answer:** As an "untracked file"

---

# Question: What Git branch is active by default in the `git status` output?

**Answer:** `master`

---

# Question: What does it mean if `git status` shows "No commits yet"?

**Answer:** It means no changes have been committed to the repository yet.

---

# Question: What does `git status` output when there are untracked files but nothing has been added to the commit?

**Answer:** It shows the list of untracked files and suggests using `git add` to track them.

---

# Question: What is a "tracked file" in Git?

**Answer:** A tracked file is one that Git is monitoring for changes.

---

# Question: How do you convert an untracked file to a tracked file in Git?

**Answer:** By using the `git add` command to add it to the staging area.

---

# Question: What command can help confirm you're in the correct folder if a file doesn't show up with `ls`?

**Answer:** `pwd`

---

# Question: What should you check if `git status` does not list a file you expect?

**Answer:** Ensure you're in the correct folder and that the file has been saved properly.

---
