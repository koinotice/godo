# 可以尝试push --force
$ git add .
$ git commit --amend --no-edit
$ git push --force



git rebase -i head~{num}
前面提到的git rebase -i commitHash指令可以合并提交历史，其实还可以换成一种快捷方式，如当需要合并最近两个提交时，执行：

git rebase -i head～2


远程
2.4. 注意事项

rebase操作只能在本地仓库完成，如果要合并远程仓库的commit，可能会遇到问题，请慎重操作。

# 可以尝试push --force
$ git add .
$ git commit --amend --no-edit
$ git push --force


如果这个过程中有操作错误，可以使用git rebase --abort来撤销修改，回到没有开始操作合并之前的状态。

$ git rebase --abort

 

新建dev    
 git checkout -b dev

 git checkout -b is5

 git checkout dev

 合并分支
 git merge is5

删除分支

git branch -d is5

删除远端分支

git push origin is5 -d

   