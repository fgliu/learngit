
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

git push origin :<branch-name> #delete origin/branchname

git merge <name> 

git log --graph --pretty=oneline --abbrev-commit

git merge --no-ff

git stash

git stash apply & git stash drop

git stash pop

git stash list

git branch -D <name>

git pull

git fetch origin master
git merge

git branch --set-upstream branch-name origin/branch-name

git checkout -b branch-name origin/branch-name

git push origin branch-name

git tag v1.0 or git tag commitid

git tag -a <tagname> -m "blabla"

git tag -s <tagname> -m "blabla"

git tag

git tag -d <tagname>
git push origin <tagname>
git push origin --tags
git push origin :refs/tags/v1.0

git config --global color.ui true

git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"

git remote add <upstream name >  <remote url>
git remote update <upstream name>
git rebase upstream/{branch name}
git pull
git push origin master

cat  id_rsa.pub  >> git/.ssh/authorized_keys
git init  --bare sample.git

git .gitignore
https://github.com/github/gitignore

以镜像推送的方式上传代码到 GitCafe 服务器上
git push --mirror git@github.com:fgliu/newproject.git

