# Git & Github Tutorial
[Spanish Version](README_ES.md)
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
1. `git status`: Check the status of the repository
1. `git add .`: Add all files to the staging area
1. `git commit -m "message"`: Commit changes to the repository
1. `git log`: View the commit history
1. `git checkout <branch>`: Switch to a different branch. If you want to create a new branch, use the `git checkout -b <branch>` command. You can also checkout into a different commit using `git checkout <commit-hash>`.
1. `git branch`: List all branches in the repository
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
1. `git commit --amend`: Amend the last commit with new changes


## Github

### What is Github?

GitHub is a web-based platform that allows you to host your Git repositories online. It provides a graphical interface for managing your codebase and collaborating with other developers. GitHub is widely used by developers to share their codebase, collaborate on projects, and contribute to open-source projects. It is a powerful tool that can help you manage your codebase and collaborate with other developers.

### Why use Github?

GitHub is a powerful tool that can help you manage your codebase and collaborate with other developers. It provides a graphical interface for managing your codebase and allows you to collaborate with other developers. GitHub also provides features such as issues, pull requests, and project boards that can help you manage your projects more effectively. It is a great tool for managing your codebase and collaborating with other developers.

### Creating a Github Repository

Here’s a step-by-step guide on how to create a new repository on GitHub:

### 1. Sign In to GitHub
First, you need to sign in to your GitHub account. If you don't have an account, you will need to create one at [github.com](https://github.com/).

### 2. Create a New Repository
- Once logged in, navigate to your GitHub dashboard. You can create a new repository by clicking the "+" icon in the top-right corner of the page and selecting "New repository" from the dropdown menu.
- Alternatively, you can go directly to the new repository page using this URL: [https://github.com/new](https://github.com/new).

### 3. Configure Your Repository
- **Repository Name**: Enter a unique name for your repository. This name will be part of the URL for your repository.
- **Description** (optional): Provide a brief description of your project. This helps others understand what your project is about and can be found in search results.
- **Visibility**: Choose whether your repository will be public (visible to anyone) or private (visible only to you and those you grant access).
- **Initialize this repository with**: Although optional, it’s often helpful to initialize the repository with a README file, which can include information about your project. You can also add a `.gitignore` file, which specifies intentionally untracked files to ignore, and choose a license for your project.

### 4. Create Repository
- After configuring your repository, click the "Create repository" button at the bottom of the page.

### 5. Clone the Repository (Optional)
- Once the repository is created, you may want to clone it to your local machine to start working on your project. You can do this by clicking the "Code" button on your repository page, copying the URL provided, and then using the command `git clone <repository-url>` in your terminal or command prompt.

### Key Points
- **README.md**: A Markdown file where you can introduce and explain your project. It supports formatting and can contain images, links, and structured documentation.
- **.gitignore**: A text file listing files or directories that Git should ignore. Useful for excluding local configuration files, build directories, or files containing sensitive information.
- **License**: Choosing a license is important if you intend to share your code. It defines how others can use, modify, and distribute your code.

Creating a GitHub repository not only allows for version control and code management but also opens up collaboration opportunities, issue tracking, and the integration of various development tools and CI/CD pipelines. GitHub’s interface and documentation provide comprehensive support, making it accessible for developers of all skill levels.

### Fork
A fork in Git is essentially a copy of a repository that allows you to freely experiment with changes without affecting the original project. This concept is widely utilized in open-source development on platforms like GitHub, where forking a repository enables you to make your own modifications, add new features, or fix bugs in the project independently of the main repository.


