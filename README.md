# Learnable-Task-2

## Explain Version control

Version control is a system that tracks changes to a set of files over time.
It allows multiple contributors to work on a project simultaneously,
providing a structured way to manage and organize changes.

The primary goals of version control are to:
-Track changes
-Collaboration
-History and Rollback
-Branching and Merging
-Traceability

## Explain difference between git and github

Git and GitHub are related but serve different purposes
in the context of version control and collaborative software development.

### GIT

Git is a tool for tracking changes in code during software development.
Git is primarily used for local version control. It allows developers to create branches,
commit changes, merge branches, and maintain a complete history of the codebase.
Git operates on a developer's local machine and doesn't require a network connection to function.

Developers use Git to manage and track changes to their code, experiment with new features in separate branches, and collaborate with others. It is a command-line tool, and various graphical user interfaces (GUIs) are available to make it more user-friendly.

### GITHUB

GitHub is a website that hosts your Git repositories in the cloud. It extends the functionality of Git by providing collaboration features, issue tracking, project management tools, and a web-based interface for easier navigation and interaction with repositories.

Developers use GitHub to host their Git repositories remotely, making it easy to share code with others and collaborate on projects. It serves as a central hub for teams to work together, manage code reviews, and track issues and project milestones.

### DIFFERENCES

- Git is a distributed version control system that operates locally on a developer's machineand Github is cloudbased.
- Git is focused on version control operations such as branching, committing, merging.
- GitHub adds collaboration features, project management tools, and a web interface to interact with Git repositories.
- Git doesn't require an internet connection for basic version control operations but Github requires and internet connection.

## List 3 other github alternatives

- GitLab
- BitBucket
- SourceForge

## Explain the difference between git fetch and git pull

git fetch and git pull are both commands in Git used to update your local repository with changes from a remote repository

- Fetching retrieves the latest changes from the remote repository to your local repository, but it does not automatically update your working directory or merge the changes into your local branch. It is often used to see what changes exist in the remote repository without incorporating those changes into your current working branch.

- Pulling also retrieves changes from the remote repository, but it goes further by automatically updating your working directory and merging the changes into your current local branch. It is a convenient way to fetch changes and apply them to your local working branch in a single command.

## Explain in simple terms git rebase and the command for it

Git rebase is a Git command that allows you to change the way your changes are added to a branch. It's like rearranging or rewriting your commit history. It's a way to organize your commits in a cleaner and more linear way. Instead of merging changes into a branch, it moves your changes to the tip of another branch and it can make your commit history look more straightforward and easier to understand.

The command is "$git rebase"

## Explain in simple terms git cherry-pick and the command for it

Git cherry-pick is a Git command that allows you to pick specific commits from one branch and apply them to another branch. It's like selecting certain changes and copying them to a different branch. This makes it very seful when you only want certain changes from one branch and not the entire branch.

The command is "$git cherry-pick"
