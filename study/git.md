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

作者：红薯爱帅
链接：https://www.jianshu.com/p/a79cdc725954
來源：简书
简书著作权归作者所有，任何形式的转载都请联系作者获得授权并注明出处。