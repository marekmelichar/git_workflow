## git_workflow

### - new branch
git checkout -b new-feature
...work on a branch
git commit -am "commit message"
git push -u origin new-feature

### - last updated version of code : git pull origin master
will do fetch and merge in one

### - switching between branches/master
git checkout new-feature
git checkout master

### - merging branch to master
`
git checkout master
git pull origin master
git merge new-feature
git push origin master

or

git checkout new-feature
git pull
git checkout master
git pull
git merge --no-ff --no-commit new-feature
`
