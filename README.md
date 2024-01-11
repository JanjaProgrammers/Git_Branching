# Git_Branching

Learning Git Branching

## Define terms

- Branch

1.  Isolation
2.  Parallel Development

## Git Commands

1. Create a branch

```bash
git branch "branchname"
```

2.  Switching between branches

    ```bash
      git switch branchname
    ```

    ```bash
      git checkout branchname
    ```

    - Directly switching to a new branch

    ```bash
      git checkout -b branchname
    ```

3.  Merging

`    git merge sourcebranch`

4. Resolve Conflicts

`    git mergetool`

5. List all branches

````bash
git branch`

6. A list of extra commands

```bash
git branch -v`

```bash
git status`

- List merged commits
  ```bash
git branch --merged`
- List unmerged commits
  ```bash
git branch --no-merged`
````
