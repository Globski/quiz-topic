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

# Question: What is the purpose of the staging environment in Git?

**Answer:** It allows you to control which changes are included in the next commit by staging specific files before committing.

---

# Question: What Git command stages a specific file?

**Answer:** `git add <file>`

---

# Question: What does `git add index.html` do?

**Answer:** It stages the file `index.html` so it will be included in the next commit.

---

# Question: What command stages all changes in the working directory, including new, modified, and deleted files?

**Answer:** `git add --all` or `git add -A`

---

# Question: Are `git add --all` and `git add -A` functionally the same?

**Answer:** Yes, they both stage all changes in the working directory.

---

# Question: How can you see which files are currently staged?

**Answer:** By running `git status`

---

# Question: In the output of `git status`, what section shows staged files?

**Answer:** The "Changes to be committed" section.

---

# Question: What command removes a file from the staging area?

**Answer:** `git restore --staged <file>`

---

# Question: What is the effect of running `git restore --staged index.html`?

**Answer:** It unstages `index.html`, removing it from the staging area but leaving the file unchanged in the working directory.

---

# Question: What is an alternative command to unstage a file besides `git restore --staged`?

**Answer:** `git reset HEAD <file>`

---

# Question: What should you do if you forgot to stage a file before committing?

**Answer:** Run `git add <file>` to stage it before committing.

---

# Question: What command helps you verify what will be included in the next commit?

**Answer:** `git status`

---

# Question: What does Git suggest using in the `git status` output to unstage a file?

**Answer:** `git restore --staged <file>`

---

# Question: What is a commit in Git?

**Answer:** A commit is a save point in your project that records a snapshot of your files at a particular time along with a message describing what changed.

---

# Question: What command is used to commit staged changes with a message?

**Answer:** `git commit -m "message"`

---

# Question: What does `git commit -m "First release of Hello World!"` do?

**Answer:** It commits all staged changes with the commit message "First release of Hello World!"

---

# Question: What command commits all modified and deleted tracked files without staging them first?

**Answer:** `git commit -a -m "message"`

---

# Question: Does `git commit -a -m` commit new/untracked files?

**Answer:** No, it only commits tracked files. New/untracked files must be added with `git add` first.

---

# Question: What is the risk of using `git commit -a -m`?

**Answer:** It can include unwanted changes since it skips the staging step, so it should be used with care.

---

# Question: What happens if you run `git commit -a -m` with only new/untracked files?

**Answer:** Git will return a message saying "nothing added to commit but untracked files present," and the commit won't happen.

---

# Question: What command opens your default editor for writing a multi-line commit message?

**Answer:** `git commit` (without the `-m` flag)

---

# Question: How should you format a multi-line commit message?

**Answer:** Start with a short summary on the first line, leave a blank line, then write detailed information below.

---

# Question: What are three best practices for writing commit messages?

**Answer:**

1. Keep the first line short (50 characters or less).
2. Use the imperative mood.
3. Leave a blank line between the summary and the details.

---

# Question: What command creates an empty commit?

**Answer:** `git commit --allow-empty -m "message"`

---

# Question: What command reuses the previous commit message without opening an editor?

**Answer:** `git commit --no-edit`

---

# Question: What command amends the last commit without changing its message?

**Answer:** `git commit --amend --no-edit`

---

# Question: What command do you use if you forgot to stage a file before committing?

**Answer:** Stage the file with `git add <file>` and run `git commit --amend` to include it in the last commit.

---

# Question: How do you correct a typo in the most recent commit message?

**Answer:** Use `git commit --amend -m "Corrected message"`

---

# Question: What command undoes the last commit but keeps the changes staged?

**Answer:** `git reset --soft HEAD~1`

---

# Question: What command shows the full commit history?

**Answer:** `git log`

---

# Question: What information does `git log` display for each commit?

**Answer:** Commit hash, author, date, and commit message.

---

# Question: What command gives a one-line summary of each commit?

**Answer:** `git log --oneline`

---

# Question: What command shows which files changed in each commit?

**Answer:** `git log --stat`

---

# Question: What is a tag in Git?

**Answer:** A tag is a label or bookmark for a specific commit, commonly used to mark important points like releases, milestones, or deployment versions.

---

# Question: What command creates a lightweight tag?

**Answer:** `git tag <tagname>`

---

# Question: What is the difference between a lightweight tag and an annotated tag?

**Answer:** A lightweight tag is just a name for a commit and stores no additional information. An annotated tag includes metadata such as the tagger's name, date, and a message.

---

# Question: What command creates an annotated tag with a message?

**Answer:** `git tag -a <tagname> -m "message"`

---

# Question: Which tag type is recommended for public sharing and releases?

**Answer:** Annotated tags

---

# Question: What command tags a specific commit by its hash?

**Answer:** `git tag <tagname> <commit-hash>`

---

# Question: What command lists all tags in the current Git repository?

**Answer:** `git tag`

---

# Question: What command displays details of a specific tag and its associated commit?

**Answer:** `git show <tagname>`

---

# Question: What is the command to push a single tag to a remote repository?

**Answer:** `git push origin <tagname>`

---

# Question: What command pushes all local tags to the remote repository?

**Answer:** `git push --tags`

---

# Question: Are tags pushed automatically when running `git push`?

**Answer:** No, tags are not pushed automatically; you must explicitly push them using `git push origin <tagname>` or `git push --tags`.

---

# Question: What command deletes a tag from the local repository?

**Answer:** `git tag -d <tagname>`

---

# Question: What command deletes a tag from the remote repository?

**Answer:** `git push origin --delete tag <tagname>`

---

# Question: What command updates or replaces a tag locally by moving it to a new commit?

**Answer:** `git tag -f <tagname> <new-commit-hash>`

---

# Question: After force-updating a tag locally, what command must you use to overwrite it remotely?

**Answer:** `git push --force origin <tagname>`

---

# Question: Why should you use annotated tags for releases and shared versions?

**Answer:** Because they store extra metadata and are more informative, making them suitable for collaboration and version tracking.

---

# Question: When is it recommended to create a tag?

**Answer:** After passing all tests or before deploying/releasing code.

---

# Question: How should you resolve a tag that already exists but needs to be changed?

**Answer:** Delete it with `git tag -d <tagname>`, then re-create it and push again.

---

# Question: What should you do if a tag isn’t visible on the remote after pushing commits?

**Answer:** Push the tag explicitly using `git push origin <tagname>` or `git push --tags`.

---

# Question: What is the risk of using `git push --force origin <tagname>`?

**Answer:** It forcefully updates the tag on the remote, potentially overwriting it for others, which can cause inconsistencies.

---

# Question: What are some common use cases for Git tags?

**Answer:** Marking releases, highlighting milestones, managing deployments, and applying hotfixes to specific versions.

---

# Question: What is the purpose of `git stash`?

**Answer:** To temporarily save uncommitted changes (staged and unstaged tracked files) and return to a clean working directory without committing them.

---

# Question: What types of files are stashed by default with `git stash`?

**Answer:** Tracked files, both staged and unstaged.

---

# Question: How can you include untracked files in a stash?

**Answer:** Use `git stash -u` or `git stash --include-untracked`.

---

# Question: What command adds a message to your stash?

**Answer:** `git stash push -m "message"`

---

# Question: What is the benefit of using `git stash push -m "message"`?

**Answer:** It lets you label your stash with a descriptive message to remember what work was saved.

---

# Question: What command lists all saved stashes?

**Answer:** `git stash list`

---

# Question: What format is used in the stash list to identify individual stashes?

**Answer:** `stash@{n}`, where `n` is the stash index.

---

# Question: What is a stash stack in Git?

**Answer:** A stack-like structure where each stash is added to the top and can be applied, dropped, or inspected.

---

# Question: What command shows a summary of changes in the latest stash?

**Answer:** `git stash show`

---

# Question: What command displays the full diff of changes in the latest stash?

**Answer:** `git stash show -p`

---

# Question: How do you apply the most recent stash without removing it from the stack?

**Answer:** `git stash apply`

---

# Question: What command applies a specific stash from the list?

**Answer:** `git stash apply stash@{n}`

---

# Question: What is the difference between `git stash apply` and `git stash pop`?

**Answer:** `git stash apply` restores the stash but keeps it in the list; `git stash pop` restores it and removes it from the stack.

---

# Question: What command restores and removes the most recent stash?

**Answer:** `git stash pop`

---

# Question: What command deletes a specific stash from the stack?

**Answer:** `git stash drop stash@{n}`

---

# Question: What command clears all saved stashes?

**Answer:** `git stash clear`

---

# Question: What is a caution related to `git stash clear`?

**Answer:** It is irreversible; all stashes will be deleted permanently.

---

# Question: How can you create a new branch from a specific stash?

**Answer:** `git stash branch <branchname> stash@{n}`

---

# Question: What happens when you run `git stash branch new-feature stash@{0}`?

**Answer:** Git creates a new branch called `new-feature`, switches to it, applies `stash@{0}`, and removes it from the stash list.

---

# Question: What are two common use cases for stashing changes?

**Answer:**

1. Switching branches safely
2. Saving work during an emergency fix

---

# Question: Are untracked files included in a stash by default?

**Answer:** No, they must be explicitly included using `-u` or `--include-untracked`.

---

# Question: What should you do if a stash doesn't apply cleanly?

**Answer:** Resolve conflicts manually, similar to a merge conflict. Git will mark the conflicts for you.

---

# Question: How can you recover lost work you believe was stashed?

**Answer:** Use `git stash list` to locate the stash, then apply it with `git stash apply stash@{n}`.

---

# Question: What is a best practice for naming stashes?

**Answer:** Use descriptive messages like `git stash push -m "WIP: feature name"`.

---

# Question: Why shouldn't you use stashes as long-term storage?

**Answer:** Because stashes are temporary and can be lost; it's better to commit your work when possible.

---

# Question: What is the purpose of Git History?

**Answer:** Git History records every change made to a project, including what changed, when, and who made the change, helping in tracking progress, finding bugs, and understanding project evolution.

---

# Question: What command shows the full commit history in Git?

**Answer:** `git log`

---

# Question: What information does the `git log` command display for each commit?

**Answer:** It shows the commit hash, author, date, and commit message.

---

# Question: How can you display each commit on a single line for easier reading?

**Answer:** Use `git log --oneline`

---

# Question: What does the `git show <commit>` command do?

**Answer:** It displays detailed information about a specific commit, including who made it, when, the message, and the exact changes.

---

# Question: What does the command `git diff` show?

**Answer:** It shows unstaged changes — differences between the working directory and the last commit.

---

# Question: What does the command `git diff --staged` show?

