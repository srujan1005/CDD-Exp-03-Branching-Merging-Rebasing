# CDD Lab Experiment 3: Branching, Merging, Rebasing and Merge Conflicts

## Objective
Implement branching, merging, rebasing and resolve merge conflicts.

## Duration
2 Hours

## Tasks
1. Create and switch between branches.
2. Make commits on different branches.
3. Merge branches using `git merge`.
4. Practice rebasing with `git rebase`.
5. Intentionally create and resolve a merge conflict.

## Commands Reference
```bash
git branch feature-branch
git checkout feature-branch
# or
git switch -c feature-branch

git merge feature-branch
git rebase main

# Resolve conflicts, then:
git add <resolved-files>
git commit
```

## Expected Outcome
Multiple branches with successful merge and resolved conflict.
