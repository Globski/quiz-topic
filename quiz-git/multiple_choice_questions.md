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
