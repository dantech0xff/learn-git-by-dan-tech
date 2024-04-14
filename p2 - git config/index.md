# What is git config?

## Introduction

- `git config` is a command line tool that is used to set or get configuration variables that control all aspects of how Git looks and operates.

## Git Config Global

Every commits in Git will use an identity that is set in the global configuration. This is useful when you are working on a project with multiple collaborators, so that each commit can be identified with the correct author.

You can also set your own identity in a specific repository, which will override the global configuration. But this is not recommended, as it will make it difficult to identify the author of each commit.

- `git config --global user.name "John Doe"`: Set a name that is identifiable for credit when review version history.
- `git config --global user.email "your-git-email@email.domain"`: Set an email address that will be associated with each history marker.
- More global configurations can be found [here](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration).
