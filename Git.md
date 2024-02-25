# Git

## Initializing the Git repository

> git init -b main

Initialized empty Git repository in C:/Karthik/Subject/Git/.git/

## Status

> git status

In VSCode U -> Untracked, M -> Modified, A -> Added

## Adding files from working directory to Staging Area

> git add ./FileName

## Logs

> git log

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
