
yum install git 

git config --global user.name 'fgliu'
git config --global user.email 'fgliu@live.cn'

git init

git add 'filename.txt'

git commit -m 'this is remark'

git status

git diff 'filename.txt'

git add 'filename.txt'

git log

git log --pretty=oneline

git reset --hard HEAD^

git reset --hard HEAD~3

git reset --hard 23c1dbf

git reflog

git checkout -- file

git reset HEAD file

git checkout -- file

git rm file

sh-keygen -t rsa -C "fgliu@live.cn"

git remote add origin https://github.com/fgliu/learngit.git
git remote add origin git@github.com:fgliu/learngit.git
git push -u origin master

git clone git@github.com:fgliu/learngit.git

git checkout -b dev = git branch dev & git checkout dev

git branch

git branch -d <name>

git merge <name> 

git log --graph --pretty=oneline --abbrev-commit


