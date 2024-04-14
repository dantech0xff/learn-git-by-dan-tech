# What is git add?

## Introduction

- `git add` is a command line tool that is used to add changes in the working directory to the staging area.

- This command is used to prepare changes for the next commit.

- You can add individual files or directories to the staging area, or use the `git add .` command to add all changes in the working directory.

## Git Add Example

- Create a file named `file.txt` in the current directory:

```bash
touch file.txt
```

- Check the status of the current repository:

```bash
git status
```

```log
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        file.txt
nothing added to commit but untracked files present (use "git add" to track)
```

- Add the `file.txt` to the staging area:

```bash
git add file.txt
```

```log
On branch main
Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
            new file:   file.txt
```

- Check the status of the current repository:

```bash
git status
```

- Remove the `file.txt` from the staging area:

```bash
git rm --cached file.txt
```
