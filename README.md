# Git Cheat Sheet

## 1. Workflow (Daily Use)

* `git status` - Check which files have been modified.
* `git add .` - Stage all changes for commit.
* `git commit -m "message"` - Save changes to the local history.

## 2. Syncing with Remote (GitHub)

* `git push` - Upload you local commits to the cloud.
* `git pull` - Fetch and download changes from the cloud.

## 3. Branching & Experimenting

* `git branch` - List all available branches.
* `git checkout -b branch-name` - Create and swith to a new branch.
* `git checkout main` - Switch back to the main branch
* `git merge branch-name` - Combine changes from another branch into your current one.

## 4. Utilities & Troubleshooting

* `git log --oneline` - Show a condensed list of previous commits.
* `git diff` - Show specific code changes not yet staged.
* `git reset --hard` - Discard all local changes and revert to the last commit.
