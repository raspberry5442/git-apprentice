- 场景：欲将本地分支fix-D push到远程的origin/feature-D；
- 参考：chatGPT：[[../../Inbox/Git网络教程/How to push a local branch to a remote branch with a different name in Git]]
- 默认情况：执行git push命令，Git默认将本地分支push向远程同名分支；
- 前提假设：此场景设定下，我们假设本地分支fix-D没有通过`git checkout -t feature-D`命令提前安排自己要track哪个远程分支（git checkout -t是另外一个问题了）。
- 几个办法：
  1. 命令`git push <remote> <local-branch>:<remote-branch>`；
     - `<remote>`是远程仓库名，在此场景下就是`git push origin fix-D:feature-D`；
     - 该命令是告诉git把本地的一个分支push到远程某个库的某个分支。
  2. 命令`git push -u <remote> <local-branch>:<remote-branch>`
     - 这个命令直接假定了本地分支从未指定上游分支；
  3. 为本地分支设置upstream，以便在push的时候无需再特别指定远程分支:`git branch -u <remote/remote-branch> <local branch>`; 
     - 此场景下就是`git branch -u origin/feature-D fix-D`;
     - 如何理解这个命令呢？为什么是先远程分支，再本地分支呢？
       因为这个命令相当于：
       ```shell
       git branch --set-upstream-to=<remote>/<remote-branch> <local-branch>
       ```
     - 之后有push和pull需求的时候直接git push即可，无需再指定上游分支。
  4. 
- 提醒：即使解决了本地分支与远程分支不同名的问题，也不能通过不同的本地分支向同一个远程分支随意push，这是git的规则，学习了pull应该就明了了。此文章记录了我在用不同本地分支向同一个远程分支push时出现的问题。[[Resolving Git error--Updates were rejected because the tip of your current branch is behind]]