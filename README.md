#Git lab

## Description
This repository contains pratical exercises on Git and GitHub (first day of my DevOps journey) : commits, branches, merge, conflicts and pull requests.

## Useful commands

| Commande| Role |
|---|---|
| `git init` | Initializes a new and empty local Git repository  |
| `git add` | Moves the files from the working directory to the staging area, ready to be committed |
| `git commit -m "msg"` | Saves a snapshot of the staged changes in the local repository |
| `git switch -c name` | This command creates a new branch and switches to it |
| `git merge name` | Combines changes from different branches into a single one |
| `git log --oneline --graph --all` | Displays the project history as a graph of all branches |
| `git push -u origin nom` | This command push a designated branch to the GitHub repository |


## What I learned

- Fast-forward vs merge commit : In the first case, Git moves the target branch pointer forward to match the feature branch, and in the second case, Git creates a new commit that combines the histories of both branches. 
- Git merge conflict: This occurs when the same line in a file is modified differently by two  branches. 


