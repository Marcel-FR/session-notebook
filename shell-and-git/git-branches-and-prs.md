### Git `branch` commands

| command                      | functionality                        |
| ---------------------------- | ------------------------------------ |
| `git switch -c <branchname>` | creates a new branch and switch to it |
| `git switch <branchname>`    | switches branches                      |
| `git branch`                 | lists your branches                   |
| `git branch -a`              | lists all branches (local and remote) |
| `git branch -d <branchname>` | deletes a branch                      |
| `git checkout -b <branchname>`| creates and switches to branch       |
| `git checkout <branchname>`  | switches to branch                   |
| `git push --set -upstream origin <branchname>` | needed to push a new branch for the first time |
| `git push`                   | pushes staged files up to GitHub     |
| `git pull`                   | pulls GitHub                         |