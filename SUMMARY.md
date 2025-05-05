# Git Workshop: Day 1 Summary

## Introduction to Version Control

Version control is a system that records changes to files over time, allowing you to recall specific versions later. It's important because it:

- **Tracks history**: Maintains a complete history of who changed what, when, and why
- **Enables collaboration**: Multiple people can work on the same codebase without interfering with each other
- **Provides backup**: Acts as a distributed backup system for your code
- **Supports experimentation**: Allows developers to try new ideas in branches without affecting the main code
- **Ensures accountability**: Every change is attributed to a specific author

## Git vs. GitHub

### What is Git?
Git is a distributed version control system designed for speed, data integrity, and support for distributed, non-linear workflows. It was created by Linus Torvalds in 2005 for Linux kernel development.

**Key characteristics of Git**:
- Free and open-source
- Runs locally on your computer
- Tracks changes to any set of files
- Maintains a complete history of your project
- Works offline, no internet required for most operations

### What is GitHub?
GitHub is a web-based hosting service for Git repositories. It adds collaboration features such as:

- Remote repository hosting
- Pull requests and code reviews
- Issue tracking
- Project management tools
- Social coding features (stars, following, etc.)
- Wikis and documentation

GitHub essentially provides a centralized place to store your Git repositories online, making collaboration easier.

## Basic Git Commands Learned

### Configuration
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
This sets up your identity for all Git repositories on your machine. Git uses this information to attribute commits to you.

### Initializing a Repository
```
git init
```
Creates a new Git repository in the current directory by adding a hidden `.git` folder that contains all the necessary metadata.

### Tracking Files
```
git add <filename>
git add .   # Adds all files in the directory
```
Adds files to the staging area, preparing them for commit. This tells Git which changes you want to include in your next commit.

### Committing Changes
```
git commit -m "Commit message"
```
Creates a snapshot of the files in the staging area. The commit message should be a clear, concise description of the changes made.

### Checking Status
```
git status
```
Shows the current state of your working directory and staging area:
- Which files are modified but not staged
- Which files are staged but not committed
- Which files are untracked

### Viewing History
```
git log
```
Displays a chronological list of commits, showing:
- Commit hash (unique identifier)
- Author
- Date and time
- Commit message

## Best Practices To Learn

1. **Write meaningful commit messages** that clearly describe what changes were made and why
2. **Commit frequently** to create logical, atomic snapshots of your work
3. **Check status often** to understand what's happening in your repository
4. **Review your history** to understand how the project has evolved
5. **Configure Git properly** before starting to work, ensuring your identity is correctly set

## Next Steps

Future sessions will likely cover:
- Branching and merging
- Remote repositories and collaboration
- Resolving conflicts
- Advanced Git features

---

*This summary encapsulates the fundamental concepts and commands covered in Day 1 of the Git workshop, providing a foundation for version control with Git.*
