# Git Commands Cheat Sheet

## 1. Setting Up Git

### Initialize a repository
`git init`

### Check Git version
`git --version`

### Set user name
`git config --global user.name "Your Name"`

### Set user email
`git config --global user.email "your_email@example.com"`

## 2. Working with Repositories

### Check the status of the repository
`git status`

### List all configured remotes
`git remote -v`

### Clone a repository
`git clone <repository_url>`

## 3. Staging and Committing Changes

### Add a file to staging
`git add <file_name>`

### Add all changes to staging
`git add .`

### Commit changes with a message
`git commit -m "Your commit message"`

### Commit all changes directly
`git commit -a -m "Your commit message"`

## 4. Branching

### List all branches
`git branch`

### Create a new branch
`git branch <branch_name>`

### Switch to a branch
`git checkout <branch_name>`

### Create and switch to a new branch
`git checkout -b <branch_name>`

## 5. Merging and Deleting Branches

### Merge a branch into the current branch
`git merge <branch_name>`

### Delete a branch locally
`git branch -d <branch_name>`

### Delete a branch remotely
`git push origin --delete <branch_name>`

## 6. Undoing Changes

### Unstage a file
`git reset <file_name>`

### Undo the last commit (keep changes)
`git reset --soft HEAD~1`

### Undo the last commit (discard changes)
`git reset --hard HEAD~1`

### Restore a deleted file
`git checkout -- <file_name>`

## 7. Working with Remote Repositories

### Push local changes to remote
`git push origin <branch_name>`

### Pull changes from remote
`git pull origin <branch_name>`

### Fetch latest changes without merging
`git fetch`

## 8. Viewing Commit History

### View commit history
`git log`

### View commit history in one line
`git log --oneline`

### View changes in the last commit
`git show`

## 9. Stashing Changes

### Stash current changes
`git stash`

### List all stashes
`git stash list`

### Apply the latest stash
`git stash apply`

## 10. Deleting Files

### Remove a file from the repository and the filesystem
`git rm <file_name>`

### Remove a file only from tracking but keep it locally
`git rm --cached <file_name>`

## 11. Checking Differences

### Check changes between commits
`git diff`

### Check changes of a specific file
`git diff <file_name>`
