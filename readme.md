touch index.html

git init  (will initialize the repo)

git config --global user.name 'sudarshan1985'
git config --global user.email 'sudarshan0204@gmail.com'

git add index.html (tracks the file)

git status (gives status of the directory)

git rm --cached index.html (remove the file from staging)

git add . (adds everything in the staging to GIT)

git commit  >> opens a vi editor
I for initialize
press ESC to get out of VI

press :wq (and stats will be displayed)

easier way to commit:
git commit -m 'deleted a file'

you can create .gitignore and add the file name which should not be added to the staging rep
>> you could even add entire directory to .gitignore (example /dir1)

git branch testgit (create branch testgit)

git checkout testgit

switch back to master >  git checkout master

merge the changes from testgit branch to master
============
git merge testgit -m 'merged the testgit'

remote url:
git remote add origin https://github.com/sudarshan1985/mysampleapp.git
git remote

to push it into repository
==========================
git push -u origin master


remove remote origin:
git remote remove origin

>>after this add anything you want and push it to repository.




