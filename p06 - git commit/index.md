# What is git commit?

## Introduction

- git history built from a series of commits.
- `git commit` is a command line tool that is used to save changes to the local repository.
- every commit has a unique identifier called a `hash` that is used to track changes in the repository.
- When you commit, you should include with a message that describes the changes you have made.
- commit can be changed or removed from the repository using the `git` commands.

## Git Commit Example

- Create a new file named `file.txt` in the current directory:

```bash
touch file.txt
```

- Add the `file.txt` to the staging area:

```bash
git add file.txt
```

- Commit the changes to the repository:

```bash
git commit -m "Add file.txt"
```

- Modify the `file.txt`:

```bash
echo "Hello, World!" > file.txt
```

- Add the changes to the staging area:

```bash
git add file.txt
```

- Commit the changes to the repository:

```bash
git commit -m "Update file.txt"
```

- View the commit history:

```bash
git log
```

- Exit git log:

```bash
q
```
