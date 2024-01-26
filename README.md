# Git WOW

Useful git commands to improve productivity.

## How to use

- Clone this repository in a directory that your user has access
- In your `.bashrc` or `.zshrc` add the following line:
  ```bash
  export PATH=$PATH:/full-path/to/git-wow
  ```
- Reload your terminal

## Branch comands

Very useful commands when you have a large list of local branches and you want to easily switch or delete them.

```bash
# List and switch to a branch
git wow switch-branch

# List and switch to a branch filtering by name
git wow switch-branch <partial-branch-name>

# List and deletes a branch
git wow delete-branch

# List and delete branch filtering by name
git wow delete-branch <partial-branch-name>
```
