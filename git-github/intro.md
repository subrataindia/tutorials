# GIT

Git is a distributed version control system (DVCS) that is widely used for tracking changes in source code during software development. It allows multiple developers to collaborate on a project by managing and tracking changes to the source code. Git was created by Linus Torvalds in 2005 and has become a standard tool in the software development industry.

# GITHUB

GitHub, on the other hand, is a web-based platform that provides hosting for Git repositories. It adds a graphical interface and additional features to Git, making it easier to collaborate on projects. GitHub allows developers to share their code with others, contribute to open-source projects, and manage their code repositories more effectively.

## In summary:

- Git is the version control system itself, a tool for tracking changes in source code.
- GitHub is a web-based platform that provides hosting for Git repositories, adding a user-friendly interface and collaborative features.

While Git can be used without GitHub, GitHub leverages the power of Git and provides a platform for collaboration, code review, issue tracking, and more. There are also other platforms similar to GitHub, such as GitLab and Bitbucket, which offer similar services but may have different features and pricing structures.

## Basic Git commands

- `git init` : Initializes a new Git repository in the current directory.
- `git add <file(s)>` : Adds changes in the working directory to the staging area.
- `git add .` : Adds all changed files in the working directory to the staging area.
- `git commit -m "Commit message"` : Records changes in the staging area with a commit message.
- `git clone <repository_url>` : Clones a remote repository into a new local directory.
- `git push` : Pushes changes from the local repository to a remote repository.
- `git pull` : Fetches changes from a remote repository and merges them into the current branch.
- `git status` : Shows the status of changes as untracked, modified, or staged.
- `git branch` : Lists all branches
- `git branch <branch_name>` : Creates a new branch
- `git checkout <branch_name>` : Switches to a different branch or restores working tree files.
- `git checkout -b <branch_name>` : Creates a new branch and switches to that.
- `git remote -v` : Lists remote repositories connected to your local repository.
- `git fetch` : Fetches changes from a remote repository without merging.
- `git diff` : Shows the differences between the working directory and the staging area.
- `git log` : Displays a log of all commits in reverse chronological order.
- `git merge <branch_name>` : Combines changes from one branch into another.
- `git branch -d <branch_name>` : This command will delete the specified branch if it has been fully merged into the branch you are currently on. If the branch contains changes that are not merged, Git will prevent you from deleting it using the -d option.
- `git branch -D <branch_name>` : Be cautious when using the -D option, as it discards any changes that are not merged.

  
