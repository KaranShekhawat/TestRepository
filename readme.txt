hello git!!
Git commands
git init for initialization of git
git config --global user.mail "karanpratapsingh90@gmail.com 
git clone repository to get repository from remote
git add filename for staging
git add * to add files for staging
git commit -m "wirte message while commiting"
git commit -a to commit all files added since taken repository
git push origin master >>to send changes to all your master branch
git remote add origin <server> If you haven't connected your local repository to a remote server, add the server to be able to push to it:
git remote -v to show all configured remote repositories.
git checkout -b branchname create a new branch and switch to it.
git checkout branchname switch from current to other branch.
git branch list all branches.
git branch -d branchname
git branch origin server : Push the branch to remote server.
git push --origin :Push all branches to remote server.
git pull fetch and merge from remote branch to working copy
git merge to merge a branch to your active branch
git diff view all the differences
git diff --base <filename>
git diff <sourcebranch> <targetbranch>
git tag significant change as release
git push --tags origin  push all tags to remote repisitory
git checkout --filename
git fetch origin drop all your changes and fetch the latest
git resret --hard origin master
git grep "foo" search the working for foo.
git status provides the status of working copy
git rm -r <filename> remove the filename 
git stash stash changes in working directory
git stash clear remove all stashed enteries.

first all create a branch out of master branch 
1 git branch branchname
2 git checkout branchname in it. 
3 git merge benachname
git log --summary view changes detailed.
git merge to merge a different branch to your active branch
git push origin master to commit data to git repository at git hub
git remote -v to check permisions availiable on remote repository
git push --set-upstream origin newbranch
