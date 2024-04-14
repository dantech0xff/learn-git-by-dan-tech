# What is git push?

## Introduction

- When you want to push your changes to a remote repository, you can use the `git push` command.
- This command will upload the changes from your local repository to the remote repository.
- `git push` is used to share your work with others and collaborate on projects.

## Git Push Example 1

- Create a repository on <https://github.com> and copy the Git URL of the repository.

- Clone the repository to your local machine:

```bash
git clone <repository-url>
```

- Make changes to the files in the repository.
- Add the changes to the staging area:

```bash
git add .
```

- Commit the changes to the local repository:

```bash
git commit -m "Commit message"
```

- Push the changes from the local repository to the remote repository:

```bash
git push
```

- View the result

```log
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 10 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 683 bytes | 683.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/dantech0xff/learn-git-by-dan-tech.git
   8953361..d20f4bf  main -> main
```
