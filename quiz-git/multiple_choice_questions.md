# Question: What are Git and GitHub, and why are they important?

**Answer:** Git is a free and open-source version control system that helps programmers track code changes. GitHub is a platform that hosts Git repositories, enabling collaboration and sharing. They are essential tools widely used in software development.

---

# Question: What is version control?

**Answer:** Version control is a method programmers use to track and manage code changes over time, enabling them to revert to previous versions or investigate bugs.

---

# Question: How does Git help programmers manage code changes?

**Answer:** Git allows programmers to save an initial version of their code and continually save updates, creating a history of changes that can be reviewed or reverted as needed.

---

# Question: Why do programmers often use the terminal or CLI instead of graphical applications?

**Answer:** Because it helps them learn the core Git workflow and get accustomed to command-line environments, which are frequently used in development tasks like installing software and running programs.

---

# Question: What is a code editor used for?

**Answer:** A code editor is used to write and edit code.

---

# Question: What is a code editor, and how does it differ from a regular text document?

**Answer:** A code editor is a specialized text editor designed with tools and features for programming, unlike general-purpose applications like word processors.

---

# Question: In programming, what is typically meant by the term “repository”?

**Answer:** A repository usually refers to a Git repository — the folder or location where a project is stored and tracked using Git.

---

# Question: What is the difference between Git and GitHub?

**Answer:** Git is a version control tool that tracks code changes locally, while GitHub is a website that hosts Git repositories online for collaboration and portfolio management.

---

# Question: Why is GitHub useful for developers?

**Answer:** GitHub enables online collaboration, makes group work easier, and allows developers to organize and showcase their projects in a portfolio for potential employers.

---

# Question: What does the `clone` command do in Git?

**Answer:** `clone` copies a repository from a remote source, like GitHub, to the local machine for local use.

---

# Question: Are Git commands case-sensitive?

**Answer:** Yes, all Git commands are lowercase.

---

# Question: What is the purpose of the `add` command in Git?

**Answer:** The `add` command tells Git to start tracking newly created, updated, or deleted files and folders.

---

# Question: What does it mean to “commit” in Git?

**Answer:** To commit is to save the tracked changes into the Git repository, creating a permanent snapshot of the current state of the code.

---

# Question: What is the typical Git workflow for saving changes?

**Answer:** First, use `add` to track changes, then use `commit` to save those changes, and finally use `push` to upload them to a remote repository.

---

# Question: What is the function of the `push` command in Git?

**Answer:** `push` uploads committed changes from the local Git repository to a remote repository like GitHub.

---

# Question: What does the `pull` command do in Git?

**Answer:** `pull` retrieves and merges changes from a remote repository into the local repository.

---

# Question: What must you do before using GitHub?

**Answer:** You must sign up for a GitHub account, provide minimal information, verify your email, and log in.

---

# Question: After logging into GitHub, where can you create a new repository?

**Answer:** You can create a new repository from the green “New” button or the plus (+) dropdown menu in the top navigation.

---

# Question: What does a GitHub repository contain?

**Answer:** A GitHub repository contains all files and folders related to a project, including code and other project resources.

---

# Question: What is the term "repo" short for?

**Answer:** Repo is short for "repository."

---

# Question: How do you create a new repository on GitHub?

**Answer:** You click the green "New" button or the plus (+) dropdown, give the repository a name, leave the default settings if desired, and click "Create repository."

---

# Question: Where can you create project files for a GitHub repository?

**Answer:** Files and folders can be created locally on your machine or directly in the online GitHub editor.

---

# Question: What is a README file, and what is its purpose?

**Answer:** A README file is a markdown file typically named `README.md` that describes the project, what it does, and other relevant information.

---

# Question: What is Markdown used for in a README file?

**Answer:** Markdown is used to format text using simple syntax, such as `#` for headers, making documentation easy to read.

---

# Question: How do you create a new file in the GitHub online editor?

**Answer:** Click “Create a new file,” enter a filename like `README.md`, type content, and commit it to save.

---

# Question: What happens if you leave the commit message blank when creating a file?

**Answer:** GitHub will use a default commit message based on the filename, such as “create README.md.”

---

# Question: Why does GitHub always show the `README.md` file on the repository home page?

**Answer:** GitHub is configured to display `README.md` as the default visible file in the repository view.

---

# Question: How do you edit an existing file in GitHub's web interface?

**Answer:** Navigate to the file and click "Edit this file," make changes, then commit them with an appropriate message.

---

# Question: What does the default commit message say when updating a file?

**Answer:** If not manually changed, the default message is "update \[filename]", e.g., `update readme.md`.

---

# Question: How can you view your commit history on GitHub?

**Answer:** Go to the “Commits” section of the repository to see all commit messages and timestamps.

---

# Question: What information does each commit contain?

**Answer:** Each commit has a unique identifier, a message/title, and a visual representation of file changes.

---

# Question: In GitHub’s file change view, what does green with a plus sign mean?

**Answer:** Lines were added to the file.

---

# Question: What does red with a minus sign indicate in GitHub’s commit comparison?

**Answer:** Lines were deleted from the file.

---

# Question: What does white text mean in GitHub’s commit comparison view?

**Answer:** The line stayed the same between commits.

---

# Question: How can you check if Git is installed on a Mac or Linux machine?

**Answer:** Open the terminal and run the command:
`git --version`

---

# Question: What should you do if Git is not installed on your system?

**Answer:** Follow the Git installation tutorial provided by Atlassian, which covers all operating systems.

---

# Question: When installing Git on Windows, what option is recommended during setup?

**Answer:** Select the **Git Bash** option from the installation menu.

---

# Question: Can you use Command Prompt on Windows for Git?

**Answer:** Yes, you can use Command Prompt, but Git Bash is recommended for a Unix-like command-line experience.

---

Here are **quiz questions** based on your provided material, written to cover **100% of the content** with technical clarity and CLI examples.

---

# Question: What command line interface is recommended for Git on Windows?

**Answer:** Git Bash is recommended for Git on Windows as it often works more smoothly than Command Prompt.

---

# Question: What package manager is recommended for installing Git on macOS?

**Answer:** Homebrew is recommended for installing Git on macOS.

---

# Question: Do Mac and Linux users typically need to install Git manually?

**Answer:** No, Git is usually already installed on Mac and Linux systems.

---

# Question: Can any word processing software be used for coding?

**Answer:** While technically possible, it is not recommended. Dedicated code editors are better suited for coding tasks.

---

# Question: What Git command is used to copy a GitHub repository to your local system?

**Answer:** `git clone [repository URL]`

---

# Question: What is the effect of running `git clone` with an SSH URL?

**Answer:** It creates a local copy of the GitHub repository in the current directory.

---

# Question: How do you navigate into the cloned repository from the terminal?

**Answer:** Use the `cd` command followed by the repository folder name (e.g., `cd demo-repo`).

