# Git Workflow Commands Summary

## Initial Setup
git init
git clone <repo-url>

## Branching
git checkout -b feature/user-profile

## Commits
git add .
git commit -m "message"

## Rebase
git rebase main
git rebase -i HEAD~3

## Conflict Resolution
(edit file)
git add .
git rebase --continue

## Push
git push origin feature/user-profile
git push --force-with-lease
