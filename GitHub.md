# GitHub Commands

## Clean Commits

1. Checkout/create orphan branch (this branch won't show in git branch command):

```git
git checkout --orphan latest_branch
```

2. Add all the files to the newly created branch:

```git
git add -A
```

3. Commit the changes:

```git
git commit -am "commit message"
```

4. Delete main (default) branch (this step is permanent):

```git
git branch -D main
```

5. Rename the current branch to main:

```git
git branch -m main
```

6. Finally, all changes are completed on your local repository, and force update your remote repository:

```git
git push -f origin main
```
