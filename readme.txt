1.installed git scm

2.right-click desktop icon, changed path variable to desired location of project source

3.git config --global user.name "name"
git config --global user.email "name@email.com"

4.git init "foldername" 
you want to initialize or begin git-ing.

5.git add filename

or

git add . (adds all files in current directory)

6.git status
git log

7.git rm --cached filename (or . for total removal)

8.git commit -m "message for commit"

9.add files to staging area after modifications to be able to commit them (git add .)

10.git diff 
to see the changes added in the files in the repo

11.git diff --cached

12.Shift + zz

13. git log --oneline

14. git commit -a -m "msg"

25. git status -s


--------------------------
--------------------------

creating SSH key

git init
git add .
git commit -m
git status git log
git remote add origin "get it from github.com under the repo of the project you want to upload it and select the ssh and copy paste it here"
git push origin master (master is the name of branch and pushing is uploading)