---

# Question: After cloning, what does the terminal prompt change indicate?

**Answer:** It may include an indicator such as `Git master` showing that the current directory is a Git repository.

---

# Question: How can you tell if you're inside a Git repository even if it looks like a regular folder?

**Answer:** There is a hidden `.git` folder inside the directory, which indicates it's a Git repository.

---

# Question: What is the `.git` directory and why is it hidden?

**Answer:** The `.git` directory is a hidden folder that stores all Git-related data, including commits and the complete history of the repository. It is hidden by default on most operating systems.

---

# Question: How can you view hidden files and folders on Mac using the terminal?

**Answer:** Use the `la` command, which is shorthand for `ls -lA`, to list all files including hidden ones.

---

# Question: What is the full command equivalent to `la` on Mac for listing hidden files?

**Answer:** `ls -lA`

---

# Question: How can non-Mac users list hidden files and folders in a terminal?

**Answer:** Use the command `ls -lA`

---

# Question: What does the `.git` folder contain?

**Answer:** It contains all the files that track commits and record the full change history of the repository.

---

# Question: How can you make local changes to a Git-tracked file?

**Answer:** By editing the file (e.g., adding a subheader and text to `README.md`), then saving the file.

---

# Question: What does the command `git status` do?

**Answer:** It displays the state of the working directory and staging area, showing modified, untracked, or staged files.

---

# Question: What type of file status is shown when a file is changed but not yet staged?

**Answer:** The file appears as "modified" in the `git status` output.

---

# Question: What does Git mean by an "untracked" file?

**Answer:** An untracked file is one that exists in the working directory but is not yet being tracked by Git.

---

# Question: How can you add a new file (e.g., `index.html`) to Git tracking?

**Answer:** Use the `git add` command followed by the filename or `.` to stage the file for commit.

---

# Question: What does the command `git add .` do?

**Answer:** It stages all modified and untracked files in the current directory and its subdirectories for commit.

---

# Question: What is an alternative to using `git add .`?

**Answer:** You can specify individual file names, e.g., `git add README.md index.html`.

---

# Question: What command do you use to verify if files have been staged for commit?

**Answer:** `git status`

---

# Question: What does it mean when `git status` shows changes in a different format after `git add`?

**Answer:** It means the files have been successfully staged and are ready to be committed.

---

# Question: What is the purpose of `git commit -m`?

**Answer:** It creates a new commit with a message describing the changes being saved.

---

# Question: Is the commit message in `git commit -m` optional?

**Answer:** No, a commit message is required; Git will throw an error if none is provided.

---

# Question: What is the structure of a typical commit message using `git commit -m`?

**Answer:** The structure is `git commit -m "Your message here"`, where the message briefly describes the commit.

---

# Question: How can you add a second message (like a description) when committing?

**Answer:** By adding another `-m` flag, e.g., `git commit -m "Title" -m "Description"`

---

# Question: What does Git display after a successful commit?

**Answer:** It shows the number of files changed, lines inserted or deleted, e.g., `2 files changed, 5 insertions`.

---

# Question: Where are changes saved after running `git commit`?

**Answer:** Changes are saved locally in the repository; they are not yet pushed to a remote server.

---

# Question: What does the `git push` command do?

**Answer:** It pushes local commits to a remote repository, making them live on platforms like GitHub.

---

# Question: Why is authentication needed when pushing code to GitHub?

**Answer:** GitHub requires users to prove they own the account before pushing code to a repository.

---

# Question: How does Git authenticate your local machine with your GitHub account?

**Answer:** Through the use of SSH keys that are linked to your GitHub account.

---

# Question: What command is used to generate a new SSH key?

**Answer:** `ssh-keygen`

---

# Question: What options are typically specified during SSH key generation?

**Answer:** The type of encryption, strength of encryption, and GitHub email address.

---

# Question: Why must the email address used during SSH key generation match your GitHub account?

**Answer:** To associate the key correctly with your GitHub identity.

---

# Question: Where is the default SSH key file stored on your system?

**Answer:** Inside the user directory, under the `.ssh` directory, with the default filename `id_rsa`.

---

# Question: What should you do if you already have a key named `id_rsa`?

**Answer:** Give the new key a different name during generation.

---

# Question: Is it mandatory to set a passphrase for an SSH key?

**Answer:** No, it's optional—you can leave it blank.

---

# Question: What are the two files generated when you create an SSH key?

**Answer:** A private key (e.g., `test_key`) and a public key (e.g., `test_key.pub`).

---

# Question: Which SSH key file should you upload to GitHub?

**Answer:** The public key file (`.pub`), such as `test_key.pub`.

---

# Question: What does the `.pub` file extension indicate?

**Answer:** That the file is a public key and can be shared safely.

---

# Question: Why must you never share your private key?

**Answer:** Because it's used to authenticate you securely and must remain confidential.

---

# Question: How does the SSH key authentication process work with GitHub?

**Answer:** The private key on your machine proves you generated the public key uploaded to GitHub.

---

# Question: What does the structure of a public SSH key look like?

**Answer:** It starts with `ssh-rsa`, followed by encoded characters, and ends with your email address.

---

# Question: What’s the correct way to copy an SSH key from the terminal?

**Answer:** Highlight the key text in the terminal to copy it automatically.

---

# Question: Why shouldn’t you use Ctrl+C to copy in the terminal?

**Answer:** Because Ctrl+C is a command to cancel a running process, not for copying text.

---

# Question: What command can you use to copy the SSH public key from a file?

**Answer:** `pbcopy < path/to/your/public/key.pub`

---

# Question: In what path is the SSH key usually found?

**Answer:** In the `.ssh` directory inside your home folder, e.g., `~/.ssh/test_key.pub`

---

# Question: Where on GitHub can you add your SSH key?

**Answer:** Under **Settings → SSH and GPG keys**.

---

# Question: What must you do after clicking **New SSH key** in GitHub?

**Answer:** Give the key a title and paste your public key into the key field.

---

# Question: Why might you need to remove extra whitespace when pasting your SSH key on GitHub?

**Answer:** To avoid format issues or authentication errors.

---

# Question: What must you do after adding your SSH key to GitHub to make Git recognize it locally?

**Answer:** Start the SSH agent and add the key to it using the `ssh-add` command.

---

# Question: What must users of macOS 10.12.2 or later modify to ensure the SSH key is used properly?

**Answer:** They must edit their SSH configuration file and add specific settings to it.

---

# Question: Where is the SSH config file typically located?

**Answer:** Inside the `.ssh` directory in the user’s home folder.

---

# Question: What command is used to add your SSH key to the SSH agent?

**Answer:** `ssh-add path/to/your/private_key`

---

# Question: What does the `origin` argument represent in a Git push command?

**Answer:** It represents the remote repository location.

---

# Question: What does the `master` argument represent in a Git push command?

**Answer:** It specifies the branch being pushed to the remote repository.

