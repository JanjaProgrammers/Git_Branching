# Git_Branching

Learning Git Branching

## Define terms

- Branch
- 1. Isolation
- 2. Parallel Development

## Git Commands

1. Create a branch

`git branch "branchname"`

2. Switching between branches

   - `git switch branchname`
   - `git checkout branchname`

   - Directly switching to a new branch

     `git checkout -b branchname`

3. Merging

`    git merge sourcebranch`

4. Resolve Conflicts

`    git mergetool`

5. List all branches

`git branch`

6. A list of extra commands

`git branch -v`

`git status`

- List merged commits
  `git branch --merged`
- List unmerged commits
  `git branch --no-merged`