**Answer:** It shows differences between staged files and the last commit (i.e., staged changes ready to be committed).

---

# Question: How do you compare the differences between two specific commits?

**Answer:** Use `git diff <commit1> <commit2>`

---

# Question: What does `git log --author="Alice"` do?

**Answer:** It shows only the commits made by the author "Alice".

---

# Question: What command shows only commits made in the last two weeks?

**Answer:** `git log --since="2 weeks ago"`

---

# Question: What does `git log --stat` provide that `git log` does not?

**Answer:** It shows which files were changed in each commit and how many lines were added or removed.

---

# Question: How can you visualize the history of branches and merges?

**Answer:** Use `git log --graph` or `git log --graph --oneline` for a simplified view.

---

# Question: How can you scroll while viewing the full log using `git log`?

**Answer:** Use the arrow keys.

---

# Question: How can you quit the `git log` or `git diff` view?

**Answer:** Press `q`.

---

# Question: While viewing `git log`, how can you search for a specific word?

**Answer:** Type `/` followed by the search term, then press `n` to jump to the next match.

---

# Question: What is a best practice when writing commits to keep Git history useful?

**Answer:** Make frequent, meaningful commits with clear commit messages.

---

# Question: Why is it recommended to use `git diff` before committing?

**Answer:** To review your work and ensure only intended changes are included in the commit.

---

# Question: What is the output format of `git log --oneline`?

**Answer:** Each commit is shown on a single line with its abbreviated hash and message.

---

# Question: What output does the `git diff` command produce for a modified file?

**Answer:** It shows lines removed (with `-`) and lines added (with `+`) for each file modified.

---

# Question: If your changes don’t appear in the history, what might be the reason?

**Answer:** The changes are not yet committed.

---

# Question: If the commit history is too long to read, what commands can simplify it?

**Answer:** Use `git log --oneline` or `git log --since` to shorten the output.

---

# Question: What does the following command do: `git show 09f4acd`?

**Answer:** It shows full details of the commit with hash prefix `09f4acd`, including changes made.

---

# Question: In the example `git diff 1234567 89abcde`, what are `1234567` and `89abcde`?

**Answer:** They are abbreviated commit hashes used to compare two specific commits.

---

# Question: What kind of graph does `git log --graph` produce?

**Answer:** A simple ASCII graph showing branch and merge history.

---

# Question: What does the command `git log --graph --oneline` combine?

**Answer:** It combines a visual branch graph with a condensed single-line format of commits.

---

# Question: What does this example from `git log --stat` indicate: `1 file changed, 1 insertion(+), 1 deletion(-)`?

**Answer:** One file was modified, with one line added and one line removed.

---

# Question: Why is Git's built-in help system useful?

**Answer:** It provides quick access to command usage, options, and guides without leaving the terminal, making it helpful when you forget how a command works or want to explore its options.

---

# Question: What command displays the full manual for a specific Git command?

**Answer:** `git help <command>`

---

# Question: What is an alternative syntax to `git help <command>` that performs the same function?

**Answer:** `git <command> --help`

---

# Question: Which command provides a quick summary of a Git command’s options?

**Answer:** `git <command> -h`

---

# Question: What command lists all Git commands grouped by category?

**Answer:** `git help --all`

---

# Question: How do you view a list of Git guides and concepts?

**Answer:** `git help -g`

---

# Question: What information does `git help commit` show?

**Answer:** It shows the full manual page for the `git commit` command, including its name, synopsis, description, options, and usage examples.

---

# Question: What is the `SYNOPSIS` section in a Git help page?

**Answer:** It describes the basic usage format and arguments of the Git command.

---

# Question: While viewing help pages in the terminal, how can you scroll down and up?

**Answer:** Use the arrow keys or Space to scroll down and `b` to scroll up.

---

# Question: In Git help viewer, how do you search for a word?

**Answer:** Press `/`, type the search term, and press Enter. Then press `n` to find the next match.

---

# Question: How do you exit the Git help viewer?

**Answer:** Press `q`.

---

# Question: What does the command `git status --help` do?

**Answer:** It opens the full documentation for the `git status` command.

---

# Question: What does the command `git add -h` show?

**Answer:** It shows a short summary of available options for the `git add` command without opening the full manual.

---

# Question: What is shown in the output of `git help --all`?

**Answer:** A very long list of all available Git commands grouped by categories such as Main Porcelain Commands, Ancillary Commands, Low-level Commands, and External Commands.

---

# Question: Name a few commands listed under “Main Porcelain Commands” from `git help --all`.

**Answer:** `add`, `commit`, `branch`, `merge`, `status`, `log`, `push`, `pull`, `checkout`

---

# Question: What category do commands like `config`, `remote`, and `reflog` belong to?

**Answer:** Ancillary Commands / Manipulators

---

# Question: What is the category of `blame`, `annotate`, and `count-objects` in the Git help listing?

**Answer:** Ancillary Commands / Interrogators

---

# Question: What is the purpose of commands like `cat-file`, `ls-tree`, and `rev-list`?

**Answer:** These are Low-level Commands / Interrogators, used to inspect and analyze the state and contents of the repository at a granular level.

---

# Question: Which Git command lists references in a remote repository?

**Answer:** `ls-remote`

---

# Question: Which command allows you to compare two commit ranges?

**Answer:** `range-diff`

---

# Question: What is the purpose of `git show-branch`?

**Answer:** It shows branches and their commits.

---

# Question: What command would you use to verify the GPG signature of commits?

**Answer:** `verify-commit`

---

# Question: Which command lets you manage multiple working trees in Git?

**Answer:** `worktree`

---

# Question: What command helps reuse recorded resolution of conflicted merges?

**Answer:** `rerere`

---

# Question: What is `git instaweb` used for?

**Answer:** It instantly launches a web browser interface (gitweb) for the current repository.

---

# Question: What is the function of the command `git maintenance`?

**Answer:** It runs tasks to optimize Git repository data.

---

# Question: If the list in `git help --all` is too long, what key combination jumps to the end?

**Answer:** Press `SHIFT + G`.

---

# Question: How do you exit the list view in `git help --all`?

**Answer:** Press `q`.

---

# Question: What command group includes tools like `imap-send`, `send-email`, and `request-pull`?

**Answer:** Interacting with Others

---

# Question: Which command category includes `apply`, `read-tree`, and `hash-object`?

**Answer:** Low-level Commands / Manipulators

---

# Question: Which command allows you to create a tree object from the current index?

**Answer:** `write-tree`

---

# Question: What command shows available Git guides like “glossary” or “everyday”?

**Answer:** `git help -g`

---

# Question: What topics are included in the output of `git help -g`?

**Answer:** Guides like `attributes`, `everyday`, `glossary`, and `revisions`.

---

# Question: What can you do if the Git help page doesn’t open?

**Answer:** Try `git <command> -h` for a quick summary instead.

---

# Question: What is a Git branch?

**Answer:** A Git branch is a separate workspace that allows changes and experimentation without affecting the main project.

---

# Question: Why are Git branches useful?

**Answer:** They enable isolated work on features, bug fixes, or ideas without interfering with the main branch.

---

# Question: What are three common reasons to create a branch?

**Answer:** Developing a new feature, fixing a bug, and experimenting with ideas.

---

# Question: What does branching in Git prevent compared to manually copying files?

**Answer:** It prevents confusion and inconsistencies from managing multiple copies of files and dependencies manually.

---

# Question: In Git, how do you create a new branch called `hello-world-images`?

**Answer:** `git branch hello-world-images`

---

# Question: What does the `git branch` command do without any arguments?

**Answer:** Lists all local branches and shows the current branch with an asterisk.

---

# Question: How do you switch to a different branch named `hello-world-images`?

**Answer:** `git checkout hello-world-images`

---

# Question: After switching branches, do untracked files from the previous branch remain?

**Answer:** No, untracked files specific to another branch will not appear unless they are part of the current branch.

---

# Question: How can you create and switch to a branch named `emergency-fix` in one command?

**Answer:** `git checkout -b emergency-fix`

---

# Question: What command is used to stage all changes, including new and deleted files?

**Answer:** `git add --all`

---

# Question: What does `git status` show about your working directory?

**Answer:** It shows the current branch, changes not staged for commit, untracked files, and staged changes ready for commit.

---

# Question: What does the `git commit -m "message"` command do?

**Answer:** Commits staged changes to the current branch with a specified commit message.

---

# Question: After committing in a branch, are those changes visible in the `master` branch?

**Answer:** No, each branch keeps its changes isolated until merged.

---

# Question: What does `git checkout master` do if you are currently on another branch?

**Answer:** It switches your working directory to the `master` branch.

---

# Question: What happens to files like `img_hello_world.jpg` that exist only in a branch when switching to another?

**Answer:** They disappear from the working directory because they aren't part of the checked-out branch.

---

# Question: How do you stage and commit an individual file?

**Answer:**

```bash
git add filename  
git commit -m "commit message"
```

---

# Question: How do you delete a branch that has already been merged?

**Answer:** `git branch -d branch-name`

---

# Question: What command is used to force delete an unmerged branch?

**Answer:** `git branch -D branch-name`

---

# Question: What does `git branch -m old-name new-name` do?

**Answer:** Renames a branch from `old-name` to `new-name`.

---

# Question: How do you check what branch you are currently on?

**Answer:** Use `git status`; it displays the current branch name.

---

# Question: What are two ways to switch branches in Git?

**Answer:** `git checkout branch-name` and `git switch branch-name`

---

# Question: What is the recommended format for naming branches?

**Answer:** Use clear, descriptive names like `feature/login-page` or `bugfix/header-crash`.

---

# Question: What should you do to keep a branch updated with recent changes from the main branch?

**Answer:** Regularly merge changes from the main branch into your branch.

---

# Question: What is the significance of the `*` in the output of `git branch`?

**Answer:** It indicates the currently checked-out branch.

---

# Question: What happens if you try to delete a branch that hasn’t been merged yet using `git branch -d`?

**Answer:** Git will prevent the deletion and show an error message.

---

# Question: What’s the advantage of Git’s branch model over manually managing file versions?

**Answer:** Git branches are fast, lightweight, and prevent errors caused by manual file copying and name tracking.

---

# Question: When working in a branch and committing changes, where are the changes saved?

**Answer:** In the branch you’re currently on.

---

# Question: Can branches be used to work on multiple features in parallel?

**Answer:** Yes, each feature or fix can be developed independently on separate branches.

---

# Question: Why should you delete branches that are no longer needed?

**Answer:** To keep your repository clean and manageable.

---

# Question: If a feature is half-complete and an urgent fix is needed, what should you do?

