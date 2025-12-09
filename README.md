# Git Assignment 3

## Objective
Practice Git branch management including:
- Creating multiple branches
- Working with files across different branches
- Pushing branches to GitHub
- Deleting branches locally and remotely

## Tasks
1. Create a Git working directory with branches: Develop, F1, and f2
2. Commit main.txt in the master branch
3. Add develop.txt to develop branch, f1.txt to F1 branch, f2.txt to f2 branch
4. Push all branches to GitHub
5. Delete f2 branch locally
6. Delete f2 branch on GitHub

## Branches
- master (main branch)
- Develop
- F1
- f2

## Commands Log

| Step | Description | Command |
|------|-------------|---------|
| 1 | Create directory | `mkdir git_assignment_3` |
| 2 | Navigate to directory | `cd git_assignment_3` |
| 3 | Initialize Git | `git init` |
| 4 | Create main.txt and commit to master | `git add main.txt && git commit -m "Initial commit with main.txt to the master branch"` |
| 5 | Create branches | `git branch Develop && git branch F1 && git branch f2` |
| 6 | Verify branches | `git branch` |
| 7 | Switch to Develop and create develop.txt | `git checkout Develop && touch develop.txt` |
| 8 | Add develop.txt to Develop branch | `git add develop.txt && git commit -m "Added develop.txt to the Develop branch"` |
| 9 | Switch to F1 and create f1.txt | `git checkout F1 && touch f1.txt` |
| 10 | Add f1.txt to F1 branch | `git add f1.txt && git commit -m "Added f1.txt to the F1 branch"` |
| 11 | Switch to f2 and create f2.txt | `git checkout f2 && touch f2.txt` |
| 12 | Add f2.txt to f2 branch | `git add f2.txt && git commit -m "Added f2.txt to the f2 branch"` |
| 13 | Connect to remote repository | `git remote add origin https://github.com/gp97-dot/git_assignment_3.git` |
| 14 | Push all branches to GitHub | `git push -u origin --all` |
| 15 | Switch to master branch | `git checkout master` |
| 16 | Delete f2 branch locally | `git branch -d f2` |
| 17 | Delete f2 branch from GitHub | `git push origin --delete f2` |
