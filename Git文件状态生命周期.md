即File Status Lifecycle
![image-20230310234106195](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230310234106195.png)
由上图可知，git仓库中的文件状态有：
- untracked/tracked
- unmodified/modified
- staged/unstaged
已跟踪（tracked）的文件指本来就被纳入版本控制管理的文件，因而在历史版本快照中都有该类文件的记录，工作一段时间后，它们的状态可能是未更新(unmodified)，已修改(modified)或者已放入暂存区(staged)

因此，git仓库中文件状态并不是线性的，而是流动的，随着对文件的修改和我们对文件执行的操作，文件的状态是在不断变化的。