# Mission 6 – Git and GitHub

## Objective
Understand version control, practise Git commands, create a branch, and open a Pull Request.

## Task 6.1 – Basic Git Workflow

Practised these operations:

- `git status` – Checked repository status.
- `git add README.md` – Staged the selected README file.
- `git commit` – Saved staged changes in Git history.
- `git log --oneline -5` – Viewed recent commits.

### Difference Between Staging and Committing

Staging selects changes for the next commit. Committing saves those staged changes in the local Git history.

## Task 6.2 – Branch Creation

Created a branch named `update-about`.

Updated the root README.md with a section titled "My Learning", describing Linux, Git, Python, and number-system conversions.

Committed the changes with the message:

`Add my learning update to README`

Published the branch to GitHub.

## Task 6.3 – Pull Request

Created Pull Request #1:

- Title: Add my learning update to README
- Source branch: `update-about`
- Target branch: `main`
- Status: Open (not merged)
- Merge conflicts: None

The Pull Request allows changes to be reviewed before merging them into the main branch.

## Task 6.4 – Git Command Glossary

See `git-glossary.md` for explanations of the required Git operations.

## Why Branches and Pull Requests Matter

Branches allow developers to work independently without directly changing the main branch. Pull Requests allow team members to review, discuss, and check changes before merging them.

## Difficulty Faced

I learned that Git commands such as `git log` and `git branch` may open a pager. Pressing `q` exits it.

I also learned how to publish a branch and create a Pull Request through GitHub.

## Status

Documentation prepared. Pull Request #1 is open and has not been merged.
