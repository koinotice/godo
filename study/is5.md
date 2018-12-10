此时工作目录中的内容和你在解决问题 #53 之前一模一样，你可以集中精力进行紧急修补。这一点值得牢记：Git 会把工作目录的内容恢复为检出某分支时它所指向的那个提交对象的快照。它会自动添加、删除和修改文件以确保目录的内容和你当时提交时完全一样。

接下来，你




git add .
git pull
vi README.md
git branch
git push origin dev -d
git branch -d dev
git merge dev
git checkout master
git checkout dev
git checkout master
git checkout dev
git checkout -d dev
git push origin is5 -d
git branch -d is5
git push origin dev
git merge is5
git branch dev
git push origin is5
git commit -m "fix fox"
git checkout -b is5
git merge master
git rebase master
git branch -r
git checkout -b dev
git log