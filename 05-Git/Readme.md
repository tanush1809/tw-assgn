
# 05 - Git

## Introduction
Git is a free and open-source distributed version control system. It is used to track changes in source code and collaborate with other developers.

## Features of Git
- Tracks changes in files.
- Maintains different versions of a project.
- Allows multiple developers to work together.
- Helps restore previous versions.
- Supports branching and merging.

## Important Git Commands

### 1. git config
Used to configure username and email.

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### 2. git init
Initializes a new Git repository.

```bash
git init
```

### 3. git status
Displays the current status of files.

```bash
git status
```

### 4. git add
Adds files to the staging area.

```bash
git add filename
git add .
```

### 5. git commit
Saves staged changes in the repository.

```bash
git commit -m "Initial commit"
```

### 6. git log
Displays the commit history.

```bash
git log
git log --oneline
```

### 7. git diff
Displays changes made to files.

```bash
git diff
```

### 8. git branch
Displays or creates branches.

```bash
git branch
git branch new-branch
```

### 9. git checkout
Switches between branches.

```bash
git checkout branch-name
```

### 10. git merge
Combines changes from different branches.

```bash
git merge branch-name
```

### 11. git remote
Displays remote repository information.

```bash
git remote -v
```

### 12. git clone
Creates a local copy of a remote repository.

```bash
git clone repository-url
```

### 13. git push
Uploads local commits to a remote repository.

```bash
git push origin main
```

### 14. git pull
Downloads and integrates changes from a remote repository.

```bash
git pull origin main
```

## Conclusion
Git is an important tool for software development. It helps developers track changes, manage different versions of projects, and collaborate efficiently.
