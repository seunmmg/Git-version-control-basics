# Git-version-control-basics

## What is Git?

Git is a distributed version control system that lets you track changes in your code, collaborate with others, and revert to previous versions if needed.

## Basic Git Workflow

#### 1. Initialize a new Git repo
git init

![](./img/1.Git%20Init.png)

#### 2. Check current status
git status

#### 3. Add files to staging
git add filename          # or use . to add all
git add .

![](./img/4.Git%20add.png)

#### 4. Commit the changes
git commit -m "Your commit message"

![](./img/5.Git%20Commit.png)

#### 5. Connect to remote repo (like GitHub)
git remote add origin https://github.com/username/repo.git

#### 6. Push your code to remote
git push -u origin main   # or master depending on your default branch

## Common Git Commands

git status -  Check changes

![](./img/2.Git%20status.png)

git log -  view commit history

![](./img/3.Git%20log.png)

git branch branch-name  - Create a branch

![](./img/7.Git%20branch.png)

git checkout branch-name - Switch branches

![](./img/8.Git%20checkout.png)

git merge branch-name  - Merge branches

![](./img/9.Git%20merge.png)

git pull origin main  -  Pull latest changes

![](./img/10.Git%20pull.png)

git push origin main  -  Push local changes

![](./img/6.%20Git%20push.png)

git clone https://url  -  Clone a repo

![](./img/11.Git%20clone.png)

# Github Dashboard

![](./img/12.Git-hub%20Dashboard.png)