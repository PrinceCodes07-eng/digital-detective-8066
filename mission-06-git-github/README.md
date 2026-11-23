# Mission 6 — Git and GitHub

## Objective

Understand version control and practise saving changes, working with branches, publishing commits and opening a pull request.

## 1. Basic Git Workflow

| Command | Purpose |
|---|---|
| `git status` | Check the working tree |
| `git add README.md` | Stage a selected file |
| `git commit -m "message"` | Save staged changes as a commit |
| `git log --oneline` | View commit history |
| `git branch` | List local branches |
| `git switch -c update-about` | Create and switch to a branch |
| `git switch main` | Switch to the main branch |
| `git push -u origin update-about` | Publish a branch |
| `git pull` | Fetch and integrate remote changes |

## 2. Staging vs Committing

Staging selects which changes should be included in the next commit. Committing records the staged changes in the repository's history. A commit is a saved snapshot, not the same thing as pushing to GitHub.

## 3. Branches

A branch is a separate line of work. The assignment branch is named `update-about`. It allows changes to be prepared separately from `main`.

## 4. Pull Request

A pull request proposes changes from one branch to another so they can be reviewed before merging.

- Pull Request: [#1 — Add my learning update to README](https://github.com/PrinceCodes07-eng/digital-detective-8066/pull/1)
- Source branch: `update-about`
- Target branch: `main`
- Status when this README was last checked: open, not merged

## 5. Git Command Glossary

See [git-glossary.md](git-glossary.md) for short explanations of the main Git commands and workflow terms.

## What I Learned

Git records the history of project changes. Branches keep separate work organised, and pull requests allow changes to be reviewed before they are merged into the main branch.

## Conclusion

This mission gave me practice with the basic Git workflow and showed me how GitHub supports sharing and reviewing project changes.