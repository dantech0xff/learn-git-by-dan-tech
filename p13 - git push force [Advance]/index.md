# What is git push force?

- Git Clients are not always perfect, and sometimes they may not be able to push the changes to the remote repository.
- Git push force is a powerful command that is used to update the remote repository with the local changes forcefully.
- This cmd will override the remote repository with the local changes and history. Should use it wisely, as it may lead to data loss if used incorrectly.

## Git Push Force Example

- At any time, you can use the `git push --force` command to update the remote repository with the local changes.
- To make the git push force safer, you should use the `--force-with-lease` option.
- This option will only force the push if the remote branch is in the same state as the local branch.

```bash
git push --force
```
