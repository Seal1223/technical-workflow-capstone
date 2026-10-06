# Recovery Log

## Git Recovery Practice

Phase 00 includes exercises for restoring unwanted changes, unstaging files, resolving merge conflicts, and recovering a repository from a fresh clone.

## Merge Conflict Exercise

Two branches changed the same line in `docs/learning-log.md`.

Git could not automatically determine which version should be retained, so it stopped the merge and marked the file as conflicted.

I reviewed the `HEAD` and feature-branch versions, manually selected the final content, removed the conflict markers, staged the resolved file, and completed the merge commit.

Verification:
- `git status` showed a clean working tree.
- The resolved content was preserved on `main`.
- The completed merge was pushed to GitHub.