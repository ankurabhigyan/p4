# p4
mkdir p3
vi p3.txt
git init
git add p3.txt
git commit -m " "
git checkout -b sourcebranch
vi p3.txt
git stash save " "

git checkout master
vi p3.txt 
git add p3.txt
git commit -m "file update"

git checkout -b targetbranch
git stash apply
git add p3.txt
git commit -m "file update success'


git checkout master
git merge target branch
vi p3.txt
git branch --list
git stash list
git stash drop stash@{0}










'