**Answer:** Create a new branch from the main branch for the fix, then merge it when done.

---

# Question: What does `git checkout -b emergency-fix` accomplish?

**Answer:** It creates a new branch `emergency-fix` and switches to it in one step.

---

# Question: How does Git handle file visibility across branches?

**Answer:** Files committed in one branch do not appear in other branches unless merged.

---

# Question: What does merging in Git mean?

**Answer:** Merging in Git means combining the changes from one branch into another to bring work together after working separately on different features or fixes.

---

# Question: What command is used to merge a branch into your current branch?

**Answer:** `git merge`

---

# Question: What does the `--no-ff` option do in `git merge`?

**Answer:** It forces Git to always create a merge commit, even if a fast-forward merge is possible, preserving the branch history.

---

# Question: What is the purpose of the `--squash` option in `git merge`?

**Answer:** It combines all the changes from the merged branch into a single commit, cleaning up the commit history.

---

# Question: What does `git merge --abort` do?

**Answer:** It cancels a merge in progress and reverts the working directory to its state before the merge started.

---

# Question: What must you do before merging branches in Git?

**Answer:** Always commit or stash your changes to avoid losing work.

---

# Question: What is a fast-forward merge?

**Answer:** A merge where no new commits have diverged and Git simply moves the branch pointer forward.

---

# Question: What is a non-fast-forward merge?

**Answer:** A merge where new commits have been made, requiring Git to create a new merge commit.

---

# Question: How do you merge a branch named `emergency-fix` into `master`?

**Answer:**

```bash
git checkout master  
git merge emergency-fix
```

---

# Question: What is the result of a fast-forward merge in Git?

**Answer:** Git just moves the branch pointer forward and does not create a merge commit.

---

# Question: How do you delete a branch after a successful merge?

**Answer:** `git branch -d branchname`

---

# Question: How do you ensure a merge commit is always created?

**Answer:** Use `git merge --no-ff branchname`

---

# Question: What output confirms a merge was made with the recursive strategy?

**Answer:**

```
Merge made by the 'recursive' strategy.
```

---

# Question: What is the purpose of squash merging?

**Answer:** To combine all changes into a single commit before merging to clean up the commit history.

---

# Question: Does `git merge --squash` automatically commit the result?

**Answer:** No, it stops before committing, requiring a manual commit.

---

# Question: How do you manually commit a squash merge?

**Answer:** Run `git commit` after `git merge --squash branchname`.

---

# Question: When should you use `git merge --abort`?

**Answer:** When you encounter a merge conflict or want to cancel an in-progress merge.

---

# Question: What is a merge conflict?

**Answer:** A merge conflict occurs when changes from two branches affect the same part of a file, and Git cannot automatically decide which version to keep.

---

# Question: What does Git insert in a file to mark a merge conflict?

**Answer:** Conflict markers such as `<<<<<<<`, `=======`, and `>>>>>>>`.

---

# Question: How do you resolve a merge conflict?

**Answer:** Edit the conflicted file, remove the conflict markers, keep the desired changes, then `git add` and `git commit`.

---

# Question: What command shows the current state during a merge?

**Answer:** `git status`

---

# Question: What does `git status` show during a merge conflict?

**Answer:** It shows "You have unmerged paths" and lists modified files and files staged for commit.

---

# Question: What should you do after editing a conflicted file?

**Answer:** Run `git add filename` and then `git commit` to complete the merge.

---

# Question: What should you avoid when resolving merge conflicts?

**Answer:** Avoid accepting all changes blindly—review them carefully.

---

# Question: How do you check out a branch named `hello-world-images`?

**Answer:** `git checkout hello-world-images`

---

# Question: What command stages all modified files in Git?

**Answer:** `git add --all`

---

# Question: What is the output after staging and committing all changes with `git add --all` and `git commit -m "message"`?

**Answer:**

```
[branchname commit_hash] commit message  
N files changed, X insertions(+), Y deletions(-)
```

---

# Question: What conflict occurred when merging `hello-world-images` into `master`?

**Answer:** Conflict in `index.html` due to changes made to the same lines in both branches.

---

# Question: What message does Git display when a merge conflict occurs?

**Answer:**

```
CONFLICT (content): Merge conflict in filename  
Automatic merge failed; fix conflicts and then commit the result.
```

---

# Question: After resolving a conflict and staging the file, what does `git status` display?

**Answer:**

```
All conflicts fixed but you are still merging.  
(use "git commit" to conclude merge)
```

---

# Question: What command finalizes a merge after resolving conflicts?

**Answer:** `git commit -m "your message"`

---

# Question: How do you delete the `hello-world-images` branch after merging?

**Answer:** `git branch -d hello-world-images`

---

# Question: Why use `git merge --no-ff` even when a fast-forward is possible?

**Answer:** To preserve a clearer history by recording that a merge occurred.

---

# Question: What does "Auto-merging index.html" mean?

**Answer:** Git is attempting to automatically combine changes from both branches in `index.html`.

---

# Question: In a merge conflict example, what were the two conflicting lines in `index.html`?

**Answer:**

* `<<<<<<< HEAD` section: `<p>This line is here to show how merging works.</p>`
* `>>>>>>> hello-world-images` section:

  ```html
  <p>A new line in our file!</p>
  <div><img src="img_hello_git.jpg" alt="Hello Git" style="width:100%;max-width:640px"></div>
  ```

---

# Question: How should the final resolved `index.html` appear after merging the two conflicting parts?

**Answer:**

```html
<p>This line is here to show how merging works.</p>
<div><img src="img_hello_git.jpg" alt="Hello Git" style="width:100%;max-width:640px"></div>
```

---

# Question: What best practice helps reduce merge conflicts when working on long-lived feature branches?

**Answer:** Regularly merge changes from the `main` or `master` branch into the feature branch.

---

# Question: How do you ensure all files are committed after a successful merge resolution?

**Answer:** Run `git add <files>` for all modified files, then `git commit`.

---

# Question: What are the consequences of not resolving a merge conflict properly before committing?

**Answer:** The commit may include unresolved conflict markers or incorrect code, leading to errors or broken features.

---

# Question: What are the three main areas in Git's workflow?

**Answer:** Working Directory, Staging Area (Index), and Repository.

---

# Question: What command stages changes for commit in Git?

**Answer:** `git add`

---

# Question: What command saves staged changes to the local repository?

**Answer:** `git commit`

---

# Question: What command sends committed changes to a remote repository?

**Answer:** `git push`

---

# Question: What command shows the current state of your working directory and staging area?

**Answer:** `git status`

---

# Question: What command can you use to unstage a file?

**Answer:** `git restore --staged <file>`

---

# Question: What is the role of the Working Directory in Git?

**Answer:** It is where you make changes to your files before staging or committing them.

---

# Question: What is the Staging Area in Git?

**Answer:** It is the area where you prepare changes with `git add` before committing them.

---

# Question: What is the Repository in Git's workflow?

**Answer:** It is the area where your committed history is stored.

---

# Question: What is the function of `git add .`?

**Answer:** It stages all changes in the working directory, including new, modified, and deleted files.

---

# Question: What does `git commit -m "message"` do?

**Answer:** It saves all staged changes to the local repository with a commit message.

---

# Question: What is the difference between `git commit -m "message"` and `git commit -a -m "message"`?

**Answer:** `git commit -a -m` stages and commits all modified and deleted files in one step, but not new (untracked) files.

---

# Question: What does `git push` do in the Git workflow?

**Answer:** It sends your local commits to a remote repository so others can access them.

---

# Question: Why is using `git status` considered a best practice?

**Answer:** It helps you track which files are staged, unstaged, or untracked and avoid surprises before committing.

---

# Question: How does `git restore <file>` differ from `git restore --staged <file>`?

**Answer:** `git restore <file>` discards changes in the working directory; `git restore --staged <file>` removes the file from the staging area without discarding changes.

---

# Question: What does `git reset HEAD~` do?

**Answer:** It undoes the last commit, but keeps the changes in the working directory.

---

# Question: How can you modify the last commit message or add more changes to it?

**Answer:** Use `git commit --amend`.

---

# Question: What is the purpose of `git restore --staged index.html`?

**Answer:** It removes `index.html` from the staging area without deleting or altering the file content.

---

# Question: What should you do before pushing changes to avoid committing unintended files?

**Answer:** Use `git status` and stage only intended files with `git add <filename>`.

---

# Question: Why is pushing regularly to a remote repository recommended?

**Answer:** It backs up your work and shares your progress with collaborators.

---

# Question: What does the command `git commit -a -m "message"` fail to include?

**Answer:** It does not include new (untracked) files—only modified and deleted ones.

---

# Question: What should you do if you accidentally commit something you didn't mean to?

**Answer:** Use `git reset` or `git commit --amend` before pushing.

---

# Question: In the Git workflow diagram, what is the sequence of commands from editing to saving in the repository?

**Answer:**
`[Working Directory] --git add--> [Staging Area] --git commit--> [Repository]`

---

# Question: What analogy is used to describe the staging area in Git?

**Answer:** Like putting your finished letter in an envelope before mailing it.

---

# Question: What analogy is used for committing changes in Git?

**Answer:** Like mailing a letter—you can't change it after it's sent.

---

# Question: What Git command allows you to review changes before committing?

**Answer:** `git diff`

---

# Question: What are some best practices for using Git effectively?

**Answer:**

* Commit frequently with clear messages
* Use `git status` often
* Stage only intended files
* Push regularly
* Review changes before committing

---

# Question: What is GitHub Flow?

**Answer:** A popular collaborative workflow for teams using GitHub.

---

# Question: What should you do if you're unsure about a Git error?

**Answer:** Ask a teammate or look up the error message.

---

# Question: How does the Git workflow support distributed version control?

**Answer:** By allowing users to make, stage, and commit changes locally before sharing via push.

---

# Question: Why is it important to commit often in Git?

**Answer:** Frequent commits help capture progress, make it easier to track changes, and simplify debugging.

---

# Question: Give an example of a commit command following the best practice of committing often.

**Answer:**

```bash
git add .  
git commit -m "Add user authentication logic"
```

---

# Question: Why are clear commit messages important?

**Answer:** They help you and your team understand the project’s history by explaining why changes were made.

---

# Question: What are two key tips for writing effective commit messages?

**Answer:**

1. Be specific: explain what and why, not just "Update" or "Fix".
2. Use imperative mood: e.g., "Fix bug" instead of "Fixed bug".

---

# Question: Provide an example of a clear and effective commit message.

**Answer:**

```bash
git commit -m "Fix bug in user login validation"
```

---

