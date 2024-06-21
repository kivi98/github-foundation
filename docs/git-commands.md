# Common git commands

---
## Git configuration
- Set your name and email
```bash
git config --global user.name "Your Name"
git config --global user.email "
```

- Set your default editor
```bash
git config --global core.editor "code --wait"
```

- Set your default branch name
```bash
git config --global init.defaultBranch main
```
## Creating a new repository
- Create a new repository
```bash
git init
```
## Cloning a repository
- Clone a repository
```bash
git clone <repository-url>
```
## Checking the status of files
- Check the status of files
```bash
git status
```
- Check the status of files in short format
```bash
git status -s
```
## Staging files
- Stage all files
```bash
git add .
```
- Stage a specific file
```bash
git add <file-name>
```
## Committing files
- Commit files with a message
```bash
git commit -m "Commit message"
```
- Commit files with a message and add all changes
```bash
git commit
```
- Change the last commit message
```bash
git commit --amend -m "New commit message"
```
## Viewing commit history
- View commit history
```bash
git log
```
- View commit history on one line
```bash
git log --oneline
```
- View commit history with a graph
```bash
git log --oneline --graph --all
```
## Branching and merging
- Create a new branch
```bash
git branch <branch-name>
```
- Create a new branch and switch to it
```bash
git checkout -b <branch-name>
```
- Switch to a branch
```bash
git checkout <branch-name>
```
- Merge a branch into the current branch
```bash
git merge <branch-name>
```
- Delete a merged branch
```bash
git branch -d <branch-name>
```
- Delete an unmerged branch (force delete)
```bash
git branch -D <branch-name>
```
## Stashing changes
- Stash changes
```bash
git stash
```
- Apply stashed changes
```bash
git stash apply
```
- Apply and remove stashed changes
```bash
git stash pop
```
- List stashed changes
```bash
git stash list
```
- Remove stashed changes
```bash
git stash drop
```
- Clear all stashed changes
```bash
git stash clear
```
## Working with remotes
- Add a remote repository
```bash
git remote add <remote-name> <repository-url>
```
- List remote repositories
```bash
git remote -v
```
- Fetch changes from a remote repository
```bash
git fetch <remote-name>
```
- Pull changes from a remote repository
```bash
git pull <remote-name> <branch-name>
```
- Push changes to a remote repository
```bash
git push <remote-name> <branch-name>
```
- Push changes to a remote repository (set upstream)
```bash
git push -u <remote-name> <branch-name>
```
- Remove a remote repository
```bash
git remote remove <remote-name>
```
## Resetting and reverting
- Reset to a previous commit
```bash
git reset <commit-hash>
```
- Reset to a previous commit and keep changes
```bash
git reset --soft <commit-hash>
```
- Reset to a previous commit and unstage changes
```bash
git reset --mixed <commit-hash>
```
- Reset to a previous commit and discard changes
```bash
git reset --hard <commit-hash>
```
- Revert a commit
```bash
git revert <commit-hash>
```
## Tagging
- Create a tag
```bash
git tag <tag-name>
```
- Create an annotated tag
```bash
git tag -a <tag-name> -m "Tag message"
```
- Push tags to a remote repository
```bash
git push --tags
```
- Checkout a tag
```bash
git checkout <tag-name>
```
## Submodules
> Add a submodule to your repository. When you clone the repository, the submodule will also be cloned. The submodules are useful when you want to include another repository within your repository.
- Add a submodule
```bash
git submodule add <repository-url>
```
- Initialize and update submodules
```bash
git submodule init
git submodule update
```
- Clone a repository with submodules
```bash
git clone --recurse-submodules <repository-url>
```
## Ignoring files
- Create a `.gitignore` file
```bash
touch .gitignore
```
- Add files to `.gitignore`
```bash
echo "<file-name>" >> .gitignore
```
## Aliases
> Create aliases for common git commands to save time and typing.
- Create a git alias
```bash
git config --global alias.<alias-name> "<git-command>"
```
- Use a git alias
```bash
git <alias-name>
```
## Help
- Get help for a specific command
```bash
git help <command>
```
- Get help for all available commands
```bash
git help -a
```


[]: # (END) git-commands.md