---

# Question: What command pushes local commits to the `master` branch on the `origin` remote?

**Answer:** `git push origin master`

---

# Question: How can you confirm that your local Git push was successful?

**Answer:** By refreshing the GitHub repository page and checking if the code changes and commit appear.

---

# Question: What indicates that a commit was made locally and pushed to GitHub?

**Answer:** The presence of a commit with a message that was written locally using the `-m` flag.

---

# Question: How can you differentiate between commits made locally and those made directly on GitHub?

**Answer:** Commits pushed from local appear with the message created via the local Git CLI, while others are created via the GitHub interface.

---

# Question: What is demonstrated when code is pushed from a local Git repository to GitHub?

**Answer:** How to create a new Git repository using GitHub and push code to it.

---

# Question: What happens when you create a new folder that is not yet a Git repository?

**Answer:** It contains no `.git` folder, and Git commands like `git status` will indicate that it is not a repository.

---

# Question: How do you initialize a Git repository in a new folder?

**Answer:** By running the command `git init` inside that folder.

---

# Question: What does the `git init` command do?

**Answer:** It initializes a new Git repository in the current directory.

---

# Question: What does `git status` show after initializing a repository and creating a new file?

**Answer:** It shows that the file (e.g., `README.md`) is untracked.

---

# Question: What kind of file was first created in the new folder to track changes?

**Answer:** A `README.md` file containing a header and some text.

---

# Question: What does it mean when `git status` shows a file as “untracked”?

**Answer:** The file is not yet staged for commit and is not being tracked by Git.

---

# Question: What error occurs if you try to push to `origin` before connecting your local repository to a remote?

**Answer:** `fatal: 'origin' does not appear to be a git repository`

---

# Question: Why does Git return the error “origin does not appear to be a git repository”?

**Answer:** Because the local repository was not cloned from a remote and has no remote URL configured.

---

# Question: What is the first step to connect a local Git repository to a remote GitHub repository?

**Answer:** Create a new, empty repository on GitHub.

---

# Question: What Git command is used to connect a local repository to a remote one?

**Answer:** `git remote add origin <remote_repository_URL>`

---

# Question: In Git, what does the term "remote" refer to?

**Answer:** A repository that exists on another system or platform, not on the local machine.

---

# Question: How can you verify that a remote has been added to your Git repository?

**Answer:** Run `git remote -v` to display the connected remote repositories.

---

# Question: After adding a remote, what command can you use to push commits?

**Answer:** `git push origin master`

---

# Question: What does the `-u` flag in `git push -u origin master` do?

**Answer:** It sets the upstream so that future pushes can be done using just `git push`.

---

# Question: What is the benefit of setting an upstream with `git push -u`?

**Answer:** You can use `git push` alone in the future without specifying the branch and remote.

---

# Question: What confirms a successful push to GitHub in your browser?

**Answer:** Refreshing the repository page and seeing the newly added or modified file(s), like `README.md`.

---

# Question: What are the main steps in pushing code from a local Git repository to GitHub?

**Answer:** Initialize the repo with `git init`, create or modify files, stage changes with `git add`, commit with `git commit -m`, connect a remote with `git remote add origin <URL>`, then push with `git push`.

---

# Question: What step is automatically handled when you commit code directly on GitHub?

**Answer:** The `git add` step is handled automatically — changes are staged and committed in one action.

---

# Question: Why is there no need to push after committing changes via GitHub’s interface?

**Answer:** Because GitHub is already the remote repository — commits there are live immediately.

---

# Question: What is a pull request used for on GitHub?

**Answer:** To request that your code changes be reviewed and merged into a repository you do not own or don’t have direct write access to.

---

# Question: What are the steps involved in writing code locally and pushing it to GitHub?

**Answer:** Write code in a text editor, use `git add` to stage changes, `git commit` to save them, and `git push` to upload to GitHub.

---

# Question: How does the workflow differ between committing on GitHub and pushing from a local machine?

**Answer:** On GitHub, committing skips staging (`git add`) and changes are live immediately; locally, you must stage, commit, and then push.

---

# Question: What does the `git push` command do?

**Answer:** It updates the remote repository on GitHub with changes made locally.

---

# Question: What must be done if access rights are restricted or a code review is required before merging changes to GitHub?

**Answer:** A pull request must be created.

---

# Question: In Git, what is the default branch typically called?

**Answer:** The default branch is typically called `master`.

---

# Question: What does the term "branching" refer to in Git?

**Answer:** Branching refers to the practice of creating separate lines of development that look like branches on a tree, diverging from the main codebase.

---

# Question: When a new branch is created from `master`, what is its initial content?

**Answer:** It is exactly the same as the `master` branch at the time of creation.

---

# Question: If you make a commit on a feature branch, will those changes be visible when switching back to `master`?

**Answer:** No, changes made on the feature branch are not visible on `master`.

---

# Question: How does Git track changes across branches?

**Answer:** Each branch only tracks the changes committed to itself and is unaware of changes in other branches.

---

# Question: What happens if you make changes on the master branch while a feature branch exists?

**Answer:** Those changes are committed to master and remain invisible to the feature branch until a merge occurs.

---

# Question: Why is branching useful in software development?

**Answer:** It allows developers to build features in isolation, preventing unfinished or potentially breaking code from affecting the main codebase.

---

# Question: What is the purpose of working on a separate branch like a feature branch?

**Answer:** To develop new features safely without affecting the stable code on the master branch.

---

# Question: How does branching help when multiple people are working on the same repository?

**Answer:** It allows each person to work in isolation on their respective branches without interfering with others’ work on the master branch or other branches.

---

# Question: What is a "hotfix" branch typically used for?

**Answer:** It is used to quickly fix major bugs in the code, with the changes merged back into the master branch once resolved.

---

# Question: What is the usual workflow after fixing a bug in a hotfix branch?

**Answer:** Commit the fix in the hotfix branch, test it, and then merge it back into the master branch.

---

# Question: What does the `git branch` command do?

**Answer:** It lists all branches in the repository and shows the current branch with a star `*`.

---

# Question: What does the star `*` next to a branch in `git branch` output indicate?

**Answer:** It indicates the branch you are currently on.

---

# Question: What key do you press to exit the branch list view after running `git branch`?

**Answer:** Press the letter `Q` to exit the view.

---

# Question: What is the syntax for creating and switching to a new branch using `git checkout`?

**Answer:** `git checkout -b [branch-name]`

---

# Question: What is the purpose of the `-b` flag in `git checkout -b`?

**Answer:** It tells Git to create a new branch before switching to it.

---

# Question: What naming conventions are commonly used for Git branches in collaborative projects?

**Answer:** Names like `feature/description`, `bugfix/issue-number`, or `hotfix/description`, often including ticket or issue numbers.

---

# Question: After creating a new branch, what message does Git display?

**Answer:** `Switched to a new branch '[branch-name]'`

