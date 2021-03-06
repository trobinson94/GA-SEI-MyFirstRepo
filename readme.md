# My Git Cheatsheet

## Creating a git Repo

In the folder you want to create a repo, do the following command in terminal:

```
git init
```

**Always check that you are not already in a repo by using git status**

---
 ## Adding files to staging

 Staging are files that are being tracked to be comitted

 use git staus to see which files are untracked (red) or in staging (green)

 ```
 git status
 ```

 Three ways to add files to staging:
 - Add oone file at a time `git add <filename>`
 -Add all files in the repo `git add -A`
 -Add all files in my current folder with `git add`

 ---

 ## Comitting files to our repo

 ```
 git commit -m "descriptive messeage"

```

**If you forget the -m, you'll end up im vim, th exit, type ":wq"**

---

## Looking at our commit history

```
git log
```

```
git log --oneline
```

## Working with remotes (enterprise, github, bitbucket, etc)

- To add a remote `git remote add <name> <url>`
- To see list of remotes `git remote -v`
- To push code `git push <remoteName> <brandName>`
- To see your current branch `git branch` 