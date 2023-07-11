- 首先，要知道git仓库中文件状态是流动性的。参考[[Git文件状态生命周期]]；
- **字面解释的话，`git commit -m`用于提交暂存区的文件，`git commit -am`用于提交跟踪过的文件**；
- 其次，下面用一个实例说明
   1. 在项目文件夹中新增一个文件如'a.txt'时，该文件处于未跟踪状态(untracked)。未跟踪状态的文件是无法提交的；![image-20230311000346215](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230311000346215.png)
   2. 接下来，使用git add a.txt，使其变成已跟踪状态(tracked)；![image-20230311000419103](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230311000419103.png)
   3. 这时，如果使用git commit -m 'add a.txt'就可以顺利提交了；![image-20230311000437375](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230311000437375.png)
   4. 但是，git commit -m 和 git commit -am的区别在哪里？在于a.txt文件修改之后的处理：下面，向a.txt添加内容'a'。可以看出，文件a.txt处于已跟踪(tracked)，但未暂存状态(unstaged)；![image-20230311000603660](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230311000603660.png)
   5. 这时，如果使用git commit -m是无法提交最新版本的a.txt的，提交的还只是最开始空内容的旧版本a.txt；![image-20230311000725782](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230311000725782.png)
   6. 而如果使用git commit -am，则可以省略git add a.txt这一步，因为git commit -am可以提交跟踪过的文件，而a.txt一开始已经被跟踪过了；![image-20230311000930219](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230311000930219.png)