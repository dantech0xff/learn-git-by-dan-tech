# What is git init?

## Introduction

- `git init` is a command line tool that is used to create a new Git repository in the current directory.
- This command will create a new directory named `.git` that contains all the necessary files for the repository.
- After running `git init`, you can start adding files to the repository and tracking changes with Git.

## Git Init Example

- To create a new Git repository, navigate to the directory where you want to create the repository and run the following command:

```bash
git init
```

```log
Initialized empty Git repository in /path/to/your/directory/.git/

```

- Check status of the current repository:

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
