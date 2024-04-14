# What is git rebase?

## Introduction

- `main` branch

```bash
  A -> B -> C -> D
```

- `feature` branch that is based on `main` branch from commit B

```bash
  A -> B -> F -> G
```

- When the changes in the `feature` branch are based on an outdated version of the main branch, you can use the `git rebase` command to reapply the changes on top of the latest version of the main branch.

- This cmd will rewrite the commit history of the `feature` branch, making it look like the changes were made on top of the latest version of the main branch.

- In git flow, we using it to make the commit tree more linear and easier to understand.

- A software engineer should understand it and know how to use it wisely. It good for team communication and code review.

## Git Rebase Example

- Create a new branch named `feature` and switch to it:

```bash
git checkout -b feature
```

- Modify the `file.txt`:

```bash
echo "Hello, World!" > file.txt
```

- Add the changes to the staging area:

```bash
git add file.txt
```

- Commit the changes to the `feature` branch:

```bash
git commit -m "Add file.txt"
```

- Switch back to the `main` branch:

```bash
git checkout main
```

- Modify the `file.txt`:

```bash
echo "Hello, Universe!" > file.txt
```

- Add the changes to the staging area:

```bash
git add file.txt
```

- Commit the changes to the `main` branch:

```bash
git commit -m "Update file.txt"
```

- Switch back to the `feature` branch:

```bash
git checkout feature
```

- Rebase the `feature` branch on top of the `main` branch:

```bash
git rebase main
```

- View the commit history:

```bash
git log
```

- Exit git log:

```bash
q
```
