# What is git merge?

## Introduction

- When you want to combine the changes from one branch into another branch, you can use the `git merge` command.
- This command will take the changes from the specified branch and merge them into the current branch.

## Git Merge Example

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

- Merge the changes from the `feature` branch into the `main` branch:

```bash
git merge feature
```

- View the commit history:

```bash
git log
```
