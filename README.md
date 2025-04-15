# Git-version-control-basics

## What is Git?

Git is a distributed version control system that lets you track changes in your code, collaborate with others, and revert to previous versions if needed.

## Basic Git Workflow

#### 1. Initialize a new Git repo
git init

#### 2. Check current status
git status

#### 3. Add files to staging
git add filename          # or use . to add all
git add .

#### 4. Commit the changes
git commit -m "Your commit message"

#### 5. Connect to remote repo (like GitHub)
git remote add origin https://github.com/username/repo.git

#### 6. Push your code to remote
git push -u origin main   # or master depending on your default branch

## Common Git Commands

git status -  Check changes

git log -  view commit history

git branch branch-name  - Create a branch

git checkout branch-name - Switch branches

git merge branch-name  - Merge branches

git pull origin main  -  Pull latest changes

git push origin main  -  Push local changes

git clone https://url  -  Clone a repo