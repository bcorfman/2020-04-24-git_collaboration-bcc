# Daniel Chen's Git collaboration workshop
- `git clone <URL>`: downloads the repository from the web to our computer
    - don't nest this command in another repo
    - just like `git init` do this only once per repository 
- `git add <file1> [<file2> ...]`: puts one or more files into the staging area
- `git status`: shows the state of the working directory and its relationship to the Git repo
    - displays the current branch
    - shows whether the files are part of the staging area or not, plus whether the files are untracked by Git
    - gives simple help on how to take another step, or how to revert the step that was previously taken.

## Branches
- `git branch <branch_name>`: create a new branch
- `git switch <branch_name>`: switch over to an existing branch

- `git switch -c <branch_name>: create and switch to a new branch all at once

## Pull requests (Online merge)
- `git push origin <branch_name>`: pushes branch to the remote
    - this is where you will create the PR (online)
    - you merge the PR (and also the branch) by accepting and merging the PR
- don't forget to clean up your branches
- `git fetch --prune`: cleans up the references in your `git log`
- `git branch -d <branch_name>`: delete branch on your local machine
    - it will tell you to move to another branch first

