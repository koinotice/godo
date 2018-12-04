# 可以尝试push --force
$ git add .
$ git commit --amend --no-edit
$ git push --force



git rebase -i head~{num}
前面提到的git rebase -i commitHash指令可以合并提交历史，其实还可以换成一种快捷方式，如当需要合并最近两个提交时，执行：

git rebase -i head～2