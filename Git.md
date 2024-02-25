# Git

Let the git know who you are

> git config --global user.name "Karthik"
> git config --global user.email "<Someone@gmail.com>"

## Initializing the Git repository

> git init -b main

Initialized empty Git repository in C:/Karthik/Subject/Git/.git/

## Status

> git status

In VSCode U -> Untracked, M -> Modified, A -> Added

> git status --short

## Adding files from working directory to Staging Area

> git add ./FileName

## Logs

> git log

TO get the log in pretty manner

> git log --pretty=oneline

## Adding files from Staging area to GitHub repo

> git commit -m "Message"

If we do this without adding to staging area it will result in Error.

> git add .
> git commit -m "Message"

Alternative for that

> git commit -a -m "Message"

## What are changes?

> git diff (In working repository)
> git diff --staged (If you added to Staging area and you want to check)

## Removing files from Git

> git rm --cached FileName

## Pushing files to Remote repo

> git remote add origin <https://github.com/....git>

To check the remote repo you are connected

> git remote -v

To push

> git push -u origin main

To remove any remote connection from your device

> git remote remove origin

## Tags

Tags are used to mark significant points from the history of the project.

> git tag

To add tag

> git tag v1.0 -m "Version 1.0"

To push these tags to remote server

> git push origin v1.0

## Downloading a repo

> git clone <https://github.com>

TO view a specific tag

> git show v1.0

## Branch

Git branches are effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes.
In Git, a branch is a new/separate version of the main repository.

To create a branch

> git branch hello-world-images
> git switch -c/--create branchName
> git checkout -b branchName

To delete a branch in the git

> git branch -d feature1