---

# Question: How can you confirm which branch you’re currently on after creating or switching branches?

**Answer:** By running `git branch`; the current branch will be marked with a star.

---

# Question: What does hitting `Tab` while typing a branch name do in Git?

**Answer:** It autocompletes the branch name if it matches a known branch.

---

# Question: Can you use `Tab` completion starting from the middle or end of a branch name?

**Answer:** Yes, partial matches from any part of the branch name will autocomplete.

---

# Question: Why is `Tab` completion useful when working with many Git branches?

**Answer:** Because many branches share prefixes like `feature/`, the unique part is often at the end, making tab-completion faster.

---

# Question: What does the letter `M` beside a file in VS Code signify in Git context?

**Answer:** It means the file has been modified since the last commit.

---

# Question: What does the `git status` command do?

**Answer:** It shows which files have been changed, staged, or are untracked.

---

# Question: After modifying a file, what is the first Git command used to save the change?

**Answer:** `git add [filename]`

---

# Question: What command is used to stage changes in Git?

**Answer:** `git add` is used to stage changes in Git, such as staging changes made to the `README.md` file.

---

# Question: How do you make a Git commit with a message?

**Answer:** You use `git commit -m "your message"` to make a Git commit with a message. The message must be enclosed in quotes.

---

# Question: What does Git show after a successful commit?

**Answer:** It shows output like the number of files changed and the number of insertions or deletions (e.g., "1 file changed, 4 insertions").

---

# Question: Where are changes saved after a commit on a branch?

**Answer:** Changes are saved locally on the current branch and not visible in other branches until merged.

---

# Question: What command is used to switch branches in Git?

**Answer:** `git checkout branch-name` is used to switch between branches, such as switching from `feature-readme-instructions` to `master`.

---

# Question: Why might changes not appear after switching to the master branch?

**Answer:** Because the changes were made and committed on another branch and haven't been merged into `master`.

---

# Question: What command is used to merge one branch into another locally?

**Answer:** `git merge branch-name` is used to merge the specified branch into the current branch.

---

# Question: Before merging, what command can be used to preview the differences?

**Answer:** `git diff branch-name` shows the differences between the current branch and the specified branch.

---

# Question: What does the `git diff` output show?

**Answer:** It shows the file(s) affected, unchanged lines in white, added lines in green with a `+`, and removed lines in red with a `-`.

---

# Question: How do you exit the `git diff` view?

**Answer:** Press `q` to quit the diff view.

---

# Question: What is the typical process after committing changes to a branch locally?

**Answer:** The common practice is to push the changes to GitHub and create a pull request (PR).

---

# Question: What command is used to push changes to GitHub?

**Answer:** `git push` is used to push changes to GitHub.

---

# Question: What happens when you push a new local branch to GitHub for the first time?

**Answer:** Git prompts you to specify the remote branch name, typically using `git push --set-upstream origin branch-name`.

---

# Question: What does the `--set-upstream` or `-u` flag in Git do?

**Answer:** It links the local branch to the remote branch, so future `git push` and `git pull` commands default to that branch.

---

# Question: What is a pull request (PR) in GitHub?

**Answer:** A pull request is a request to merge code from one branch (e.g., a feature branch) into another (e.g., master).

---

# Question: What can happen after a pull request is made?

**Answer:** Reviewers can comment on the code, request changes, and developers can update the PR by making new commits and pushing them to the same branch.

---

# Question: Can you update a PR after it’s created?

**Answer:** Yes, by making additional commits to the same branch and pushing them to GitHub.

---

# Question: What typically happens after a PR is successfully merged?

**Answer:** The feature or source branch is usually deleted, and developers switch back to the master branch.

---

# Question: What is the common Git workflow for new coding changes after a PR?

**Answer:** Create a new branch, make commits, push to GitHub, create a pull request, and repeat the cycle.

---

# Question: What happens on GitHub when you push a new branch?

**Answer:** GitHub detects the new branch and prompts you to compare it to another branch and create a pull request.

---

# Question: In the GitHub interface, how can you tell which branch is being merged into which?

**Answer:** The arrow in the GitHub interface indicates the direction of the merge — the feature branch will be merged *into* the base branch.

---

# Question: What is the base branch in a GitHub pull request?

**Answer:** The base branch is the branch into which changes from another branch will be merged, typically `master` or `main`.

---

# Question: What information can you include when creating a pull request on GitHub?

**Answer:** You can include a title, a message, and a description listing the changes made and reasons behind them.

---

# Question: What kinds of views are available after you create a PR on GitHub?

**Answer:** You can view comments, commits made, and diffs of changed files in the pull request interface.

---

# Question: How can you leave a comment on a specific line of code in a GitHub PR?

**Answer:** Click the blue plus (`+`) button next to a line of code to open a comment box and leave a comment.

---

# Question: What is the benefit of commenting on a specific line of code in a PR?

**Answer:** It allows collaborators to provide targeted feedback on individual lines, making reviews more precise and collaborative.

---

# Question: What does the "Resolve" button in a GitHub PR comment thread indicate?

**Answer:** It indicates that a comment thread has been addressed or acknowledged, often after changes are made or questions are answered.

---

# Question: Do you need to resolve all comments before merging a PR?

