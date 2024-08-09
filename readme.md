# JS project N1
## Basic Git commands are:
**fetch:** *This command downloads commits, files, and refs from a remote repository to your local repository. Fetching is what you do when you want to see what everybody else has been working on. It leaves your local branch untouched, thus it's safe to fetch at any time without affecting your changes in your local branch.* 

**pull:** *This command is basically a combination of 'git fetch' followed by 'git merge'. It retrieves the changes from the remote repository and then automatically attempts to merge them into the local branch. It's a quick way of catching up your local branch with a remote.*

**git commit --amend:** *If you realized that you have forgotten to stage certain changes when doing your latest commit, you can stage those changes with git add and then use git commit --amend. This will update and replace the most recent commit with a new commit which includes those staged changes without creating an additional commit.*

So what's the difference?:

```
git fetch is the command that says "bring my local copy of the remote repository up to date." But it doesn’t change any of your local branches.
git pull, however, does that AND it also merges those changes into your current branch.
```
