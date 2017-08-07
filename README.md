## git_workflow

### - new branch
```
git checkout -b new_branch old_branch -> will create a branch from old_branch
...work on a branch
git add .
git commit -m "commit message"
git push -u origin new-feature
```

### - delete branch
```
git branch -d the_local_branch
```

### - last updated version of code :
```
git pull origin master
will do fetch and merge in one
```

### - switching between branches/master
```
git checkout new-feature
git checkout master
```

### - merging branch to master
```
the safe way without auto-merge :

git checkout new-feature
git pull origin master
git checkout master
git pull origin master
git merge --no-ff --no-commit new-feature
git add .
git commit -m "commit message"
git push -u origin master
```

### - going back to certain commit
```
git reset --hard <SHAsum of commit>
```

### - pulling last changes from remote repository into local repository
```
git pull origin master
```