# Question: What is the purpose of using branches in Git?

**Answer:** To work on features, fixes, or experiments without affecting the stability of the main branch.

---

# Question: How do branches support safe collaboration?

**Answer:** They allow developers to test and develop independently, reducing the risk of breaking the main codebase.

---

# Question: What is a good naming convention for branches?

**Answer:** Use descriptive names like `feature/login-form` or `bugfix/user-auth`.

---

# Question: What command creates and switches to a new branch called `feature/login-form`?

**Answer:**

```bash
git checkout -b feature/login-form
```

---

# Question: Why should you run `git pull` before `git push`?

**Answer:** To fetch and merge changes from others before pushing your own, which helps avoid conflicts and rejected pushes.

---

# Question: What command sequence pulls and then pushes to the `main` branch?

**Answer:**

```bash
git pull origin main  
git push origin main
```

---

# Question: What commands help you review changes before committing?

**Answer:** `git status` and `git diff`

---

# Question: What does `git status` show you?

**Answer:** The current state of the working directory and staging area, including staged, unstaged, and untracked files.

---

# Question: What does `git diff` show?

**Answer:** Differences between the working directory and the staging area or the last commit.

---

# Question: Why should repositories be kept small?

**Answer:** To ensure they are fast to work with and easy to clone.

---

# Question: What should you do instead of adding large files directly to your repo?

**Answer:** Use Git LFS (Large File Storage).

---

# Question: What types of files should typically be excluded using `.gitignore`?

**Answer:** Build artifacts, log files, temporary files, and sensitive data like secrets or `.env` files.

---

# Question: What does `.gitignore` actually prevent?

**Answer:** It prevents new files from being tracked by Git.

---

# Question: If a file is already tracked, will adding it to `.gitignore` stop Git from tracking it?

**Answer:** No, you must remove it manually using `git rm --cached <file>`.

---

# Question: What is an example of a `.gitignore` file that ignores `node_modules/`, `.log` files, and `.env`?

**Answer:**

```
# .gitignore
node_modules/
*.log
.env
```

---

# Question: What are Git tags used for?

**Answer:** To mark specific release points (like `v1.0`) for easy reference and version tracking.

---

# Question: How do tags help with project versioning?

**Answer:** They make it easier to locate, reference, or roll back to important versions of the project.

---

# Question: What command creates a tag called `v1.0`?

**Answer:** `git tag v1.0`

---

# Question: What command pushes a local tag named `v1.0` to a remote repository?

**Answer:** `git push origin v1.0`

---

# Question: What is a branch in Git?

**Answer:** A parallel version of your repository used to develop features independently.

---

# Question: What command creates a new branch called `feature/login`?

**Answer:**

```bash
git branch feature/login
```

---

# Question: What does `git checkout` do?

**Answer:** Switches to a different branch or commit.

---

# Question: What is the command to switch to the `main` branch?

**Answer:**

```bash
git checkout main
```

---

# Question: What does `git clone` do?

**Answer:** Creates a local copy of a remote repository.

---

# Question: What is an example of the `git clone` command?

**Answer:**

```bash
git clone https://github.com/user/repo.git
```

---

# Question: What is a commit in Git?

**Answer:** A snapshot of your changes in the repository.

---

# Question: What is an example command to make a commit?

**Answer:**

```bash
git commit -m "Add login feature"
```

---

# Question: What is a merge conflict?

**Answer:** A situation where Git can't automatically merge changes from different commits or branches and manual resolution is required.

---

# Question: What message might you see during a merge conflict?

**Answer:**

```
CONFLICT (content): Merge conflict in file.txt
```

---

# Question: What does `git fetch` do?

**Answer:** Downloads changes from a remote repository without merging them.

---

# Question: What is an example of using `git fetch`?

**Answer:**

```bash
git fetch origin
```

---

# Question: What is a fork in Git?

**Answer:** A personal copy of someone else's repository, typically created on platforms like GitHub.

---

# Question: How do you typically create a fork of a repository?

**Answer:** Use the GitHub interface to fork the repo.

---

# Question: What is the Index (Staging Area) in Git?

**Answer:** The area where changes are prepared before committing.

---

# Question: What command stages a file called `file.txt`?

**Answer:**

```bash
git add file.txt
```

---

# Question: What does the `git merge` command do?

**Answer:** Combines changes from different branches.

---

# Question: How do you merge a branch named `feature/login`?

**Answer:**

```bash
git merge feature/login
```

---

# Question: What is `origin` in Git?

**Answer:** The default name for your main remote repository.

---

# Question: How do you add a remote named `origin`?

**Answer:**

```bash
git remote add origin https://github.com/user/repo.git
```

---

# Question: What does `git pull` do?

**Answer:** Fetches and merges changes from a remote repository into your current branch.

---

# Question: How do you pull from the `main` branch on `origin`?

**Answer:**

```bash
git pull origin main
```

---

# Question: What does `git push` do?

**Answer:** Uploads your commits to a remote repository.

---

# Question: What is the command to push changes to `origin` on the `main` branch?

**Answer:**

```bash
git push origin main
```

---

# Question: What does `git rebase` do?

**Answer:** Moves or combines a sequence of commits to a new base commit.

---

# Question: What is the command to rebase onto `main`?

**Answer:**

```bash
git rebase main
```

---

# Question: What is a remote in Git?

**Answer:** A version of your repository hosted on the internet or a network.

---

# Question: What command lists all remote URLs?

**Answer:**

```bash
git remote -v
```

---

# Question: What is a repository (or repo) in Git?

**Answer:** A database where your project's history is stored.

---

# Question: What command initializes a new Git repository?

**Answer:**

```bash
git init
```

---

# Question: What does `git stash` do?

**Answer:** Temporarily saves changes that are not ready to be committed.

---

# Question: What is an example of using `git stash`?

**Answer:**

```bash
git stash
```

---

# Question: What is a tag in Git?

**Answer:** A marker for a specific commit, often used for releases.

---

# Question: What command creates a tag called `v1.0`?

**Answer:**

```bash
git tag v1.0
```

---

# Question: What does `HEAD` refer to in Git?

**Answer:** The current commit your working directory is based on, usually the latest commit on your current branch.

---

# Question: How can you view the commit that HEAD points to?

**Answer:**

```bash
git log --oneline
```

(The top entry is HEAD)

---

# Question: What is an upstream branch in Git?

**Answer:** The default branch that your current branch tracks and pulls from, usually on a remote repository.

---

# Question: What command sets an upstream branch for pushing?

**Answer:**

```bash
git push --set-upstream origin main
```

---

# Question: What are the commonly used Console API methods and what do they do?

### Console Object Methods

| Method             | Description                                                                               |
| ------------------ | ----------------------------------------------------------------------------------------- |
| `assert()`         | Writes an error message to the console if the assertion is false                          |
| `clear()`          | Clears the console                                                                        |
| `count()`          | Logs the number of times that this particular call to `count()` has been called           |
| `error()`          | Outputs an error message to the console                                                   |
| `group()`          | Creates a new inline group in the console (indents messages until `groupEnd()` is called) |
| `groupCollapsed()` | Creates a new collapsed group in the console (user must expand it manually)               |
| `groupEnd()`       | Exits the current inline group in the console                                             |
| `info()`           | Outputs an informational message to the console                                           |
| `log()`            | Outputs a general message to the console                                                  |
| `table()`          | Displays tabular data as a table in the console                                           |
| `time()`           | Starts a timer to track how long an operation takes                                       |
| `timeEnd()`        | Stops a timer that was previously started by `console.time()`                             |
| `trace()`          | Outputs a stack trace to the console                                                      |
| `warn()`           | Outputs a warning message to the console                                                  |

---

# Question: What is the first step to using GitHub for version control and collaboration?

**Answer:** The first step is to sign up for a free GitHub account.

---

# Question: What email address should you use when signing up for GitHub?

**Answer:** You should use the same email address you plan to use for your Git configuration.

---

# Question: How do you create a new repository on GitHub after signing in?

**Answer:** Click the "New" button to create a new repository.

---

# Question: What details are required when filling out the form to create a new repository on GitHub?

**Answer:** You need to provide the repository name, description, choose public or private visibility, and then click "Create repository."

---

# Question: What is a remote repository?

**Answer:** A remote repository is a version of your project hosted on the internet.

---

# Question: Why is GitHub a popular choice for hosting remote repositories?

**Answer:** GitHub enables collaboration with others and serves as a backup for your code.

---

# Question: What is SSH used for in the context of Git?

**Answer:** SSH is used to connect securely to remote computers and services, such as Git repositories.

---

# Question: What does SSH use to ensure secure access to code?

**Answer:** SSH uses a pair of keys—a public key and a private key.

---

# Question: What command generates a new SSH key pair?

**Answer:** `ssh-keygen`

---

# Question: What is the purpose of the `ssh-add` command?

**Answer:** It adds your private key to the SSH agent so Git can use it.

---

# Question: How can you test your SSH connection to GitHub?

**Answer:** Use the command `ssh -T git@github.com`.

---

# Question: Which command lists all SSH keys currently loaded in your SSH agent?

**Answer:** `ssh-add -l`

---

# Question: Which command removes a specific SSH key from the SSH agent?

**Answer:** `ssh-add -d`

---

# Question: How do SSH keys function conceptually?

**Answer:** The public key acts like a lock shared with the server, while the private key is like your own key kept securely on your computer.

---

# Question: Who can access resources locked by a public key?

**Answer:** Only someone with the corresponding private key.

---

# Question: What does the `-t rsa` option specify when generating an SSH key?

**Answer:** It specifies that the RSA algorithm should be used.

---

# Question: What does the `-b 4096` option specify in the `ssh-keygen` command?

**Answer:** It sets the key size to 4096 bits for stronger security.

---

# Question: What does the `-C` option do in the `ssh-keygen` command?

**Answer:** It adds a comment, typically your email, to the key for identification.

---

# Question: What is the default file path for the SSH key if no custom location is specified?

**Answer:** `~/.ssh/id_rsa` for the private key and `~/.ssh/id_rsa.pub` for the public key.

---

# Question: What is the recommended extra step during key generation for added security?

**Answer:** Setting a passphrase.

---

# Question: What command adds your private key to the SSH agent?

**Answer:** `ssh-add ~/.ssh/id_rsa`

---

# Question: How do you copy your public SSH key on macOS?

**Answer:** `pbcopy < ~/.ssh/id_rsa.pub`

---

# Question: How do you copy your public SSH key on Windows (Git Bash)?

**Answer:** `clip < ~/.ssh/id_rsa.pub`

---

# Question: How do you view your public SSH key on Linux?