**Answer:** Not always. If you have full permissions (e.g., you're the repo owner), you can merge without resolving comments. Otherwise, resolution may be required based on repository settings.

---

# Question: What does clicking “Merge” and then “Confirm” in a PR do?

**Answer:** It finalizes the PR by merging the changes from the feature branch into the base branch (e.g., `master`).

---

# Question: After merging a PR, where are the changes visible?

**Answer:** They become part of the base branch on GitHub (e.g., `master`) and can be seen by viewing the code in the GitHub interface.

---

# Question: Why might you not see merged PR changes in your local master branch?

**Answer:** Because the changes exist only on GitHub until you pull them into your local repository.

---

# Question: What command do you use to pull the latest changes from GitHub into your local branch?

**Answer:** Use `git pull` to fetch and merge changes from the remote repository into your current local branch.

---

# Question: What’s the difference between `git pull` and `git pull origin master`?

**Answer:** `git pull` uses the set upstream branch, while `git pull origin master` explicitly pulls from the `origin/master` branch when upstream isn’t set.

---

# Question: What message might you see after pulling from GitHub successfully?

**Answer:** A message like “1 file changed, 4 insertions” indicating that updates have been applied to your local branch.

---

# Question: After pulling, how do you verify that your local branch includes the changes?

**Answer:** Check the code files in your local environment to confirm the updates from the remote branch are now present.

---

# Question: What is Git stash used for?

**Answer:** Git stash temporarily stores local changes without committing them, allowing you to switch branches safely and retrieve the changes later.

---

# Question: What command stages and commits all modified tracked files with a message?

**Answer:** `git commit -am "commit message"`

---

# Question: Why is `git commit -am` used in this scenario?

**Answer:** Because only modified files (not new ones) were present, and it provides a quick way to stage and commit them together.

---

# Question: What Git command shows differences between the current branch and another branch?

**Answer:** `git diff <branch_name>`

---

# Question: Why might you want to merge `master` into your feature branch before continuing development?

**Answer:** To keep the feature branch up to date with the latest changes from `master`, avoiding larger conflicts later.

---

# Question: What command merges the `master` branch into the current branch?

**Answer:** `git merge master`

---

# Question: What message does Git show when a merge conflict occurs?

**Answer:** It indicates there is a conflict and specifies the file(s) involved, such as `merge conflict in index.html`.

---

# Question: What are common ways to resolve Git merge conflicts?

**Answer:** Using GitHub’s interface, editing the file manually in a code editor, or using tools like VS Code’s merge resolution UI.

---

# Question: In a merge conflict, what do the Git conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`) indicate?

**Answer:** They show the conflicting changes:

* `<<<<<<< HEAD`: your branch’s changes
* `=======`: separator
* `>>>>>>> branch_name`: incoming branch’s changes

---

# Question: After resolving a merge conflict manually, what must you do?

**Answer:** Remove the conflict markers, save the file, and make a new commit to finalize the merge.

---

# Question: What is an appropriate commit message after resolving a merge conflict?

**Answer:** Something like `"merged in master"` or `"resolved conflicts and updated with master"`.

---

# Question: Why is a new commit needed after fixing merge conflicts?

**Answer:** Because Git treats the resolution as a change that must be recorded to complete the merge process.

---

# Question: After updating your feature branch with `master`, what should you do next?

**Answer:** Continue developing your feature, fix, or enhancement as normal.

---

# Question: If you accidentally commit something in Git, what can you do?

**Answer:** You can undo the commit using Git commands to reset or unstage changes (covered in the next part of the transcript).

---

# Question: What does the `git status` command show after adding a file with `git add`?

**Answer:** It shows that the file is staged under “changes to be committed.”

---

# Question: How can you unstage a file after you've accidentally staged it with `git add`?

**Answer:** Use `git reset` with or without the file name to unstage it.

---

# Question: What message does Git display after using `git reset` to unstage a file?

**Answer:** “Unstaged changes after reset” followed by the file name.

---

# Question: What is the result of running `git status` after using `git reset` to unstage a file?

**Answer:** The file appears under “changes not staged for commit.”

---

# Question: How do you commit a staged file in Git?

**Answer:** Use `git commit -m "<message>"`, for example: `git commit -m "added install step"`.

---

# Question: What does `git status` show after committing changes?

**Answer:** “Nothing to commit, working tree clean,” indicating all changes have been committed.

---

# Question: How do you undo your last Git commit but keep the changes?

**Answer:** Use `git reset HEAD~1`.

---

# Question: What does `HEAD` represent in Git?

**Answer:** `HEAD` is a pointer to the last commit.

---

# Question: What does `git reset HEAD~1` do specifically?

**Answer:** It resets `HEAD` to point to the commit before the last one, effectively undoing the last commit and unstaging the changes.

---

# Question: What does Git display after using `git reset HEAD~1`?

**Answer:** It says the changes were unstaged and uncommitted.

---

# Question: What command can you use to view what Git now considers unstaged changes after a reset?

**Answer:** `git diff`

---

# Question: What does `git diff` show after undoing a commit?

**Answer:** The changes from the undone commit now appear as new, unstaged changes.

---

# Question: How are commits arranged in `git log`?

**Answer:** In reverse chronological order, with the latest commit first.

---

# Question: Why is writing a good commit message important?

**Answer:** It helps humans quickly identify and understand each commit when scrolling through the log.

---

# Question: How can you identify a specific commit in Git history?

**Answer:** By its unique hash shown in the `git log`.

---

# Question: How can you reset to a specific past commit?

**Answer:** Use `git reset <commit-hash>`.

---

# Question: What happens when you run `git reset <commit-hash>`?

**Answer:** Git unstages and uncommits all changes made after that commit but preserves the working directory changes.

---

# Question: What key difference is there between `git reset` and `git reset --hard`?

**Answer:** `git reset` keeps changes in the working directory; `git reset --hard` completely removes them.

---

# Question: What does `git reset --hard <commit-hash>` do?

**Answer:** It resets the working directory and index to match the given commit, erasing all changes after it.

---

# Question: What happens to the `HEAD` pointer after using `git reset --hard`?

**Answer:** It points to the specified commit, effectively rolling back the repo to that state.

---

# Question: What is the result of using `git reset --hard` on your files?

**Answer:** All changes made after the target commit are permanently erased from both Git and the filesystem.

---

# Question: What does forking a repository on GitHub do?

**Answer:** It creates a complete copy of the repository under your GitHub account, giving you full control over the code.

---

# Question: Why would you fork someone else’s repository instead of your own?

**Answer:** You fork someone else’s repository when you don’t have direct access to modify their code, but want to make changes or contributions.

---

# Question: What can you do after forking a repository to your GitHub account?

**Answer:** You can create branches, edit files, commit changes, and push updates independently of the original repository.

---

# Question: What is the default branch typically used in a GitHub repository?

**Answer:** It is often `master`, but can also be `dev` or any other branch designated as default.

---

# Question: What is one reason a project might use multiple branches like `master`, `dev`, and `staging`?

**Answer:** To separate environments: `dev` for development, `staging` for pre-production, and `master` for production-ready code.

---

# Question: After forking and editing a file like `README.md`, how do you save your changes?

**Answer:** By committing the changes, optionally with a custom commit message, and specifying the branch to commit to.

---

# Question: Where do changes appear after committing in a forked repo?

**Answer:** They appear in your fork, not in the original repository.

---

# Question: How can you propose your changes from a forked repository to the original repository?

**Answer:** By creating a pull request (PR) comparing your updated fork/branch with the base branch in the original repository.

---

# Question: When creating a pull request, what two elements must you specify?

**Answer:** The base (original repository and branch) and the compare (your fork and updated branch).

---

# Question: What GitHub feature allows you to preview differences in a pull request?

**Answer:** The **diff view**, which shows file changes and commit history for the PR.

---

# Question: Can you create a pull request between branches in your own forked repository?

**Answer:** Yes, you can create PRs between branches like `dev` and `master` within your fork.

---

# Question: What happens when you merge a pull request in GitHub?

**Answer:** The changes from the source branch are added to the target branch.

---

# Question: After merging a feature branch into `dev` or `master`, what is the recommended cleanup step?

**Answer:** Delete the feature branch both on GitHub and locally if it’s no longer needed.

---

# Question: Why aren’t branches like `dev` and `master` deleted after merges?

**Answer:** Because they are permanent branches used as base branches for future merges and deployment workflows.

---

# Question: What is the general workflow for contributing to a large open-source project like Vue.js?

**Answer:** Fork the repo, pull it to your local machine, make and test updates, push changes to your fork, then create a PR to the original repo.

---

# Question: What does CRUD stand for in the context of GitHub repository control?

**Answer:** Create, Read, Update, Delete — referring to full control over files in your fork.

---

# Question: What is the purpose of creating feature branches?

**Answer:** To isolate changes and updates before merging them into stable branches like `dev` or `master`.

---

# Question: When should feature or temporary branches be deleted?

**Answer:** After they are successfully merged into a mainline branch such as `dev` or `master`.

---

# Question: What is the advantage of pushing changes to a fork before creating a pull request?

**Answer:** It allows for independent testing, experimentation, and staging before proposing changes to the main repository.

---

# Question: What does the landing page of a GitHub project depict?

**Answer:**
The landing page of a GitHub project depicts the contents of a person's local Git repository, including the tree-like structure of the files.

---

# Question: What additional features does GitHub provide on the repository landing page besides the file structure?

**Answer:**
GitHub provides features such as branches, commits, and tags of the repository, bringing commonly used Git commands to the browser.

---

# Question: What is the purpose of the GitHub issue tracker?

**Answer:**
The issue tracker is used for discussions, tracking and reporting bugs, requesting features, and discussing anything relevant to the project.

# Question: What are labels and milestones in the context of GitHub issues?

**Answer:**
Labels and milestones are features on top of the issue tracker that allow better visualization and categorization of issues.

---

# Question: Why is the main page of a repository important?

**Answer:**
The main page is where people spend most of their time when visiting a project, serving as the hub to explore repository content and features.

---

# Question: How do you start creating a new repository on GitHub after signing up?

**Answer:**
Navigate to the top-right corner, click the plus (+) icon next to your username, and select "New repository."

---

# Question: What is the minimal information you need to provide to create a new repository on GitHub?

**Answer:**
You need to provide a repository name, which will form the URL for your repository.

---

# Question: What is the typical URL scheme for a GitHub repository?

**Answer:**
The URL scheme is: `https://github.com/<username>/<repository_name>`

---

# Question: What options can you set about the visibility of your GitHub repository?

**Answer:**
You can choose whether the repository is public (visible to everyone) or private (restricted access), with private repositories usually requiring payment.

# Question: What is the purpose of including a README file when creating a repository?

**Answer:**
A README file provides comprehensive information about the project, such as installation, usage instructions, and contribution guidelines.

---

# Question: Can you add a README file later if you don’t include it when creating the repository?

**Answer:**
Yes, you can always add a README file later.

---

# Question: What is a .gitignore file, and how can GitHub help with it when creating a repository?

**Answer:**
A .gitignore file specifies files to be ignored by Git, and GitHub offers templates to choose from during repository creation.

---

# Question: Why might you want to add a license file when creating a repository?

**Answer:**
A license file clarifies how others can fork, reuse, or contribute to your code, and you can add it during creation or manually later.

---

# Question: What should you do after clicking the "Create repository" button on GitHub?

**Answer:**
GitHub provides instructions on what to do next, such as pushing an existing local Git repository to GitHub or starting fresh with new code.

---

# Question: Why is it recommended to generate an SSH key for your GitHub account?

**Answer:**
Generating an SSH key allows secure communication between your local machine and GitHub, making it easier to push and pull code without repeatedly entering credentials.

---

# Question: Where can you find the official guide to generating SSH keys for GitHub?

**Answer:**
The official guide is available at [https://help.github.com/articles/generating-ssh-keys/](https://help.github.com/articles/generating-ssh-keys/).

---

# Question: What Git configuration settings should you make sure to set properly when working with GitHub?

**Answer:**
You should properly configure your Git username and email settings.

---

# Question: Where can you find guides on setting your Git username and email?

**Answer:**
Guides are available at [https://help.github.com/articles/setting-your-username-in-git/](https://help.github.com/articles/setting-your-username-in-git/) and [https://help.github.com/articles/setting-your-email-in-git/](https://help.github.com/articles/setting-your-email-in-git/).

---

# Question: What URL do you visit to access the main page of your GitHub repository?

**Answer:**
You visit `https://github.com/<username>/<repository>`, where `<username>` is your GitHub username and `<repository>` is the repository name.

---

# Question: What does the `<username>` in the GitHub repository URL represent?

**Answer:**
It represents the GitHub username you registered with, which can be found at the top-right corner of the GitHub page.

---

# Question: How does GitHub’s web UI relate to common git commands?

**Answer:**
GitHub’s web UI presents many common git commands visually, making it easier to interact with repository features like commits.

---

# Question: What are the steps to create a README file and push it to GitHub from the command line?

**Answer:**

1. Create and enter a directory: `mkdir -p ~/github-essentials && cd $_`
2. Create README.md: `echo "# github-essentials" >> README.md`
3. Initialize git: `git init`
4. Stage README.md: `git add README.md`
5. Commit changes: `git commit -m "first commit"`
6. Add remote origin: `git remote add origin git@github.com:<username>/<repository>.git`
7. Push to master branch: `git push -u origin master`

---

# Question: Why is the SSH-based Git protocol (`git@github.com`) preferred when pushing code?

**Answer:**
Because it uses SSH underneath, so you don't have to enter your username and password every time you push or pull code.

---

# Question: Does the local directory name need to match the repository name on GitHub?

**Answer:**
No, the local directory name can be different. The important part is that the remote URL set with `git remote add` matches the GitHub repository URL.

---

# Question: What happens to the commit count on the GitHub project main page as you add more commits?

**Answer:**
The total number of commits increases and is displayed on the project’s main page as a clickable link.

---

# Question: What information can you see on the commits page on GitHub?

**Answer:**
You can browse the list of commits and see details similar to the output of the `git log` command, such as commit hashes, authors, dates, and commit messages.

---

# Question: How does the output of `git log` on your local machine compare to the GitHub commits page?

**Answer:**
Both show the same commit information, but GitHub presents it in a user-friendly graphical interface.

---

# Question: What three key pieces of information are shown for each commit on GitHub?

**Answer:**
The commit message, the time it was committed, and the commit SHA (shortened to the first 7 characters).

---

# Question: What happens when you click on the commit SHA or the commit message on GitHub?

**Answer:**
You see the detailed changes introduced by that specific commit.

---

# Question: How does GitHub’s view of a commit compare to the `git show <commit>` command?

**Answer:**
GitHub’s view displays the same detailed commit information and diffs as the `git show <commit>` command but in a graphical format.

---

# Question: What is the purpose of displaying the commit message in big bold letters on GitHub?

**Answer:**
To emphasize the importance of the commit message as it conveys the key changes or purpose of the commit.

---

# Question: Where on GitHub can you see which branches include a specific commit?

**Answer:**
Just under the commit message, GitHub shows the branches where the commit is included.

---

# Question: What additional information does GitHub show under the commit details besides the SHA, author, and date?

**Answer:**
GitHub shows how many files changed during the commit and the number of additions and deletions made.

---

# Question: How does GitHub visually represent added and removed changes in a commit?

**Answer:**
Added changes are shown in green, while removed changes are shown in a pinkish color.

---

# Question: How do you create and switch to a new branch named `add_description` from the command line?

**Answer:**
Use the command: `git checkout -b add_description`

---

# Question: After creating the `add_description` branch and editing README.md, what are the steps to commit and push the changes to GitHub?

**Answer:**

1. Edit README.md and add text
2. Stage changes: `git add README.md`
3. Commit: `git commit -m "Add second level header to README file"`
4. Push to the new branch: `git push origin add_description`

---

# Question: How do you create a second branch named `new_feature` from the master branch and push it to GitHub?

**Answer:**

1. Switch to master: `git checkout master`
2. Create branch: `git branch new_feature`
3. Push branch: `git push origin new_feature`

---

# Question: How many branches are visible on the main GitHub repository page after pushing the new branches?

**Answer:**
Three branches are visible on the main repository page.

---

---

# Question: What information does the Overview page of the branches tab provide on GitHub?

**Answer:**
It provides an overview of the default branch, branches pushed from your account (Yours tab), most active branches in the last three months (Active tab), and stale branches not updated for over three months (Stale tab).

---

# Question: How can you change the default branch that appears on your project’s homepage?

**Answer:**
You can change the default branch in the project's settings, covered in detail in Chapter 6 of the book.

---

# Question: Why might the `new_feature` branch show an earlier update time than the `add_description` branch even though it was pushed later?

**Answer:**
Because `new_feature` has the same commit date as the master branch, which is dated before the `add_description` branch’s commits.

---

# Question: What does GitHub display next to each branch regarding its commits relative to the default branch?

**Answer:**
GitHub shows the number of commits each branch is behind or ahead of the default branch.

---

# Question: How do you delete a branch like `new_feature` on GitHub?

**Answer:**
Click the red trash icon next to the branch name on the branches page to delete it.

---

# Question: What happens to the option to restore a deleted branch on GitHub if you refresh the page or navigate away?

**Answer:**
The Restore button disappears, meaning you lose the chance to restore the recently deleted branch.

---

# Question: What is the purpose of the Raw button when viewing a file on GitHub?

**Answer:**
The Raw button opens the file in its raw form without any HTML formatting, which is useful for downloading the file directly.

---

# Question: Why is the Raw file format useful when downloading files with command-line tools like Wget or Curl?

**Answer:**
Because it provides the pure file content without HTML wrappers, ensuring you download the actual file rather than an HTML page.

---

# Question: What happens if you try to download a file from GitHub without using the Raw button?

**Answer:**
You might end up downloading an HTML file instead of the actual file content.

---

# Question: When do the Raw, Blame, and History buttons appear on GitHub?

**Answer:**
They appear when viewing a single file within a repository.

---

# Question: What does the Blame button on GitHub do?

**Answer:**
It uses Git’s blame function to show who last modified each line of a file and when.

---

# Question: Why might the README.md file not be ideal to demonstrate GitHub’s Blame feature?

**Answer:**
Because it typically has very few commits or changes, so there is less line-by-line history to show.

---

# Question: What example repository is suggested for better exploring the Blame feature?

**Answer:**
The repository at [https://github.com/gitlabhq/gitlabhq](https://github.com/gitlabhq/gitlabhq), specifically the file `app/models/ability.rb`.

---

# Question: How does GitHub enhance the functionality of `git blame` compared to the terminal command?

**Answer:**
GitHub annotates every line of code showing who, when, and in what commit the line was changed, with color-coded "hotness" bars indicating older (brown) and newer (yellow) commits.

---

# Question: What does the History button on GitHub show for a particular file?

**Answer:**
It shows the commit history (similar to Git’s `git log`) for that specific file.

---

# Question: Where are the Watch, Star, and Fork buttons located on a GitHub repository page?

**Answer:**
They are located at the top-right corner of every public repository page.

---

# Question: What is the purpose of the Watch button on GitHub?

**Answer:**
It manages your subscription level to a repository’s notifications, letting you control how and when you get notified about repository activity.

---

# Question: What are the three levels of subscription for the Watch button on GitHub?

**Answer:**

1. Never notified unless explicitly participating or mentioned
2. Notified only if you participate or are mentioned
3. Always notified (default when creating a new repository)

---

# Question: Where can you view and manage your GitHub notifications?

**Answer:**
In the notifications area at [https://github.com/notifications](https://github.com/notifications), where you can also mark notifications as read.

---

# Question: How do you mention someone on GitHub to get their attention?

**Answer:**
By prefixing their username with the at sign (@). GitHub also autocompletes usernames as you type.

---

# Question: What is the purpose of the Star button on GitHub?

**Answer:**
The Star button shows appreciation for a repository and indicates its popularity. Starred repositories are added to your personal starred list.

---

# Question: Where can you find a list of all the repositories you have starred?

**Answer:**
At [https://github.com/stars](https://github.com/stars).

---

# Question: How can you see the people who have starred a specific repository?

**Answer:**
By clicking the number next to the Star/Unstar button on that repository's page.

---

# Question: What is the main purpose of the Fork button on GitHub?

**Answer:**
To create a personal copy of a repository under your own namespace so you can freely modify it, typically used to contribute to projects.

---

# Question: What happens when you fork a repository like [https://github.com/axilleas/github-essentials](https://github.com/axilleas/github-essentials)?

**Answer:**
The repository is copied to your own GitHub account, and you gain full ownership and control over that copy.

---

---

# Question: How do you add or change the description and website URL of a GitHub repository?

**Answer:**
On the main repository page, fill in the Description field with a project note and the Website field with a URL, then hit Save to apply changes immediately.

---

# Question: What is the primary use of GitHub's issue tracker?

**Answer:**
It is primarily used as a bug tracker to report and discuss bugs essential for project growth.

---

# Question: Besides bug tracking, what are some other uses of GitHub's issue tracker?

**Answer:**
It can be used for feature requests, as a discussion board for projects or blogs, and even as a notepad for personal tasks like house repairs.

---

# Question: Where can you find examples of GitHub issue trackers being used for purposes beyond bug tracking?

**Answer:**
Examples include [http://github.com/andreareginato/betterspecs/issues](http://github.com/andreareginato/betterspecs/issues) and [https://github.com/frabcus/house/issues](https://github.com/frabcus/house/issues).

---

# Question: Where do you go to see all issue activity for a GitHub repository?

**Answer:**
At [https://github.com/](https://github.com/)<username>/<repository>/issues.

---

# Question: What do you see if no issues have been created yet in a repository?

**Answer:**
A blank page with a prompt from GitHub encouraging you to open a new issue.

---

# Question: What is the minimum requirement to create a new issue on GitHub?

**Answer:**
You must provide at least a descriptive title.

---

# Question: Why is the "Submit new issue" button sometimes grayed out and unclickable?

**Answer:**
Because the required title field has not been filled in yet.

---

# Question: What can you add under the Write tab when creating a new issue?

**Answer:**
You can add detailed information and start a discussion related to the issue.

---

# Question: Who can participate in the discussion started by an issue on a public repository?

**Answer:**
Anyone who views the public repository can participate.

---

# Question: How can you attach images to a GitHub issue?

**Answer:**
By dragging and dropping the image into the issue or by selecting it using folder navigation.

---

# Question: What is the purpose of the Preview tab when creating or editing a GitHub issue?

**Answer:**
To show how the written content will look after being converted from Markdown to formatted HTML.

---

# Question: What is Markdown in the context of GitHub issues?

**Answer:**
Markdown is a text-to-HTML conversion tool that lets you write structured text easily, which GitHub then converts to valid HTML.

---

# Question: Who originally wrote Markdown?

**Answer:**
John Gruber.

---

# Question: Where can you learn more about GitHub’s extended Markdown features?

**Answer:**
At [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/).

---

# Question: What does the Preview tab display when creating or editing a GitHub issue?

**Answer:**
It displays a styled and formatted version of the issue content, showing how regular text, URLs, images, and emojis will appear after submission.

---

# Question: What formatting features does GitHub-flavored Markdown support in the Preview tab?

**Answer:**
It supports proper URL formatting, image display, emoji rendering, and other rich text features.

---

# Question: What do you do to finalize creating a new issue on GitHub?

**Answer:**
Click the "Submit new issue" button at the bottom of the page.

---

# Question: What unique identifier is assigned to each new GitHub issue?

**Answer:**
A unique issue number (e.g., #1 for the first issue).

---

# Question: What information is shown in the title area of a GitHub issue?

**Answer:**
The issue status (e.g., Open), the creator’s username, the creation time, and the number of comments.

---

# Question: How can the unique issue number be used later on?

**Answer:**
It can be used for referencing the issue in other issues, comments, or pull requests.

---

# Question: How can you edit a GitHub issue after creating it?

**Answer:**
Use the Edit button to change the title and the pencil icon to edit the issue description.

---

# Question: How do you close an issue on GitHub?

**Answer:**
Click the "Close issue" button. You can also comment and close the issue simultaneously by typing a comment, which changes the button to "Close and comment."

---

# Question: Who can be assigned to an issue in a GitHub repository?

**Answer:**
Collaborators with push access to the repository can be assigned issues.

---

# Question: Where do you assign an issue to a collaborator?

**Answer:**
Inside each issue, in the Assignee section.

---

# Question: Is it possible to assign multiple issues to a user at once?

**Answer:**
Yes, GitHub allows mass-assigning issues to a collaborator to save time.

---

# Question: What is the purpose of the `.gitattributes` file in a Git repository?

**Answer:** The `.gitattributes` file tells Git how to handle specific files in the repository, including settings for line endings, file types, merge behavior, custom diff tools, and export rules.

---

# Question: Why is `.gitattributes` versioned with a project?

**Answer:** Because it ensures that everyone on the team gets the same Git settings across all systems.

---

# Question: How does `.gitattributes` help enforce consistent line endings across operating systems?

**Answer:** By setting rules like `text eol=lf`, `.gitattributes` standardizes line endings, avoiding merge conflicts and broken files.

---

# Question: What rule would you write in `.gitattributes` to enforce LF line endings on all `.txt` files?

**Answer:** `*.txt text eol=lf`

---

# Question: What command is used to check what attributes are set for a file?

**Answer:** `git check-attr --all [filename]`

---

# Question: What is an example command to check all Git attributes on `README.md`?

**Answer:** `git check-attr --all README.md`

---

# Question: When should you use `.gitattributes` to mark a file as binary?

**Answer:** When the file should not be merged or have its line endings modified by Git.

---

# Question: What line in `.gitattributes` marks all `.png` files as binary?

**Answer:** `*.png binary`

---

# Question: What happens if you mark a file as binary in `.gitattributes`?

**Answer:** Git avoids merging the file or modifying its line endings.

---

# Question: How does `.gitattributes` relate to Git LFS?

**Answer:** It enables Git LFS by specifying filters for large files like images or datasets.

---

# Question: What rule would you use in `.gitattributes` to track `.psd` files using Git LFS?

**Answer:** `*.psd filter=lfs diff=lfs merge=lfs -text`

---

# Question: What does the `-text` flag mean in the Git LFS `.gitattributes` rule?

**Answer:** It disables Git's default text processing for that file type.

---

# Question: How can `.gitattributes` be used to define custom diff behavior?

**Answer:** By specifying a custom diff tool for a file type, such as `*.md diff=markdown`.

---

# Question: Give an example `.gitattributes` rule to use a markdown diff tool for `.md` files.

**Answer:** `*.md diff=markdown`

---

# Question: What is a practical reason to use a custom diff driver in `.gitattributes`?

**Answer:** To compare complex file formats like Markdown or Jupyter notebooks more meaningfully.

---

# Question: What is a `.gitattributes` rule to enforce LF endings specifically for shell scripts?

**Answer:** `*.sh text eol=lf`

---

# Question: How do you create or edit a `.gitattributes` file?

**Answer:** Go to the root of the repository (or a subfolder), create or open the `.gitattributes` file, and add rules line by line.

---

# Question: Where can `.gitattributes` files be placed for local rules?

**Answer:** In subfolders of the repository.

---

# Question: What are some situations where you'd use `.gitattributes`?

**Answer:** Enforcing line endings, marking files as binary, enabling Git LFS, using custom diff/merge tools, and controlling export behavior.

---

# Question: What does the rule `docs/* export-ignore` do in `.gitattributes`?

**Answer:** It prevents files in the `docs/` folder from being included in `git archive` exports (e.g., tar/zip).

---

# Question: How does `.gitattributes` support custom merge strategies?

**Answer:** By setting custom merge drivers for file types that are difficult to merge automatically, like lock files or notebooks.

---

# Question: What is a limitation of changing `.gitattributes` after files have been committed?

**Answer:** It won't retroactively fix attributes for already-committed files; they must be re-added to apply the new rules.

---

# Question: What is the recommended way to update attributes for files already committed after changing `.gitattributes`?

**Answer:** Re-add the affected files to the repository.

---

# Question: What kind of patterns can be used in `.gitattributes`?

**Answer:** The same pattern syntax as `.gitignore`, including wildcards.

---

# Question: What command can help you debug `.gitattributes` issues?

**Answer:** `git check-attr`

---

# Question: What does the `export-ignore` attribute in `.gitattributes` affect?

**Answer:** It affects the files included in archive outputs like `.tar` or `.zip` generated by `git archive`.

---

