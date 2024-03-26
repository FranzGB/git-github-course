# Git & Github Tutorial

## Git

### What is Git?

Git is a distributed version control system that allows you to track changes in your codebase. It was created by Linus Torvalds in 2005. Git is used to store the history of your codebase and allows you to collaborate with other developers. It is a powerful tool that can help you manage your codebase and keep track of changes.

### Why use Git?

Git is a powerful tool that can help you manage your codebase and collaborate with other developers. It allows you to track changes in your codebase and revert to previous versions if needed. Git also allows you to work on different features or bug fixes in parallel without interfering with each other's work. It is a great tool for managing your codebase and collaborating with other developers.

### Installing Git

To install Git, you can download it from the [official website](https://git-scm.com/downloads). Git is available for Windows, Mac, and Linux operating systems. Once you have downloaded the installer, you can follow the installation instructions to install Git on your machine.

### [Git Cheat Sheet](https://www.git-tower.com/blog/media/pages/posts/git-cheat-sheet/b5d32c23dc-1710861692/git-cheat-sheet-large01.avif)

### Glossary

- **Repository**: A repository is a collection of files and folders that make up a project. It contains the entire history of the project and allows you to track changes in your codebase.
- **Commit**: A commit is a snapshot of the codebase at a specific point in time. It records the changes made to the codebase and allows you to revert to previous versions if needed.
- **Branch**: A branch is a separate line of development in a Git repository. It allows you to work on different features or bug fixes in parallel without interfering with each other's work.2
- **Merge**: A merge is the process of combining two branches into one. It allows you to integrate changes from one branch into another branch.
- **Pull Request [PR]**: A pull request is a request to merge changes from one branch into another branch. It allows you to review the changes before merging them into the main branch.
- **Stage**: The stage is a temporary storage area in Git where you can add changes before committing them to the repository.
- **Stash**: The stash is a temporary storage area in Git where you can store changes that are not ready to be committed. It allows you to save changes and apply them later.
- **Remote**: A remote is a copy of a Git repository that is hosted on a server. It allows you to collaborate with other developers and share your codebase with them.

### Basic Git Commands

#### Local commands (Easy)

1. `git init`: Initialize a new Git repository
1. `git add .`: Add all files to the staging area
1. `git commit -m "message"`: Commit changes to the repository
1. `git status`: Check the status of the repository
1. `git log`: View the commit history
1. `git branch`: List all branches in the repository
1. `git checkout <branch>`: Switch to a different branch. If you want to create a new branch, use the `git checkout -b <branch>` command. You can also checkout into a different commit using `git checkout <commit-hash>`.
1. `git merge <branch>`: Merge changes from one branch into another branch.

#### Remote commands (Easy)

1. `git clone url`: Clone a remote repository
1. `git remote add <alias> <url>`: Add a remote repository to the local repository
1. `git push origin <branch>`: Push changes to a remote repository
1. `git pull origin <branch>`: Pull changes from a remote repository

#### Advanced Git Commands

1. `git rebase <branch>`: Rebase changes from one branch into another branch
1. `git cherry-pick <commit-hash>`: Apply changes from a specific commit to the current branch
1. `git reset --hard <commit-hash>`: Reset the repository to a specific commit
1. `git push --force origin <branch>`: Force push changes to a remote repository. Use this command with caution as it can overwrite changes in the remote repository. A safer alternative is to use `git push --force-with-lease origin <branch>`. If the remote branch has the same value as the remote branch on your local machine- you will overwrite remote. If it doesn't have the same value- it indicates a change that someone else made to the remote branch while you were working on your code and thus will not overwrite any code.
1. `git fetch`: Fetch changes from a remote repository without merging them into the local repository.
1. `git stash`: Stash changes that are not ready to be committed. You can apply the changes later using `git stash apply`.

### Useful Git Resources

## Github

### What is Github?

GitHub is a web-based platform that allows you to host your Git repositories online. It provides a graphical interface for managing your codebase and collaborating with other developers. GitHub is widely used by developers to share their codebase, collaborate on projects, and contribute to open-source projects. It is a powerful tool that can help you manage your codebase and collaborate with other developers.

### Why use Github?

GitHub is a powerful tool that can help you manage your codebase and collaborate with other developers. It provides a graphical interface for managing your codebase and allows you to collaborate with other developers. GitHub also provides features such as issues, pull requests, and project boards that can help you manage your projects more effectively. It is a great tool for managing your codebase and collaborating with other developers.

### Creating a Github Repository

