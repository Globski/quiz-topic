# Question: List commonly used Git commands.
Git is the free and open-source distributed version control system that's responsible for everything GitHub-related that happens locally on your computer. 

### 🧰 INSTALLATION & GUIs

| Tool | Description |
|------|-------------|
| [GitHub for Windows](https://windows.github.com) | Git installer and GUI for Windows |
| [GitHub for Mac](https://mac.github.com) | Git installer and GUI for Mac |
| [Git for All Platforms](http://git-scm.com) | Official Git download page (Linux, Solaris, etc.) |

---

### 🛠️ SETUP & INIT

| Command | Description |
|---------|-------------|
| `git config --global user.name "[firstname lastname]"` | Set a user name for commit history |
| `git config --global user.email "[valid-email]"` | Set an email address for commit history |
| `git config --global color.ui auto` | Enable command line coloring for Git |
| `git init` | Initialize an existing directory as a Git repository |
| `git clone [url]` | Clone an entire repository from a URL |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |
| `git --version` | Show current Git version |
| `git help` | Get help on Git commands |
| `git help [command]` | Get help for a specific Git command |

---

### STAGE & SNAPSHOT

| Command | Description |
|--------|-------------|
| `git status` | Show modified/staged files |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git add "*.txt"` | Stage all text files across the project |
| `git add docs/*.txt` | Stage all `.txt` files in `docs/` |
| `git add docs/` | Stage everything in `docs/` |
| `git reset [file]` | Unstage a file but keep the changes |
| `git commit -m "[commit message]"` | Commit changes |
| `git commit -a -m "Message"` | Automatically stage tracked files and commit |


---

### BRANCH & MERGE

| Command | Description |
|--------|-------------|
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -m [old branch name] [new branch name]` | Rename a local branch |
| `git branch -d [branch name]` | Delete a branch |
| `git branch -D Testing` | Force delete the branch |
| `git branch -r` | List remote branches |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the current branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git merge [alias]/[branch]` | Merge remote branch into local |

---

### TEMPORARY COMMITS (Stashing)

| Command | Description |
|---------|-------------|
| `git stash` | Save modified/staged changes |
| `git stash list` | View stashed changes |
| `git stash pop` | Apply and remove latest stash to working directory|
| `git stash drop` | Discard top stash entry |
| `git stash clear` | Remove all stashed entries |

---

### SHARE & UPDATE

| Command | Description |
|--------|-------------|
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git push [alias] [branch]` | Push local branch to remote |
| `git push --tags` | Push tags to remote |
| `git pull` | Fetch and merge commits from tracking branch |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |
| `git remote -v` | View the remote repository of the currently working file or directory |
| `git remote add [alias] [url]` | Add a remote Git URL alias |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |
| `git rm [file]` | Delete file and stage removal |
| `git mv [old-path] [new-path]` | Rename/move file and stage it |
| `git fetch` | Download latest changes from remote |
| `git fetch [alias]` | Fetch all branches from remote |

---

### INSPECT & COMPARE

| Command | Description |
|--------|-------------|
| `git log` | View commit history of current branch |
| `git log --summary` | View changes (detailed) |
| `git log --oneline` | View changes (briefly) |
| `git log branchB..branchA` | Show commits in A not in B |
| `git log --follow [file]` | Show history of file including renames |
| `git log --stat -M` | Show commits with path changes |
| `git diff [source branch] [target branch]` | Preview changes before merging |
| `git diff` | Show changes not staged yet |
| `git diff --staged` | Show staged changes not yet committed |
| `git diff branchB...branchA` | Show diff between A and B |
| `git show [SHA]` | Show any Git object in human-readable format |
| `git commit -m "[descriptive message]"` | Commit staged content as a snapshot |

---

### IGNORING PATTERNS

| Command/Pattern | Description |
|-----------------|-------------|
| `logs/` | Ignore entire logs directory |
| `*.notes` | Ignore all `.notes` files |
| `pattern*/` | Ignore all directories starting with `pattern` |
| `.gitignore` | Save ignore patterns here |
| `git config --global core.excludesfile [file]` | Set a global ignore file |

---


### REWRITE HISTORY

| Command | Description |
|---------|-------------|
| `git rebase [branch]` | Apply commits from current onto another branch |
| `git reset --soft HEAD^` | Undo last commit (keep staged) |
| `git reset --hard HEAD^` | Undo last commit (discard changes) |
| `git reset --hard HEAD^^` | Undo last 2 commits completely |
| `git reset --hard [commit]` | Reset staging/working tree to a commit |
| `git revert [commit]` | Revert a specific commit with a new one |
| `git reset head license` | Unstage the file `license` |

---
