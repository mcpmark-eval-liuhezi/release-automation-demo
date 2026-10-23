# release-automation-demo — a sandbox for practicing the branch, review, and merge workflow

This repository is a live, inspectable example for onboarding: a change starts on a feature
branch, goes through a reviewed pull request, and lands as a single squashed merge commit.

## How to inspect this demo

- **Branches:** `docs/contributing-guide` was cut from `main` and carries the feature work.
- **Pull request:** open the single PR in this repo to see the diff, the line-level review
  comment pinned to a specific line of `CONTRIBUTING.md`, and the review submitted against
  the branch's head commit.
- **Direct commits:** `Add sandbox note to README` was pushed straight to `main` while the PR
  was open, and the PR branch was then updated to include it.
- **Issue:** the tracking issue links to the PR, and a comment on the issue points back to it.
- **Merge:** the PR was squash-merged, so `main` gained exactly one new commit.

## Why not screenshots?

Every artifact here is real GitHub state you can click into, diff, and verify — commits,
reviews, comments, and the merge are all inspectable long after screenshots go stale.

Sandbox note: everything in this repository is disposable demo content — expect it to change without warning.
