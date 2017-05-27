## git_workflow

### for new branch
git checkout -b new-feature
...work on a branch
git commit -am "commit message"
git push -u origin new-feature

### for last updated version of code : git pull origin master
will do fetch and merge in one

### for switching between branches/master
git checkout new-feature
git checkout master

### for merging branch to master
git checkout master
git pull origin master
git merge new-feature
git push origin master
