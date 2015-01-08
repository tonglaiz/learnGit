http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000

git config --global user.name ""
git config --global user.email ""

git init

git add file

git commit -m ""

git status

git log

git log --pretty=oneline

git reset --hard HEAD^/HEAD^^/HEAD~100

git reflog

git checkout -- file

git rm file

ssh-keygen -t rsa -C "youremail@example.com"

git remote add origin git@github.com:tonglaiz/learnGit.git

git push -u origin master

git push origin master

git checkout -b dev

git branch dev
git checkout dev

git branch

git merge dev

git branch -d dev

git log --graph --pretty=oneline --abbrew-commit

git merge --no-ff -m "merge with no-ff" dev

git status

git stash apply

git stash drop

git stash pop

git stash list

git checkout -b feature-vulcan

git branch -d feature-vulcan

git branch -D feature-vulcan

git remote -v

git push origin master

git push origin dev

git clone git@github.com/tonglaiz/learnGit.git

git pull

git branch --set-upstream dev origin/dev

git tag v1.0

git tag -a "" -m ""

git show <tagname>

git tag -d <tagname>

git push origin <tagname>

git push origin --tags

git push origin :refs/tags/<tagname>

git config --global color.ui true

.gitignore