**Answer:** Use `cat ~/.ssh/id_rsa.pub` and copy it manually.

---

# Question: What command lists loaded SSH keys in your SSH agent?

**Answer:** `ssh-add -l`

---

# Question: What command removes the default key from the SSH agent?

**Answer:** `ssh-add -d ~/.ssh/id_rsa`

---

# Question: What are possible causes of the error message “Permission denied” when using SSH?

**Answer:** Your public key is not added to the Git host, or your private key is not loaded in the SSH agent.

---

# Question: What permission setting should be applied to your private SSH key?

**Answer:** `chmod 600 ~/.ssh/id_rsa`

---

# Question: Which command provides verbose SSH output for troubleshooting?

**Answer:** `ssh -v`

---

# Question: What should the remote URL start with when using SSH with Git?

**Answer:** It should start with `git@`.

---

# Question: What is the most important rule about private SSH keys?

**Answer:** Never share your private key with anyone.

---

# Question: What should you do if your private key is ever exposed?

**Answer:** Generate a new SSH key pair and update it on your Git host immediately.

---

# Question: What must you do before pushing, pulling, or cloning using SSH on GitHub?

**Answer:** You must add your public SSH key to your GitHub account and ensure it's added to your SSH agent.

---

# Question: What command is used to copy the public SSH key to the clipboard on Windows (Git Bash)?

**Answer:** `clip < ~/.ssh/id_rsa.pub`

---

# Question: What command is used to copy the public SSH key on macOS?

**Answer:** `pbcopy < ~/.ssh/id_rsa.pub`

---

# Question: How do you copy the public SSH key on Linux?

**Answer:** Use `cat ~/.ssh/id_rsa.pub` and manually copy the output.

---

# Question: Where do you go in GitHub to begin adding your SSH key?

**Answer:** Click your profile icon in the top right and select **Settings**.

---

# Question: After opening GitHub Settings, which section should you select to manage SSH keys?

**Answer:** Select **SSH and GPG keys** from the sidebar.

---

# Question: What button should you click to add a new SSH key on GitHub?

**Answer:** Click the **New SSH key** button.

---

# Question: What information must be provided when adding a new SSH key to GitHub?

**Answer:** A descriptive title and the contents of your public SSH key.

---

# Question: What security confirmation might GitHub require when adding an SSH key?

**Answer:** GitHub may prompt for your password or ask for 2-factor authentication (2FA).

---

# Question: What indicates that your SSH key has been successfully added on GitHub?

**Answer:** The new SSH key appears listed in your SSH and GPG keys section.

---

# Question: What must be done before connecting your local repository to GitHub using SSH?

**Answer:** You must add your SSH key to your GitHub account.

---

# Question: What command is used to test your SSH connection to GitHub?

**Answer:** `ssh -T git@github.com`

---

# Question: What warning message might you see the first time you connect to GitHub via SSH?

**Answer:** "The authenticity of host 'github.com' can't be established..." followed by a prompt asking if you want to continue connecting.

---

# Question: What does the message “Hi your-username! You've successfully authenticated, but GitHub does not provide shell access.” indicate?

**Answer:** It means SSH authentication was successful.

---

# Question: Where can you find your repository’s SSH address on GitHub?

**Answer:** Go to your repository, click the **Code** button, select **SSH**, and copy the SSH URL.

---

# Question: What is the format of a GitHub SSH URL?

**Answer:** It starts with `git@github.com:`, followed by `your-username/your-repo.git`.

---

# Question: What command is used to add a remote origin using SSH for the first time?

**Answer:** `git remote add origin git@github.com:your-username/your-repo.git`

---

# Question: What command is used to update an existing remote to use an SSH URL?

**Answer:** `git remote set-url origin git@github.com:your-username/your-repo.git`

---

# Question: What is the name of the default remote Git uses when pushing to or pulling from a repository?

**Answer:** `origin`

---

# Question: What feature does GitHub provide for editing files without using Git locally?

**Answer:** GitHub allows you to edit files directly in your browser.

---

# Question: What is one common use case for editing code directly on GitHub?

**Answer:** Making quick changes without needing Git on your computer.

---

# Question: How do you begin editing a file in a GitHub repository through the web interface?

**Answer:** Click the file name, then click the Edit button (pencil icon).

---

# Question: Can you edit files other than README.md directly on GitHub?

**Answer:** Yes, you can edit any file in the repository.

---

# Question: What should you write after making edits to a file on GitHub?

**Answer:** A short, clear description of the changes in the Commit message box.

---

# Question: Why is it important to write a clear commit message?

**Answer:** It helps others understand what was changed and why.

---

# Question: What feature allows you to verify the differences before committing edits on GitHub?

**Answer:** The **Preview changes** button.

---

# Question: What branch is selected by default when committing changes in GitHub’s editor?

**Answer:** The `main` or `master` branch.

---

# Question: What should you do for larger changes instead of committing directly to `main` or `master`?

**Answer:** Create a new branch for the commit and start a pull request.

---

# Question: What happens when you select “Create a new branch for this commit” in the GitHub editor?

**Answer:** GitHub suggests a new branch name and allows you to open a pull request.

---

# Question: What action should follow after creating a new branch with your changes?

**Answer:** Open a pull request to propose the changes.

---

# Question: Why is it important to pull from a remote repository before working on a project?

**Answer:** To ensure your local copy is up to date with the most recent changes made by others on the team.

---

# Question: What two Git commands are combined when using `git pull`?

**Answer:** `git fetch` and `git merge`

---

# Question: What does `git fetch` do?

**Answer:** It downloads new data from a remote repository without changing local working files or branches.

---

# Question: What does `git merge` do?

**Answer:** It combines the current branch with a specified branch, such as `origin/master`.

---

# Question: How do you fetch updates from the remote `origin` repository?

**Answer:** `git fetch origin`

---

# Question: After running `git fetch`, what command shows whether your local branch is behind the remote branch?

**Answer:** `git status`

---

# Question: In the output of `git status`, what does it mean if it says your branch is "behind 'origin/master' by 1 commit"?

**Answer:** Your local branch is one commit behind the remote branch and can be updated using `git pull`.

---

# Question: What command shows the commit history of a remote-tracking branch?

**Answer:** `git log origin/master`

---

# Question: What command displays the line-by-line differences between your local branch and the remote branch?

**Answer:** `git diff origin/master`

---

# Question: What Git command is used to apply changes from `origin/master` to your current branch after fetching?

**Answer:** `git merge origin/master`

---

# Question: What does the output line "Fast-forward" mean in the context of a Git merge?

**Answer:** The local branch was simply moved forward to match the remote, with no conflicts or additional commits needed.

---

# Question: How can you confirm your local branch is fully up to date after a merge?

**Answer:** Run `git status`, which should say "Your branch is up to date with 'origin/master'."

---

# Question: What single Git command can you use to both fetch and merge in one step?

**Answer:** `git pull origin`

---

# Question: What does the output of `git pull origin` typically show?

**Answer:** Remote activity logs (enumerating, counting, compressing objects), followed by the files updated and how many lines were changed.

---

# Question: Why might you choose to use `git fetch` and `git merge` separately instead of `git pull`?

**Answer:** To preview and review changes before applying them, which helps prevent unintended merges.

---

# Question: What Git command is used to upload your local changes to a remote repository?

**Answer:** `git push`

---

# Question: What must you do before using `git push`?

**Answer:** You must first commit your changes using `git commit`.

---

# Question: What does `git push origin` do?

**Answer:** It pushes the current local branch to the remote repository named `origin`.

---

# Question: When might a push be rejected by the remote repository?

**Answer:** When it is not a fast-forward update, such as after a rebase.

---

# Question: What command can be used to override a non-fast-forward error when pushing?

**Answer:** `git push --force origin feature-branch`

---

# Question: What is the risk of using `git push --force`?

**Answer:** It can overwrite changes on the remote repository.

---

# Question: What is a safer alternative to `git push --force`?

**Answer:** `git push --force-with-lease origin feature-branch`

---

# Question: What does `git push --tags` do?

**Answer:** It pushes all local tags to the remote repository.

---

# Question: How do you push a specific tag to GitHub?

**Answer:** `git push origin v1.0` (replace `v1.0` with the actual tag name)

---

# Question: What should you do if you receive a “non-fast-forward” error when pushing?

**Answer:** Run `git pull --rebase` before trying to push again.

---

# Question: What might cause a “non-fast-forward” error during a push?

**Answer:** Another contributor has pushed changes to the remote branch that your local branch does not have.

---

# Question: What should you check if you get an "authentication failed" error when pushing?

**Answer:** Confirm you have access to the repository and that your credentials are correct.

---

# Question: How can you confirm that a push was successful on GitHub?

**Answer:** Visit the GitHub repository and check that a new commit appears.

---

# Question: How do you create a new branch using GitHub's web interface?

**Answer:** Click the current branch name (e.g., "main" or "master"), type a descriptive name, and click "Create branch."

---

# Question: How can you confirm which branch is active in the GitHub interface?

**Answer:** Look at the branch button—it displays the name of the currently active branch.

---

# Question: After creating a new branch, how do you edit a file like `index.html` in that branch?

**Answer:** Click the file name, make changes, and use the "Preview changes" tab to review edits.

---

# Question: What should you do after previewing your changes in the GitHub editor?

**Answer:** Add a descriptive commit message and click "Commit changes."

---

# Question: How do you switch to another branch on GitHub’s website?

**Answer:** Click the branch dropdown and select the desired branch.

---

# Question: What command is used in the terminal to switch to another branch?

**Answer:** `git switch branch-name`

---

# Question: What command deletes a local Git branch from the command line?

**Answer:** `git branch -d branch-name`

---

# Question: How do you delete a branch on GitHub using the web interface?

**Answer:** Go to the branches page, locate the branch, and click the trash can icon.

---

# Question: What command deletes a remote Git branch?

**Answer:** `git push origin --delete branch-name`

---

# Question: How do you rename a Git branch from the command line?

**Answer:** `git branch -m old-name new-name`

---

# Question: How do you merge one branch into another using GitHub?

**Answer:** Open a Pull Request (PR) and follow the prompts to complete the merge.

---

# Question: What is the command to merge a branch into your current branch using Git?

**Answer:** `git merge branch-name`

---

# Question: How can you view all branches in a GitHub repository using the web interface?

**Answer:** Click the branch dropdown at the top of the file list.

---

# Question: What command lists all local branches in the Git command line?

**Answer:** `git branch`

---

# Question: What is a protected branch?

**Answer:** A protected branch (e.g., `main`) is one that cannot be deleted or force-pushed to without special permissions.

---

