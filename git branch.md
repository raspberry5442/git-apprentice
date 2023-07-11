- `git branch -f <branch> <start-point>`
  该命令用来强制改变分支的指向，即将指定分支指向指定的提交，忽略分支历史。这在需要撤销之前的一些提交或重置分支的指向时非常有用。但是，这个命令应该谨慎使用，因为它会修改分支的历史，并可能导致数据丢失或分支不一致的问题。
  `<start-point>`是分支的起始点，就是要将该分支指向的提交（commit）的SHA-1值、分支名称、相对引用等。
  e.g. 如果我们要将名为“feature”的分支指向最新的提交（HEAD），可以使用命令：`git branch -f feature HEAD`;如果要将名为“feature”的分支指向前1个提交，则利用相对引用：`git branch -f feature HEAD^`;如果要将名为“feature”的分支指向前3个提交，则利用相对引用：`git branch -f feature HEAD~3`。
  演示：
  [[../../Excalidraw/git branch -f.excalidraw]]
