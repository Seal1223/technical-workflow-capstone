# Git / GitHub Workflow

## Standard Workflow

For normal technical work, the default workflow is local-first.

1. Pull the latest remote changes.
2. Review the relevant issue or requirement.
3. Create a branch when the work warrants isolation or review.
4. Edit and test locally in VS Code.
5. Review changes with Git.
6. Stage and commit meaningful changes.
7. Push the branch or commit to GitHub.
8. Open and review a pull request when appropriate.
9. Merge approved work into `main`.
10. Pull the updated `main` branch locally.
11. Tag or release meaningful milestones when appropriate.

## Normal Session Rhythm

Start:

`git pull`

Work:

edit -> test -> `git status` -> review changes -> `git add` -> `git commit`

Finish:

`git push`

## GitHub Web Edits

Small edits may occasionally be made directly on GitHub.

After a web-based edit, the local repository should be synchronized with:

`git pull`

before additional local work continues.

## Principle

VS Code and the local Git repository are the primary working environment.

GitHub provides the remote repository, shared history, pull-request and review workflow, issue tracking, project management, publishing, and off-device preservation of committed and pushed repository content.