# Question: Why are protected branches important in Git?

**Answer:** They help prevent accidental changes to important branches.

---

# Question: What is the purpose of pulling from your GitHub repository when working on a branch?

**Answer:** To ensure your local repository is up to date with the latest changes, including any new branches added remotely.

---

# Question: What does the command `git pull` do?

**Answer:** It downloads and integrates changes from the remote repository into the current local branch.

---

# Question: What does this line mean in the `git pull` output: `* [new branch] html-skeleton -> origin/html-skeleton`?

**Answer:** A new branch called `html-skeleton` has been detected on the remote `origin`.

---

# Question: After running `git pull`, how can you check your current branch and status?

**Answer:** Use `git status` to see the current branch and sync status.

---

# Question: What does `git status` show if you're on the master branch and it's up to date?

**Answer:**

```
On branch master  
Your branch is up to date with 'origin/master'.  
nothing to commit, working tree clean
```

---

# Question: What command lists all local branches?

**Answer:** `git branch`

---

# Question: What does the asterisk (`*`) indicate in the output of `git branch`?

**Answer:** It shows which branch is currently checked out.

---

# Question: What command shows all local **and remote** branches?

**Answer:** `git branch -a`

---

# Question: What command shows only remote branches?

**Answer:** `git branch -r`

---

# Question: If `remotes/origin/html-skeleton` appears in `git branch -a`, but not in `git branch`, what does that mean?

**Answer:** The branch `html-skeleton` exists remotely but hasn’t been checked out locally yet.

---

# Question: What command is used to check out a remote branch and track it locally?

**Answer:** `git checkout html-skeleton`

---

# Question: What does Git automatically do when you run `git checkout html-skeleton` for the first time?

**Answer:** It creates a new local branch `html-skeleton` and sets it to track the remote branch `origin/html-skeleton`.

---

# Question: How do you confirm that your newly checked-out branch is up to date with the remote?

**Answer:** Run `git pull` and verify the message "Already up to date."

---

# Question: After checking out the remote branch, how can you verify which branch you’re now working in?

**Answer:** Run `git branch`, and the asterisk (`*`) will indicate the current branch.

---

# Question: What should you do after pulling a remote branch to verify that the changes are present?

**Answer:** Open your preferred code editor and review the pulled files.

---

# Question: What does the command `git checkout -b update-readme` do?

**Answer:** It creates a new branch named `update-readme` and switches to it.

---

# Question: What is the purpose of running `git status` after editing a file?

**Answer:** To see which files have been changed and are staged or unstaged for commit.

---

# Question: What sequence of commands stages and commits a change to `README.md`?

**Answer:**

```
git add README.md  
git commit -m "Update readme for GitHub"
```

---

# Question: How do you push a newly created local branch to GitHub?

**Answer:** `git push origin update-readme`

---

# Question: What does `origin` refer to in `git push origin update-readme`?

**Answer:** It refers to the remote repository, usually GitHub, that your local Git is connected to.

---

# Question: What command sets the upstream branch when pushing for the first time?

**Answer:** `git push --set-upstream origin update-readme`

---

# Question: What is the purpose of setting an upstream branch?

**Answer:** It links your local branch to the remote one, allowing you to use `git push` and `git pull` without specifying the branch name every time.

---

# Question: What does the command `git push --force origin update-readme` do?

**Answer:** It forcefully overwrites the remote branch with your local branch changes, potentially deleting others' work.

---

# Question: When should you **not** use `--force` when pushing to GitHub?

**Answer:** When others are working on the same branch, as it may overwrite their commits and cause data loss.

---

# Question: What command deletes a branch named `update-readme` from GitHub?

**Answer:** `git push origin --delete update-readme`

---

# Question: How can you push all local branches to the GitHub repository?

**Answer:** `git push --all origin`

---

# Question: What command pushes all Git tags to GitHub?

**Answer:** `git push --tags`

---

# Question: If you get a "rejected push (non-fast-forward)" error, what should you do?

**Answer:** Run `git pull --rebase` to integrate the latest changes, then try pushing again.

---

# Question: What should you check if you get an "authentication failed" error while pushing?

**Answer:** Ensure you're logged in and have permission to push to the repository.

---

# Question: What might be the issue if Git reports "remote branch not found"?

**Answer:** The branch name is likely incorrect or misspelled.

---

# **Question: What is the main purpose of the GitHub Flow?**

**Answer:** To provide a simple, effective workflow for teams to collaborate on code safely and efficiently using Git and GitHub.

---

# **Question: What is the first step in the GitHub Flow?**

**Answer:** Create a branch.

---

# **Question: Why do you create a new branch instead of working directly on the master/main branch?**

**Answer:** To experiment or make changes without affecting the deployable master branch.

---

# **Question: Why is it important to use descriptive names for your branches?**

**Answer:** So everyone can easily understand the purpose of the branch.

---

# **Question: What is the second step in GitHub Flow after creating a branch?**

**Answer:** Make changes and add commits.

---

# **Question: What should each commit message include?**

**Answer:** A clear explanation of what has changed and why.

---

# **Question: What is the third step in the GitHub Flow?**

**Answer:** Open a pull request.

---

# **Question: What is the purpose of a pull request?**

**Answer:** To notify others that you have changes ready for review or merging.

---

# **Question: What happens during the review phase of the GitHub Flow?**

**Answer:** Team members review the changes, discuss feedback, and suggest improvements.

---

# **Question: What can you do if you receive feedback on a pull request?**

**Answer:** Make improvements and push new commits to the same pull request.

---

# **Question: What is the purpose of the deploy step in GitHub Flow?**

**Answer:** To test the branch in a production-like environment before merging.

---

# **Question: What should a team do if issues arise after deployment from a branch?**

**Answer:** Revert to the master branch to undo the changes.

---

# **Question: What is the final step of the GitHub Flow?**

**Answer:** Merge the branch into the master branch.

---

# **Question: Why are comments and commit messages important in GitHub Flow?**

**Answer:** They help track changes, explain decisions, and make collaboration easier.

---

# **Question: What helpful feature does GitHub provide in pull requests for tracking all activity?**

**Answer:** A unified Pull Request view showing all commits and feedback.

---

# **Question: What is GitHub Pages used for?**

**Answer:** It is used to publish a website directly from a GitHub repository.

---

# **Question: What name must your repository have to publish a user site with GitHub Pages?**

**Answer:** `your-username.github.io`

---

# **Question: What must you include in your GitHub Pages repository to create a website?**

**Answer:** Website files like `index.html`.

---

# **Question: Which Git command adds a remote origin pointing to your GitHub Pages repository?**

**Answer:**

```bash
git remote add origin https://github.com/your-username/your-username.github.io.git
```

---

# **Question: What Git command pushes your site to GitHub for the first time?**

**Answer:**

```bash
git push -u origin master
```

---

# **Question: Where do you go to set the source branch and folder for GitHub Pages?**

**Answer:**
Settings > Pages in your GitHub repository.

---

# **Question: What default source branch and folder does GitHub Pages use?**

**Answer:**
The `main` (or `master`) branch and the root folder.

---

# **Question: After enabling GitHub Pages, what will your site URL typically look like?**

**Answer:**
`https://your-username.github.io/`

---

# **Question: How do you disable a GitHub Pages site?**

**Answer:**
Go to **Settings > Pages** and delete or remove the source branch/folder.

---

# **Question: What Git command deletes the GitHub Pages branch from the remote?**

**Answer:**

```bash
git push origin --delete gh-pages
```

---

# **Question: What is the main benefit of using a Git GUI client?**

**Answer:**
It lets users interact with Git through buttons and menus instead of typing commands.

---

# **Question: List three advantages of using a Git GUI client.**

**Answer:**

1. See branches and changes visually
2. Stage, commit, and push with clicks
3. Handle merge conflicts with helpful tools

---

# **Question: Name five popular Git GUI clients.**

**Answer:**

1. GitHub Desktop
2. GitKraken
3. Sourcetree
4. Git GUI
5. VS Code Git

---

# **Question: Which Git GUI client is beginner-friendly and works best with GitHub?**

**Answer:**
GitHub Desktop

---

# **Question: What is one limitation of GitHub Desktop?**

**Answer:**
It has fewer advanced features and is less flexible for non-GitHub platforms.

---

# **Question: What is a key feature of GitKraken that sets it apart?**

**Answer:**
A visual commit graph and built-in merge/conflict tools.

---

# **Question: What is one drawback of using GitKraken?**

**Answer:**
Some features require a paid license.

---

# **Question: Which Git GUI client is made by Atlassian and is commonly used with Bitbucket?**

**Answer:**
Sourcetree

---

# **Question: What is a con of using Sourcetree for beginners?**

**Answer:**
Its interface can be overwhelming.

---

# **Question: Which Git GUI is included by default with Git for Windows?**

**Answer:**
Git GUI

---

# **Question: What is a limitation of Git GUI?**

**Answer:**
It has a basic interface with fewer features than other clients.

---

# **Question: How does VS Code support Git operations?**

**Answer:**
Via the built-in Source Control panel for staging, committing, pushing, pulling, and resolving conflicts.

---

# **Question: What is one drawback of using Git support in VS Code compared to other GUI clients?**

**Answer:**
It is not as visual for history/branches.

---

# **Question: What should you do if changes aren't showing up in your Git GUI client?**

**Answer:**
Refresh or re-scan the repository in the client.

---

# **Question: What should you do if you face authentication issues in your Git GUI client?**

**Answer:**
Ensure SSH keys or personal access tokens are properly set up.

---

# Question: What is a fork in GitHub?

**Answer:** A fork is a copy of a repository, typically used to contribute to someone else's project or start a new project based on the original.

---

# Question: Is `fork` a Git command?

**Answer:** No, `fork` is not a command in Git; it is a feature offered by GitHub and other repository hosting services.

---

# Question: Why would you fork a repository on GitHub?

**Answer:** To make changes to someone else's project or create your own project based on their code.

---

# Question: What is the prerequisite to adding code directly to someone else's Git repository?

**Answer:** You must have access rights to the repository.

---

# Question: What does Git prevent if you don’t have access rights to a repository?

**Answer:** Git prevents you from adding code directly to someone else's repository.

---

# Question: After forking a repository on GitHub, what do you obtain?

**Answer:** Your own copy of the original repository.

---

# Question: After completing a fork on GitHub, what is typically the next step?

**Answer:** Add a local copy of the forked repository to your machine to work with it.

---

# Question: What is a clone in GitHub?

**Answer:** A clone is a full copy of a repository, including all logging and versions of files, stored locally.

---

# Question: What is the purpose of cloning a forked repository?

