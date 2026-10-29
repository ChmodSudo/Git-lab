#Git lab

## Description
This repository contain partical exercices on Git and Git (first day of my Devops journey) : commits, branches, fusions, conflits and  pull requests.

##Useful commands

| Commande | Rôle |
|---|---|
| `git init` | Initializes a new and empty local Git repository  |
| `git add` | Moves the files from the working directory to the staging area, ready to be commit |
| `git commit -m "msg"` | Used to commit changes |
| `git switch -c nom` | This command help to create a new branch and switch in it |
| `git merge nom` | This command help to combine changes from different branches in a single one |
| `git log --oneline --graph --all` | This command is used to visualize a project history |
| `git push -u origin nom` | This command push a designed branch to the GitHub repository |


## What i learned

- Fast-forward vs fusion commit : In the first case git moves the target branch pointer forward to match the feature branch, and in the second case , Git creates a new commit that combines the histories of both branches. 
- Git merge conflit :This occur when the same line in a file is modified by different branches. 


