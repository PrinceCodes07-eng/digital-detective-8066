# Git Command Glossary

| Operation | Command | Meaning |
|---|---|---|
| Create repository | `git init` | Start tracking a project with Git |
| Check status | `git status` | Show changed, staged and untracked files |
| Stage one file | `git add README.md` | Select a file for the next commit |
| Stage all changes | `git add .` | Select all changes under the current directory |
| Commit | `git commit -m "message"` | Record staged changes |
| View history | `git log --oneline` | Show commit history in compact form |
| List branches | `git branch` | List local branches |
| Create and switch | `git switch -c update-about` | Create a branch and switch to it |
| Switch branch | `git switch main` | Switch to an existing branch |
| View remotes | `git remote -v` | Show remote repository URLs |
| Push branch | `git push -u origin update-about` | Publish branch and set upstream |
| Pull changes | `git pull` | Fetch and integrate remote changes |

## Staging and Committing

Staging chooses which changes will be included in the next commit. Committing records those staged changes in the local Git history.

## Branches

A branch is an independent line of development. It lets a developer work on a change without immediately changing the main branch.

## Pull Requests

A pull request proposes that changes from one branch be reviewed and merged into another branch. Reviewers can inspect the changes and discuss them before merging.

## Why This Workflow Helps

Commits provide a history, branches separate pieces of work, and pull requests provide a review step before changes are integrated.