**Answer:** To create a local copy of the forked repository for continued work and development.

---

# Question: What is the command to clone a GitHub repository using HTTPS?

**Answer:** `git clone https://github.com/w3schools-test/w3schools-test.github.io.git`

---

# Question: What message indicates that cloning a repository has been completed successfully?

**Answer:** Messages like “Receiving objects: 100%” and “Resolving deltas: 100%” indicate successful cloning.

---

# Question: What directory is created after running a clone command without specifying a folder name?

**Answer:** A directory named after the cloned project, e.g., `w3schools-test.github.io/`.

---

# Question: How can you specify a different directory name when cloning a repository?

**Answer:** By adding the desired folder name after the repository URL, e.g., `git clone [URL] myfolder`.

---

# Question: What command shows the current status of your Git working directory?

**Answer:** `git status`

---

# Question: What message does `git status` return if there are no changes?

**Answer:**

```
On branch master  
Your branch is up to date with 'origin/master'.  
nothing to commit, working tree clean
```

---

# Question: What command is used to confirm you have the full repository history?

**Answer:** `git log`

---

# Question: What type of information is shown in the `git log` output?

**Answer:** Commit hashes, author names, commit dates, and commit messages.

---

# Question: What command shows the current remote repository URLs?

**Answer:** `git remote -v`

---

# Question: What is the default remote name Git assigns when a repository is cloned?

**Answer:** `origin`

---

# Question: What command renames an existing Git remote?

**Answer:** `git remote rename origin upstream`

---

# Question: After renaming the original remote to "upstream", what does `git remote -v` show?

**Answer:**

```
upstream  https://github.com/w3schools-test/w3schools-test.github.io.git (fetch)  
upstream  https://github.com/w3schools-test/w3schools-test.github.io.git (push)
```

---

# Question: What command adds a new remote pointing to your own fork?

**Answer:** `git remote add origin https://github.com/kaijim/w3schools-test.github.io.git`

---

# Question: After adding your own fork as `origin`, what will `git remote -v` show?

**Answer:**

```
origin    https://github.com/kaijim/w3schools-test.github.io.git (fetch)  
origin    https://github.com/kaijim/w3schools-test.github.io.git (push)  
upstream  https://github.com/w3schools-test/w3schools-test.github.io.git (fetch)  
upstream  https://github.com/w3schools-test/w3schools-test.github.io.git (push)
```

---

# Question: According to Git conventions, what should you name your own remote repository?

**Answer:** `origin`

---

# Question: According to Git conventions, what should you name the remote pointing to the original repository you forked from?

**Answer:** `upstream`

---

# Question: What access do you typically have on the `origin` remote?

**Answer:** Read and write access.

---

# Question: What access do you typically have on the `upstream` remote?

**Answer:** Read-only access.

---

# Question: What is the purpose of pushing changes to your GitHub fork?

**Answer:** To upload committed changes from your local Git repository to your forked repository on GitHub.

---

# Question: What command is used to push local commits to your GitHub fork?

**Answer:** `git push origin`

---

# Question: What message indicates a successful `git push` operation?

**Answer:**

```
To https://github.com/kaijim/w3schools-test.github.io.git  
facaeae..ebb1a5c  master -> master
```

---

# Question: After pushing changes to your fork on GitHub, what is the next step to propose these changes to the original repository?

**Answer:** Create a Pull Request.

---

# Question: Where do you go to initiate a Pull Request on GitHub?

**Answer:** On your forked GitHub repository page, where the option to "Compare & pull request" becomes available.

---

# Question: What should you include when creating a Pull Request?

**Answer:** An explanation or comment for the repository administrators to describe the changes and why they should be merged.

---

# Question: What happens after a Pull Request is created?

**Answer:** Members with access to the original repository can review, comment on, and merge the proposed changes.

---

# Question: What can repository administrators do upon reviewing a Pull Request?

**Answer:** Comment on the changes and merge the Pull Request into the main branch (typically `master`).

---

# Question: What is the final step in incorporating changes from a Pull Request?

**Answer:** Confirm the merge, which integrates the changes into the original repository’s master branch.

---

# Question: How does GitHub indicate that a Pull Request has been successfully merged?

**Answer:** The Pull Request is marked as merged, and the changes appear in the master branch of the original repository.

---


# Question: What does the `git revert` command do?

**Answer:** It undoes a previous commit by creating a new commit that reverses the changes.

---

# Question: Why is `git revert` considered the safest way to undo changes in a shared repository?

**Answer:** Because it keeps the commit history intact.

---

# Question: What does the command `git revert HEAD` do?

**Answer:** It reverts the most recent commit.

---

# Question: How do you revert a specific commit in Git?

**Answer:** Use `git revert <commit-hash>`.

---

# Question: What does `git revert HEAD~2` do?

**Answer:** It reverts the third most recent commit (two commits before HEAD).

---

# Question: What is the purpose of the `--no-edit` option with `git revert`?

**Answer:** It skips the commit message editor and uses the default generated message.

---

# Question: What command shows a concise list of previous commits?

**Answer:** `git log --oneline`

---

# Question: What does the `git log --oneline` command output?

**Answer:** A compact summary of commits showing commit hashes and messages.

---

# Question: What is the purpose of running `git log --oneline` before reverting?

**Answer:** To identify the specific commit hash to revert.

---

# Question: What is the result of running `git revert HEAD --no-edit`?

**Answer:** A new commit is created that reverts the latest commit without opening an editor for the message.

---

# Question: What happens to the file system after running a successful `git revert`?

**Answer:** A new commit is added that undoes the changes from the reverted commit, possibly affecting files (e.g., creating or deleting).

---

# Question: What does a successful `git revert` log entry look like?

**Answer:**

```
[master e56ba1f] Revert "Just a regular update, definitely no accidents here..."  
Date: Thu Apr 22 10:50:13 2021 +0200  
1 file changed, 0 insertions(+), 0 deletions(-)  
create mode 100644 img_hello_git.jpg
```

---

# Question: How can you confirm that a `git revert` has created a new commit?

**Answer:** By running `git log --oneline` and checking that a new commit message starting with “Revert” appears at the top.

---

# Question: What is the main difference between `git revert` and `git reset`?

**Answer:** `git revert` creates a new commit that reverses changes, preserving history, while `git reset` rewrites history by moving HEAD and optionally discarding commits.

---

# Question: When should you prefer `git revert` over `git reset`?

**Answer:** When working in a shared repository where preserving commit history is important.

---

# Question: What should you do if you encounter the error "could not revert..."?

**Answer:** Run `git revert --abort` to cancel the revert process.

---

# Question: What should you do if you get the error "could not apply..." during a revert?

**Answer:** Run `git revert --continue` to proceed with the revert process after resolving conflicts.

---

# Question: Why is `git revert HEAD --no-edit` commonly used in scripts or automation?

**Answer:** Because it avoids prompting for a commit message, allowing for non-interactive execution.

---

# Question: What does it mean when a commit shows "create mode 100644" in the revert output?

**Answer:** A new file was created as part of the reverted changes.

---

# Question: What does the `git reset` command do?

**Answer:** It moves the current branch (HEAD) to a different commit and optionally changes the staging area and working directory depending on the reset mode used.

---

# Question: What are the three main modes of `git reset`?

**Answer:** `--soft`, `--mixed`, and `--hard`.

---

# Question: What does `git reset --soft <commit>` do?

**Answer:** Moves HEAD to the specified commit and keeps all changes staged (in the index).

---

# Question: When is `git reset --soft` especially useful?

**Answer:** When combining several commits into one or rewriting history while keeping work ready to commit.

---

# Question: What does `git reset --mixed <commit>` do?

**Answer:** Moves HEAD to the specified commit, unstages any changes, but keeps them in the working directory.

---

# Question: What is the default mode of `git reset`?

**Answer:** `--mixed`.

---

# Question: What does `git reset --hard <commit>` do?

**Answer:** Moves HEAD to the specified commit and discards all changes in the staging area and working directory.

---

# Question: What is the command to unstage a specific file?

**Answer:** `git reset <file>`

---

# Question: What does `git log --oneline` display?

**Answer:** A concise list of commits with abbreviated hashes and commit messages.

---

# Question: How do you identify the commit to reset to?

**Answer:** By using `git log --oneline` and noting the hash of the desired commit.

---

# Question: What part of the commit hash is typically used with `git reset`?

**Answer:** The first seven characters.

---

# Question: In the example log, what commit was selected as the reset point?

**Answer:** `9a9add8` (Added .gitignore).

---

# Question: What happens to changes after the target commit when you run `git reset --soft 9a9add8`?

**Answer:** They are preserved and remain staged for a new commit.

---

# Question: What happens to changes after the target commit when you run `git reset --mixed 9a9add8`?

**Answer:** They are preserved but unstaged.

---

# Question: What should you do after running any type of `git reset`?

**Answer:** Review your changes using `git status` or manually check your files.

---

# Question: What are the risks of using `git reset`?

**Answer:** It can rewrite commit history and potentially delete uncommitted changes if used with `--hard`.

---

# Question: What should you always do before using `git reset` on a shared repository?

**Answer:** Communicate with your team, as it rewrites history and can affect others.

---

# Question: What command helps troubleshoot the state of your repo after a reset?

**Answer:** `git status`

---

# Question: Why is caution advised when using `git reset`?

**Answer:** Because it can permanently delete changes and alter commit history, especially with `--hard`.

---

# Question: What does `git commit --amend` do?

**Answer:** It modifies the most recent commit, allowing you to change the message, add or remove files, or both.

---

# Question: When should you use `git commit --amend`?

**Answer:** When you need to make small changes to the last commit, such as fixing typos, adding forgotten files, or correcting the commit message.

---

# Question: What is the command to amend the last commit message?

**Answer:** `git commit --amend -m "New message"`

---

# Question: What is the result of running `git commit --amend -m "Corrected commit message"`?

**Answer:** The previous commit message is replaced with "Corrected commit message".

---

# Question: How do you add a forgotten file to the last commit?

**Answer:**

1. Stage the file: `git add <file>`
2. Amend the commit: `git commit --amend`

---

# Question: Provide an example of amending a commit to add a forgotten file named `forgotten.txt`.

**Answer:**

```
git add forgotten.txt  
git commit --amend
```

---

# Question: How do you remove a file from the last commit?

**Answer:**

1. Unstage the file from the previous commit: `git reset HEAD^ -- <file>`
2. Amend the commit: `git commit --amend`

---

# Question: What does the command `git reset HEAD^ -- unwanted.txt` do?

**Answer:** It removes `unwanted.txt` from the previous commit by unstaging it.

