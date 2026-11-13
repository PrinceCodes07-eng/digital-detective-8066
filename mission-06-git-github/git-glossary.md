# Mission 6 - Git Command Glossary

| Git Operation | Command | Explanation |
|---|---|---|
| Initialise repository | `git init` | Creates a new Git repository. |
| Check status | `git status` | Shows modified, staged, and untracked files. |
| Stage changes | `git add` | Selects changes for the next commit. |
| Commit changes | `git commit` | Saves staged changes in Git history. |
| View history | `git log` | Displays previous commits. |
| List branches | `git branch` | Shows available local branches. |
| Create a branch | `git switch -c branch-name` | Creates and switches to a new branch. |
| Switch branches | `git switch branch-name` | Moves to another branch. |
| Publish changes | `git push` | Uploads commits to a remote repository. |
| Retrieve remote changes | `git pull` | Downloads and integrates remote changes. |

## Difference Between Staging and Committing

Staging selects the changes that should be included in the next commit.
Committing records those staged changes in the local Git history.

## Branches

A branch is a separate line of development. It allows developers to work on changes without directly modifying the main branch.

## Pull Requests

A Pull Request is a request to review and merge changes from one branch into another. It helps team members discuss and review code before merging.

## Why Branches and Pull Requests Are Useful

They allow multiple people to work on the same project safely, review changes, find problems, and collaborate without directly changing the main branch..