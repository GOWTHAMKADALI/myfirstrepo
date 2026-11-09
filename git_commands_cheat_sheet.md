# Git Commands Cheat Sheet

## 1. Setup & Configuration
git config --global user.name "Your Name"       # Set your commit username
git config --global user.email "your@email.com"  # Set your commit email
git init                                        # Initialize a local Git repository

## 2. Starting a Project
git clone <url>                                 # Clone a remote repository

## 3. Staging & Committing
git status                                      # View changed files in working directory
git add <file>                                  # Add a specific file to staging area
git add .                                       # Add all changed files to staging area
git commit -m "Commit message"                  # Commit staged changes with a message

## 4. Branching & Merging
git branch                                      # List local branches
git branch <branch-name>                        # Create a new branch
git checkout <branch-name>                      # Switch to a specific branch
git switch -c <branch-name>                     # Create and switch to a new branch
git merge <branch-name>                         # Merge specified branch into current branch

## 5. Sharing & Updating
git fetch                                       # Get latest changes from remote (no merge)
git pull                                        # Pull and merge latest changes from remote
git push origin <branch-name>                   # Push local commits to remote repository

## 6. Inspection & Undo
git log                                         # View commit history
git diff                                        # View unstaged changes
git reset --hard HEAD                           # Discard all local changes since last commit
