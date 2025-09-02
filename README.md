# DevOps Task 1: Version Control
This repository is for the CODTECH DevOps Internship.
This change is made on the feature-branch.

## Merge Conflict Resolution

1.  A conflict was created by adding a new line of text to `README.md` on the `master` branch and a different line of text in the same spot on the `feature-branch`.
2.  The `feature-branch` was merged into `master` using `git merge feature-branch`.
3.  Git reported a `CONFLICT (content)` in `README.md`.
4.  The file was opened, and the conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`) were manually removed. The desired text from both branches was kept.
5.  The resolved file was staged with `git add README.md` and committed with `git commit` to finalize the merge.
