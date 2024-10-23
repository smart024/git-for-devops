
# Git Commands Reference

## 1. Initialize a Git Repository
```bash
git init
This command initializes a new Git repository in the current directory.
2. Check Git Status
bash

git status
Shows the status of the working directory and staging area.
3. Add Files to Staging Area
bash

git add <file>
git add .
Adds specific files or all files (.) to the staging area.
4. Commit Changes
bash

git commit -m "Commit message"
Commits staged changes with a descriptive message.
5. View Commit History
bash

git log
git log --oneline
git log -n 1
Displays commit history. --oneline gives a brief format, -n 1 shows the last commit.
6. Rename or Move a File
bash

git mv <old_filename> <new_filename>
Renames or moves a file in the repository.
7. Remove Files from Staging Area or Repository
bash

git rm --cached <file>
git rm <file>
--cached removes the file from the staging area without deleting it from the working directory. Without --cached, the file is deleted from the directory.
8. Create a New Branch
bash

git branch <branch_name>
git checkout -b <branch_name>
Creates a new branch, or checkout -b creates and switches to the new branch.
9. Switch Between Branches
bash

git checkout <branch_name>
Switches to the specified branch.
10. List Branches
bash

git branch
Lists all branches in the repository.
11. Merge Branches
bash

git merge <branch_name>
Merges the specified branch into the current branch.
12. View Branch History
bash

git log --oneline --graph --all
Shows a graphical representation of the commit history across all branches.
13. Stash Uncommitted Changes
bash

git stash
Temporarily saves uncommitted changes for later use.
14. Apply Stashed Changes
bash

git stash apply
Restores the most recently stashed changes.
15. Check Remote Repository
bash

git remote -v
Lists the URLs of the remote repositories.
16. Push to a Remote Repository
bash

git push <remote> <branch>
Pushes the local branch to the specified remote repository.
17. Pull Changes from a Remote Repository
bash

git pull <remote> <branch>
Fetches and merges changes from the specified remote branch into the current branch.
18. Clone a Remote Repository
bash

git clone <repository_url>
Clones a remote repository into your local machine.
19. Discard Unstaged Changes
bash

git checkout -- <file>
Reverts the changes to a file, discarding any unstaged modifications.
20. Reset Staged Files
bash

git reset <file>
Removes the file from the staging area but keeps the changes in the working directory.
21. Delete a Branch
bash

git branch -d <branch_name>
git branch -D <branch_name>
Deletes a branch (-D forces the deletion of unmerged branches).