---

# Question: After amending a commit, how can you verify the changes in commit history?

**Answer:** Run `git log --oneline`.

---

# Question: What does the log output look like after amending a commit message?

**Answer:** The amended commit appears at the top with the updated message, replacing the original commit.

---

# Question: What is the output after running `git commit --amend -m "Added lines to README.md"`?

**Answer:**

```
[master eaa69ce] Added lines to README.md  
Date: Thu Apr 22 12:18:52 2021 +0200  
1 file changed, 3 insertions(+), 1 deletion(-)
```

---

# Question: What happens to the commit hash after using `git commit --amend`?

**Answer:** A new commit hash is generated, replacing the old one in the history.

---

# Question: Why should you be cautious when using `git commit --amend`?

**Answer:** Because it rewrites commit history, which can be problematic in shared or remote repositories.

---

# Question: When is it safe to use `git commit --amend`?

**Answer:** On your local repository before pushing or if you’re the only one working on the branch.

---

# Question: What could happen if you amend commits that have already been pushed to a shared remote repository?

**Answer:** It may cause conflicts or confusion for others, as the commit history has changed.

---

# Question: What does the command `git log --oneline` help you verify after an amend?

**Answer:** That the commit message and hash have been updated, and the amended commit is now the latest one.

---

# Question: Can you use `git commit --amend` to both change the message and add files at once?

**Answer:** Yes, as long as the files are staged before running the amend command.

---

# Question: What is the correct sequence to amend both files and the commit message?

**Answer:**

1. `git add <file>`
2. `git commit --amend -m "New message"`

---

# Question: What does Git rebase do?

**Answer:** Git rebase moves or combines a sequence of commits to a new base commit, typically to maintain a clean, linear project history.

---

# Question: What are the main benefits of using Git rebase?

**Answer:** Git rebase helps keep a clean, linear project history, avoids unnecessary merge commits, combines multiple commits into one, and allows editing or reordering commits.

---

# Question: When should you use Git rebase?

**Answer:** Use Git rebase when you want to:

* Keep a clean, linear history
* Avoid merge commits
* Combine commits
* Edit or reorder commits before sharing

---

# Question: What is the purpose of `git rebase main`?

**Answer:** It reapplies the current branch's changes on top of the latest `main` branch, effectively updating the feature branch with changes from `main`.

---

# Question: What are the CLI commands to rebase a feature branch onto `main`?

**Answer:**

```bash
git checkout feature-branch  
git rebase main  
```

---

# Question: What is interactive rebase?

**Answer:** Interactive rebase (`git rebase -i <base>`) allows you to edit, reorder, squash, or fix up commits before a certain commit, often used to clean up commit history.

---

# Question: What command starts an interactive rebase for the last 3 commits?

**Answer:**

```bash
git rebase -i HEAD~3
```

---

# Question: In an interactive rebase, what does the `pick` command do?

**Answer:** `pick` keeps the commit as is.

---

# Question: In an interactive rebase, what does the `squash` command do?

**Answer:** `squash` combines the current commit with the previous one, merging their changes.

---

# Question: In an interactive rebase, what does the `edit` command do?

**Answer:** `edit` pauses the rebase process to allow you to change the contents of the commit.

---

# Question: In an interactive rebase, what does the `reword` command do?

**Answer:** `reword` changes only the commit message without modifying the commit content.

---

# Question: What are the basic steps in performing an interactive rebase?

**Answer:**

1. Start with `git rebase -i <base>`
2. Edit the list of commits (pick, squash, edit, reword)
3. Save and close the editor
4. Git applies changes and lets you review
5. Use `git rebase --continue` to proceed

---

# Question: What command continues a rebase after resolving a conflict?

**Answer:**

```bash
git rebase --continue
```

---

# Question: What must you do before running `git rebase --continue`?

**Answer:** Resolve any conflicts and stage the fixed files using `git add`.

---

# Question: What is the command to stage a fixed file during a rebase?

**Answer:**

```bash
git add fixed_file.txt
```

---

# Question: What command cancels a rebase in progress and restores the previous branch state?

**Answer:**

```bash
git rebase --abort
```

---

# Question: What happens when you run `git rebase --abort`?

**Answer:** The rebase process is cancelled, and the branch returns to its state before the rebase started.

---

# Question: What command skips a problematic commit during a rebase?

**Answer:**

```bash
git rebase --skip
```

---

# Question: What happens when you use `git rebase --skip`?

**Answer:** Git excludes the problematic commit and continues rebasing the remaining commits.

---

# Question: What should you do after completing a rebase?

**Answer:** Review the changes to ensure everything has been correctly applied and behaves as expected.

---

# Question: Why should you avoid rebasing commits that were already pushed to a shared repository?

**Answer:** Because rebasing rewrites commit history, rebasing shared commits can cause inconsistencies and confusion for others collaborating on the repository.

---

# Question: What are best practices when using Git rebase?

**Answer:**

* Avoid rebasing pushed commits
* Use `git rebase -i` to clean up history
* Use `--continue`, `--abort`, and `--skip` appropriately
* Always review changes after rebasing

---

# Question: What should you do if you encounter a conflict during rebase?

**Answer:** Resolve the conflict, stage the resolved files using `git add`, and then run `git rebase --continue`.

---

# Question: What should you do if you can't fix a commit during rebase?

**Answer:** Use `git rebase --skip` to bypass that commit.

---

# Question: What does `git reflog` do?

**Answer:** `git reflog` records updates to the tip of branches and `HEAD`, allowing you to see past positions of `HEAD`, including changes made by mistake.

---

# Question: Why is `git reflog` useful?

**Answer:** It helps recover lost commits, undo resets or merges, and view the complete history of `HEAD` and branches, including non-branch history changes.

---

# Question: When should you use `git reflog`?

**Answer:** Use `git reflog` when you need to:

* Recover lost commits or changes
* Undo a reset or merge
* View the history of `HEAD` and branches

---

# Question: What is the command to display the reflog?

**Answer:**

```bash
git reflog
```

---

# Question: What type of actions are shown in the output of `git reflog`?

**Answer:** Actions like commits, resets, merges, checkouts, and other changes to the position of `HEAD`.

---

# Question: In the reflog entry `HEAD@{2}`, what does the `{2}` indicate?

**Answer:** It indicates the position in the reflog history, with `{0}` being the most recent and larger numbers being older entries.

---

# Question: How can you use `git reflog` to recover from an accidental `git reset --hard`?

**Answer:**

1. Run `git reflog` to find the previous commit hash or `HEAD@{n}` reference.
2. Use `git reset --hard HEAD@{n}` to restore to that point.

---

# Question: What is the command to restore your branch to a previous state using reflog?

**Answer:**

```bash
git reset --hard HEAD@{n}
```

Replace `{n}` with the appropriate reflog index.

---

# Question: What does the command `git reset --hard HEAD@{2}` do?

**Answer:** It resets the working directory and `HEAD` to the state recorded two steps back in the reflog.

---

# Question: What command is used to remove reflog entries older than 30 days for the `main` branch?

**Answer:**

```bash
git reflog expire --expire=30.days refs/heads/main
```

---

# Question: What is the purpose of the command `git gc --prune=now`?

**Answer:** It triggers Git’s garbage collection to remove unreachable or expired objects, including old reflog entries.

---

# Question: What is the combined command to expire old reflog entries and clean up with garbage collection?

**Answer:**

```bash
git reflog expire --expire=30.days refs/heads/main  
git gc --prune=now
```

---

# Question: What happens during garbage collection (`git gc`)?

**Answer:** Git compresses objects, removes unreachable or expired objects, and cleans up storage.

---

# Question: Why might you want to manually clean the reflog?

**Answer:** To reduce disk space, improve performance, or remove sensitive or obsolete history entries before sharing a repository.

---

# Question: What are some best practices for using `git reflog`?

**Answer:**

* Use it regularly to track changes
* Use it to recover lost commits or undo mistakes
* Clean up old entries using `git reflog expire`

---

# Question: What should you be cautious of when using `git reflog` to recover commits?

**Answer:** You can overwrite existing changes if you're not careful when using `git reset` or other recovery commands.

---

# Question: How is the reflog cleaned by default?

**Answer:** Git automatically expires old reflog entries based on its default settings unless overridden manually.

---

# Question: What are some troubleshooting steps if you face issues with `git reflog`?

**Answer:**

* Check Git documentation for details
* Search online for specific error messages or use cases
* Ask for help from the Git community or experienced users

---

# Question: What is Git recovery?

**Answer:** Git recovery is the process of getting back lost commits, branches, or files using Git's history and recovery tools.

---

# Question: Why is Git recovery possible?

**Answer:** Git keeps a record of recent changes, including changes to `HEAD` and branches, which allows you to undo mistakes even after resets or deletions.

---

# Question: When should you use Git recovery?

**Answer:** Use Git recovery when you:

* Accidentally delete a branch or file
* Lose changes after a reset
* Need to recover lost commits or previous states

---

# Question: What Git command is commonly used to find lost commits?

**Answer:**

```bash
git reflog
```

---

# Question: How does `git reflog` help in Git recovery?

**Answer:** It shows a history of where `HEAD` and branches have pointed, allowing you to find lost commits and recover them using their commit hash or reflog reference.

---

# Question: What is the purpose of `git checkout -b branch-name <commit-hash>` in Git recovery?

**Answer:** It recreates a deleted branch by starting a new branch at the specified commit hash.

---

# Question: What is the output of running `git checkout -b branch-name <commit-hash>`?

**Answer:**

```
Switched to a new branch 'branch-name'
```

---

# Question: How can you restore a deleted or changed file from the latest commit?

**Answer:**

```bash
git restore filename.txt
```

---

# Question: What does `git restore filename.txt` do?

**Answer:** It restores `filename.txt` from the latest committed version in the current branch, undoing deletions or unwanted changes.

---

# Question: How can you undo a `git reset --hard` if it removed useful commits?

**Answer:**

1. Run `git reflog` to find the commit you want to return to.
2. Use `git reset --hard HEAD@{n}` to reset your branch to that state.

---

# Question: What is the command to restore your branch to a previous state using reflog after a hard reset?

**Answer:**

```bash
git reset --hard HEAD@{n}
```

---

# Question: What does the command `git reset --hard HEAD@{2}` do in Git recovery?

**Answer:** It resets the working directory and branch to the state recorded two steps back in the reflog, effectively undoing a hard reset.

---

# Question: What are some tips and best practices for Git recovery?

**Answer:**

* Regularly commit your changes to avoid loss
* Use `git reflog` to find lost commits
* Use `git restore` to recover deleted or changed files

---


