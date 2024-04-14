# What is git squash?

## Introduction

- `git squash` is a command line tool that is used to combine multiple commits into a single commit.
- This command is used to clean up the commit history and make it easier to understand.
- Squashing commits is useful when you have made several small commits that are related to the same change and you want to combine them into a single commit.

## Git Squash Example

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

- Modify the `file.txt`:

```bash
echo "Hello, Universe!" > file.txt
```

- Add the changes to the staging area:

```bash
git add file.txt
```

- Commit the changes to the `feature` branch:

```bash
git commit -m "Update file.txt"
```

- View the commit history:

```bash
git log
```

- Squash the last two commits into a single commit:
  Squash commit requires multiple steps to be performed. I refer you to use the Git Client to perform this operation.

  - Using Git Desktop:
    - Open the Git Desktop application.
    - Select the repository you want to squash commits.
    - Click on the "Branch" menu.
    - Select the "Rebase" option.
    - Select the commits you want to squash.
    - Click on the "Squash" button.
    - Enter a commit message for the squashed commit.
    - Click on the "Squash and commit" button.
  - Using SmartGit:
    - Open the SmartGit application.
    - Select the repository you want to squash commits.
    - Click on the "Log" menu.
    - Select the commits you want to squash.
    - Right-click on the selected commits.
    - Click on the "Squash Commits" option.
    - Enter a commit message for the squashed commit.
    - Click on the "Squash" button.
    - Click on the "Commit" button.
