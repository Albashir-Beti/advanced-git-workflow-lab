
# Advanced Git Workflow Lab

## Project Overview

This project is a hands-on version control practice
completed as part of the Advanced Frontend Development
Programme.

The purpose is to demonstrate practical knowledge
of Git, GitHub, and Bitbucket.

## Learning Objectives

- Creating and cloning Git repositories
- Creating and managing branches
- Staging and committing changes
- Reverting commits
- Pushing and pulling changes
- Fetching remote updates
- Merging and renaming branches
- Creating and reviewing pull requests
- Merging and reverting pull requests
- Managing multiple remote repositories

## Tools Used

- Git
- GitHub
- Bitbucket
- Visual Studio Code
- PowerShell
- HTML

## Project Files

- README.md - Project documentation
- index.html - Simple HTML homepage
- bitbucket-practice.md - Bitbucket practice file

## Git Commands Practised

### 1. Initialize a Repository

git init -b main

Creates a new local Git repository with main as
the initial branch.

### 2. Clone a Repository

git clone <repository-url>

Creates a local copy of an existing remote repository.

### 3. Check Repository Status

git status

Displays the current branch and working tree status.

### 4. Create a Branch

git switch -c feature-homepage

Creates and switches to a new feature branch.

### 5. Stage and Commit Changes

git add .
git commit -m "Add new feature"

Stages files and records a commit in Git history.

### 6. Push Changes

git push -u origin feature-homepage

Uploads the branch to GitHub and sets its upstream
tracking branch.

### 7. Fetch Changes

git fetch origin

Downloads remote updates without merging them.

### 8. Pull Changes

git pull --ff-only origin main

Downloads and integrates changes using a
fast-forward update.

### 9. Merge Branches

git switch main
git merge feature-homepage

Combines changes from a feature branch into main.
In this project, branch merging was also
demonstrated through pull requests.

### 10. Rename a Branch

git branch -m feature-new-name

Renames the current local branch.

### 11. Revert a Commit

git revert --no-edit HEAD

Creates a new commit that reverses the latest commit.

### 12. View Commit History

git log --oneline --graph --all

Displays commit history and branch relationships.

### 13. Manage Remotes

git remote -v
git branch -vv

Displays remote repositories and upstream branch
tracking information.

## GitHub Practical Activities

1. Created a GitHub repository.
2. Created the feature-homepage branch.
3. Developed a simple HTML homepage.
4. Committed and pushed the changes.
5. Created and merged Pull Request #1.
6. Reverted a commit on a practice branch.
7. Created and merged Pull Request #2.
8. Reverted Pull Request #2 using Pull Request #3.
9. Practised fetching and pulling remote changes.
10. Cloned the repository and renamed a branch.

## Bitbucket Practical Activities

1. Created a Bitbucket workspace.
2. Created a new Bitbucket repository.
3. Connected Bitbucket as a second remote.
4. Pushed the main branch to Bitbucket.
5. Created the feature-bitbucket-practice branch.
6. Created and committed a practice file.
7. Pushed the feature branch to Bitbucket.
8. Created and merged Bitbucket Pull Request #1.
9. Pulled the merged changes locally.
10. Synchronized changes back to GitHub.

## Repositories

GitHub:
https://github.com/Albashir-Beti/advanced-git-workflow-lab

Bitbucket:
https://bitbucket.org/beti-dev-lab/advanced-git-workflow-lab

## Key Learning Outcomes

Through this exercise, I gained practical experience
using Git for tracking code changes and managing
development workflows.

I also learned how to collaborate using branches and
pull requests, undo changes safely, and synchronize
repositories across GitHub and Bitbucket.

## Conclusion

This project demonstrates essential version control
operations and practical workflows used in modern
software development.
