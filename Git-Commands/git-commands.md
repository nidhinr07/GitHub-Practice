# Git Commands Cheat Sheet

A collection of the most important Git commands for everyday development.

### 1. git --version
Checks the installed Git version.

### 2. git config --global user.name "Your Name"
Sets your Git username globally.

### 3. git config --global user.email "you@example.com"
Sets your Git email globally.

### 4. git init
Initializes a new Git repository in the current folder.

### 5. git clone <repository-url>
Downloads an existing remote repository to your computer.

### 6. git status
Shows the current state of your working directory.

### 7. git add <file>
Adds a specific file to the staging area.

### 8. git add .
Adds all changed files to the staging area.

### 9. git commit -m "message"
Saves staged changes with a descriptive commit message.

### 10. git log
Shows the commit history of the repository.

### 11. git log --oneline
Shows the commit history in a short format.

### 12. git diff
Shows the changes that have not been staged.

### 13. git remote -v
Shows the remote repositories connected to your project.

### 14. git remote add origin <repository-url>
Connects your local repository to a remote GitHub repository.

### 15. git push
Uploads local commits to the remote repository.

### 16. git push -u origin main
Uploads the main branch and sets it as the default upstream branch.

### 17. git pull
Downloads and integrates the latest changes from the remote repository.

### 18. git fetch
Downloads remote changes without merging them into your current branch.

### 19. git branch
Lists all local branches.

### 20. git branch <branch-name>
Creates a new branch.

### 21. git switch <branch-name>
Switches to another branch.

### 22. git switch -c <branch-name>
Creates a new branch and switches to it.

### 23. git merge <branch-name>
Merges another branch into the current branch.

### 24. git branch -d <branch-name>
Deletes a local branch that has been merged.

### 25. git restore <file>
Discards unstaged changes in a file.

### 26. git restore --staged <file>
Removes a file from the staging area without deleting its changes.

### 27. git rm <file>
Removes a file from Git and the working directory.

### 28. git mv <old-name> <new-name>
Renames or moves a file while tracking the change with Git.

### 29. git stash
Temporarily saves uncommitted changes.

### 30. git revert <commit-hash>
Creates a new commit that safely undoes the changes from an earlier commit.
