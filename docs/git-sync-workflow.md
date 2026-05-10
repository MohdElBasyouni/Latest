# Git Sync Workflow

This repo is my fork/copy.

## Remotes

- `origin` = my GitHub repo
- `upstream` = original source repo

Check remotes:

```bash
git remote -v


Update my local repo from source
git fetch upstream
git merge upstream/main

Push source updates to my GitHub repo
git push origin main


Full update flow
git status
git fetch upstream
git merge upstream/main
git push origin main



Push my own changes to my GitHub repo
git add .
git commit -m "Describe the change"
git push origin main

