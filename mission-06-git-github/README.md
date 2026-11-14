
# Mission 6 – Git and GitHub

## Objective
Understand version control, practise Git commands, create a branch, open a Pull Request, and explain the collaboration workflow.

## Task 6.1 – Basic Git Workflow

Practised these operations:

- `git status` – Checked the current repository status.
- `git add README.md` – Staged the selected README file for the next commit.
- `git commit -m "message"` – Saved staged changes in Git history.
- `git log --oneline -5` – Viewed the five most recent commits.

### Difference Between Staging and Committing

Staging selects the changes that should be included in the next commit. Committing records those staged changes in the local Git history.

## Task 6.2 – Branch Creation

Created a branch named `update-about`.

Updated the root `README.md` with a section titled "My Learning", describing Linux, Git, Python, and number-system conversions.

Checked the repository status, staged and committed the README changes, and published the branch to GitHub.

Commit message:

`Add my learning update to README`

Verified that the `update-about` branch was published successfully.

## Task 6.3 – Pull Request

Created Pull Request #1:

- Title: Add my learning update to README
- Source branch: `update-about`
- Target branch: `main`
- Status: Open (not merged)
- Merge conflicts: None

The Pull Request allows changes to be reviewed and discussed before merging them into the main branch.

## Task 6.4 – Git Command Glossary

Created `git-glossary.md` containing explanations of the required Git operations, including repository initialisation, status, staging, committing, history, branches, switching branches, pushing, and pulling.

## Why Branches and Pull Requests Matter

Branches allow developers to work independently without directly changing the main branch. Pull Requests allow team members to review, discuss, and check changes before merging them.

This makes collaboration safer and helps prevent mistakes in the main project.

## Difficulty Faced

I learned that Git commands such as `git log` and `git branch` may open a pager. Pressing `q` exits it.

I also learned how to publish a branch and create a Pull Request through GitHub.

## Status

Mission documentation completed. Pull Request #1 is open and has not been merged.
