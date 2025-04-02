# Git Commands Cheat Sheet

## Checking Status
```
git status
```

## Branch Management
```
git branch           # List branches
git checkout <branch> # Switch to branch
git checkout -b <new_branch> # Create and switch to a new branch
git branch -d <branch> # Delete a branch
```

## Adding and Removing Files
```
git add <file>       # Stage a file
git rm --cached <file> # Unstage a file
git restore <file>   # Restore a file from the last commit
```

## Committing Changes
```
git commit -m "commit message"  # Commit staged changes with a message
git commit <file>               # Commit specific file(s)
```

## Merging and Switching Branches
```
git checkout master         # Switch to master branch
git checkout dev            # Switch to dev branch
git merge <branch>          # Merge branch into the current branch
```

## Viewing History
```
git log               # Show commit history
git log --oneline     # Show brief commit history
```

## Creating and Managing Files
```
touch <file>          # Create a new file
rm -v <file>          # Remove a file
vim <file>            # Open file in Vim editor
ls                    # List files in the directory
```
