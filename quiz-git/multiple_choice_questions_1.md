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

