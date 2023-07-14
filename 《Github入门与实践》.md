---
author: 大塚弘记
category: 专业
tags: 
- Git
- GitHub
source: zotero
start_date: 2023/02/27
finish_date: 
status: 未完成
---

#阅读 
[GitHub 官方文档](https://docs.github.com/zh)
## 第1章 欢迎来到GitHub的世界
> GitHub 与 Git 的区别 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=32&annotation=BXDCEX4P))
> >Git，通常指Git本地仓库，是存放用户源代码的地方；  我们电脑上通常需要安装一个应用程序Git，它在本地运行，以独立仓库为工作单位。Github是一个面向用户的代码托管平台，通过改平台为用户提供代码托管服务，也可以理解为GitHub、Gitee、Git Lab、Coding这些平台都为远程仓库。 

---
> Pull Request 的页面展示 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=33&annotation=6MR54RFB))

---
> 输入“# 编号”，会连接到该仓库所对应的 Issue 编号。输入 “用户名 / 仓库名 # 编号”则可以连接到指定仓库所对应的 Issue 编号。只要按照这类特定格式书写便会自动创建链接。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=35&annotation=XAKL4CFL))

---
### 团队协作

> 只要将感兴趣的仓库添加至 Watch 中，就可以在 News Feed 查 看该仓库的相关信息（图 1.6）。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=35&annotation=YBV9GKGJ))

([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=36&annotation=M7VTTJ9N))  ![image-20230306143300468](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230306143300468.png)
> 比如，将全公司共用代码库的仓库添加到 Watch 中，便能在第一时间 掌握最新版本的新功能或 BUG 修正的信息。当然，您也可以参与到讨论 中去，积极地提出意见。如有必要，还可以通过 Pull Request 提交代码。 将隔壁团队正在开发的仓库添加到 Watch 中，就可以每天查看他们 都在开发什么功能。一旦发现有用的功能或者库，可以立刻运用到自己 的开发团队。如果能进一步交流，分割出共用的库，从而建立起新的仓 库，便成了不同开发者团队间协作的美谈。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=36&annotation=T97WR287))

\---
### 社会化编程
> 在工作中接触非公开代码的职业程序员们，更应该接触世界上的不 同文化，拓展见闻。如果只在公司这一封闭的小世界中敲代码，往往在 不知不觉间，手中的技术就变得陈腐不堪了。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=38&annotation=NJ5LF32K))

\---


> 放眼世界，注意那些日新月异的源代码、技术、设计以及文化，会 对自己编写的源代码及成果带来巨大影响。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=38&annotation=FUDRCWGT))

\---


> 一个求职者能否编写项目所需的源代码，最切实可行的办法就是看他实 际写出的东西。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=39&annotation=DR394U4K))

\---


> 看看 GitHub 就能了解一 个程序员的实力 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=39&annotation=95VQQVD4))

\---


> 应聘的成功与否将取决于您曾经编写过的代码。因此，面向全世界的代码公开必将越发重要。以编写代码为生的职业程序员们，更应该进行社会化编程。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=39&annotation=WT2H4R8Q))

\---
> GitHub 最大的特征是“面向人” ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=39&annotation=XGS5V5S7))

\---

> GitHub 除项目之外，还可以把注意力集中到人身上。我们不但能阅 览一个人公开的所有源代码，只要查看其控制面板中的 News Feed，还能知道他对哪些仓库感兴趣，什么时候做过提交等。一个人在GitHub进行的开发是一目了然的。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=39&annotation=JTPC3G7D))

\---
### GitHub 提供的主要功能
- 代码托管功能：Git仓库
  你的git仓库的源代码完全公开，如果只想对自己公开，需要掏钱；
- Organization账户
  公司使用，公开仓库则无需付费，适合搞团体开发的组织使用；
- Issue
  >  在 GitHub 上，每当进行Pull Request， 都会同时创建一个 Issue。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=41&annotation=T4YSU5JU))  每一个功能更改或修正都对应一个 Issue，讨论或修正都以这个 Issue 为中心进行。只要 查看 Issue，就能知道和这个更改相关的一切信 息，并以此进行管理。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=41&annotation=K2W8WCSX))
- Wiki
  > 通过 Wiki 功能，任何人都能随时对一篇文章进行更改并保存，因 此可以多人共同完成一篇文章。该功能常用在开发文档或手册的编写 中。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=41&annotation=QZPX9LAD)) Wiki 页也是作为 Git 仓库进行管理的，改版的历史记录会被切实保 存下来，使用者可以放心改写。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=41&annotation=9P74R6N2))
- Pull Request
  > 开发者向 GitHub 的仓库推送更改或功能添加后，可以通过 Pull Request 功能向别人的仓库提出申请，请求对方合并。 Pull Request 送出后，目标仓库的管理者等人将能够查看 Pull Request 的内容及其中包含的代码更改。 同时，GitHub 还提供了对 Pull Request 和源代码前后差别进行讨论 的功能。通过此功能，可以以行为单位对源代码添加评论，让程序员之间进行高效的交流。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=41&annotation=HU2QYU5T))

\---
> GitHub 上受到瞩目的软件列举（截至2013年2月） ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=42&annotation=Q6KW2ITN))
![image-20230306152004909](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230306152004909.png)
\---
## 第2、3章 Git的导入、使用GitHub的前期准备
> Git 仓库管理功能是 GitHub 的核心。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=46&annotation=PNH5QNMH))

\---
> Git 属于分散型版本管理系统，是为版本管理而设计的软件。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=46&annotation=7BIV73AR))

\---
### 版本管理
> 版本管理就是管理更新的历史记录 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=46&annotation=YLVXX924))

\---
#### 分散型
> Git属于分散型版本管理系统 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=47&annotation=8K3G8TH2))

\---
> GitHub 将 仓库 Fork 给了每一个用户。Fork 就是将 GitHub 的某个特定仓库复制到自己的账户下。Fork 出的仓库与原仓库是两个不同的仓库，开发者可以随意编辑。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=47&annotation=YWIBC65W))

> [!NOTE] Github的Fork功能是什么？
> 查了词典，fork组为动词，是分岔的意思，比如在路或者河道的岔口转弯，就叫做fork。
> 
> GitHub中的Fork功能允许用户复制一个已有的仓库（repository）到自己的账户中，并在自己的账户中独立地进行修改和管理，而不会影响原始仓库的内容。
> 
> 具体来说，当你在GitHub上找到一个你感兴趣的项目时，你可以通过点击Fork按钮，将该项目的所有内容（包括代码、文档、图片等）复制到你自己的GitHub账户中的一个新仓库中。这个新仓库会保留原始仓库中的所有历史记录，并与原始仓库保持同步。然后，你可以在这个新仓库中自由地进行修改、添加、删除等操作，直到你满意为止。
> 
> 当你在自己的Fork版本中进行了修改并想把这些修改合并到原始仓库中时，你可以提交一个Pull Request（PR），请求原始仓库的管理员审核你的修改，并将其合并到原始仓库中。如果审核通过，你的修改就会成为原始仓库的一部分，其他人也可以看到你的贡献。
> 
> Fork功能是GitHub中非常常用的一个功能，它方便了开源社区的协作和贡献，使得项目的改进和更新更加容易和快捷。





[image] ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=48&annotation=UNIJ4WBX))  ![image-20230306153810405](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230306153810405.png)
> 分散型拥有多个仓库，相对而言稍显复杂。不过，由于本地的开发环境中就有仓库，所以开发者不必连接远程仓库就可以进行开发。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=48&annotation=MF2R94U4))

某些集中性仓库的劣势在于开发者必须在连接服务器的条件下进行开发，而不能在本地进行开发。---
### Git的安装、配置和使用
#### Git安装
按照默认方式安装了git，系统里新添加了这三项。![image-20230306171231717](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230306171231717.png)

> [!NOTE] 补充：什么是bash命令
> Bash命令是在类Unix操作系统上使用的命令行解释器，它充当用户与操作系统内核之间的接口。Bash是一种功能强大的命令行工具，可以执行各种任务，如文件操作、软件安装、网络管理等等。它也可以用于编写脚本，以便自动执行一系列任务。在Linux、macOS和其他类Unix操作系统上，Bash是默认的shell，提供了一种强大的方式来与系统进行交互。

#### Git配置
Git 提供了一个叫做 git config 的工具，专门用来配置或读取相应的工作环境变量。

这些环境变量，决定了 Git 在各个环节的具体工作方式和行为。这些变量可以存放在以下三个不同的地方：[详细内容可参考官方说明](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address)

- ***/etc/gitconfig 文件***：
  系统中对所有用户都普遍适用的配置。若使用 git config 时用 --system 选项，读写的就是这个文件。![image-20230306171916719](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230306171916719.png)
- ***~/.gitconfig 文件***：
  **用户目录**下的配置文件只适用于该用户。若使用 git config 时用 --global 选项，读写的就是这个文件。   ![image-20230306210421852](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230306210421852.png)
  > 设置姓名和邮箱地址 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=52&annotation=SFAB8YDB))![image-20230306172514606](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230306172514606.png)这个命令，会在“~/.gitconfig”中以如下形式输出设置文件。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=52&annotation=482Q7CAX))![image-20230306172605235](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230306172605235.png)想更改这些信息时，可以直接编辑这个设置文件。这里设置的姓名 和邮箱地址会用在 Git 的提交日志中。由于在 GitHub 上公开仓库时，这 里的姓名和邮箱地址也会随着提交日志一同被公开，所以请不要使用不便公开的隐私信息。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=53&annotation=GBGUZIQI))
 
- ***当前项目的 Git 目录中的配置文件（也就是工作目录中的 .git/config 文件）***：
  这里的配置仅仅针对当前项目有效。每一个级别的配置都会覆盖上层的相同配置，所以 .git/config 里的配置会覆盖 /etc/gitconfig 中的同名变量。

**提示**：如果用了 --global 选项，那么更改的配置文件就是位于你用户主目录下的那个，以后你所有的项目都会默认使用这里配置的用户信息。
如果要在某个特定的项目中使用其他名字或者电邮，只要去掉 --global 选项重新配置即可，新的设定保存在当前项目的 .git/config 文件里。

#### Git与Github的使用
##### 设置SSH Key
书中提到如何进行SSH Key的设置（注意，Linux系统中输入密码时是不可见的）([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=57&annotation=FNH45N2Q))，但并没有对Git中的SSH Key的概念性的介绍。没有缘由地就让搞SSH Key和添加公开密钥。日本人写书都没有逻辑性的么（黑人问号.jpg）？ 

##### 在GitHub中添加公开密钥
([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=58&annotation=H7TMUU3C))注意：在GitHub上new SSH Key时，key的内容是要把id_rsa.pub中的内容全部粘贴进去，包括开头的`ssh-rsa`和结尾的邮箱。

##### Github中创建仓库
> 创建仓库 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=59&annotation=KVMRQE8B))

> [!NOTE]  .gitignore文件 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=61&annotation=BFRDPU4L))
>是用来干啥的？❓
> 该文件用来描述 Git 仓库中不需管理的文件与目录 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=61&annotation=B2UXHF4N))。


> [!NOTE] 专栏：公开时的许可协议 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=65&annotation=2DKCA42D))
> ![image-20230309162236664](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309162236664.png)




##### clone已有仓库
- 首先需要把要clone的仓库的ssh url复制下来;
  例如`git@github.com:akashgiricse/Custom-Pomodoro-Countdown.git`![image-20230309041726712](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309041726712.png)
- bash中执行clone命令； ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=63&annotation=82A4QWZK))  
  `$ git clone git@github.com:akashgiricse/Custom-Pomodoro-Countdown.git`
  在GitHub上找到了这本书里的这个[Hello-World项目](https://github.com/hirocastest/Hello-World)，然后自己尝试clone了下来。![image-20230309043507246](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309043507246.png)
  提示：因为第一次尝试clone一个git仓库到本地，本地修改后进行提交、push等一系列操作，所以最好创建一个自己的仓库进行尝试。
- 指定clone下来的git仓库在本地磁盘中的位置
  在clone的时候并没有指定磁盘路径，它默认是存储在`C:\Users\47176`这个路径下。无论是使用HTTPS协议还是SSH协议clone，如果想指定路径，则需要在git clone命令后指定路径。
  e.g. `$ git clone git@github.com:hirocastest/Hello-World.git f:/GitStock`![image-20230309150459727](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309150459727.png)。但新的问题是，clone结束，仓库中的文件存放在了GitStock文件夹里，而不是放在Hello-World文件夹。`$ git clone git@github.com:hirocastest/Hello-World.git f:/GitStock/Hello-World`像这样最好是把项目指定一下。[](![image-20230309151815225](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309151815225.png))![image-20230309151909843](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309151909843.png)
- commit
  首先需要用git add命令将文件加入暂存区，然后再通过git commit命令进行提交，最后可以用git log命令 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=64&annotation=AZ4S66G8))查看提交日志。
  > 使用git commit命令将某文件，例如hello_word.java 提交至仓库。这样一来，这个文件就进入了版本管理系统的管理之下。今后的更改管理都交由 Git 进行。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=64&annotation=JBVTQZXC))
  `$ git commit -m '提交的描述信息'`
- push
   只要执行 push，GitHub 上的仓库就会被更新 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=65&annotation=DA9A8NDY))。在Github刷新仓库，就能看到新提交上的内容，代表着代码在Github上公开了。 

##### 删除本地仓库
- `$rm -rf .git`命令
  这是一个用于删除当前目录下的.git文件夹的命令，其中 -r 选项表示递归删除， -f 选项表示强制删除，忽略不存在的文件和提示信息。在Git中，.git文件夹包含了所有版本控制相关的文件和信息，删除该文件夹会删除版本控制历史和当前状态。
- `$rm -rf repository`命令
  如果您想要删除整个克隆下来的 repository，可以使用 rm -rf repository 命令来删除整个目录。请注意，这个命令非常强大，会无条件地删除指定目录及其所有子目录和文件，请谨慎使用。
- 如果觉得本地仓库可以直接彻底删除，那就直接磁盘删除。（试了下这个命令没卵用？）
## 第4章 通过实际操作学习Git
这章主要理解常用git命令和基本操作。
### git几个常用命令
#### git init
要使用 Git 进行版本管理，必须先初始化仓库。([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=68&annotation=IJ5UN78Q))Linux在当前文件夹下创建目录的命令为`$mkdir xxxx`，进入这个新建的目录后，就初始化空仓库。如果初始化成功，执行了 git init命令的目录下就会生成 .git目录。这个.git目录里存储着管理当前目录内容所需的仓库数据,用于跟踪管理项目中的所有更改，并记录提交历史和分支信息等。 使用该命令初始化的仓库可以与远程仓库关联，通过 Git 提供的一系列命令来实现版本控制。([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=68&annotation=EM3KTXUR))。

> [!NOTE] .git文件夹
> 
在 Git 中，我们将.git目录的内容称为“附属于该仓库的工作树”。 文件的编辑等操作在工作树中进行，然后记录到仓库中，以此管理文件 的历史快照。如果想将文件恢复到原先的状态，可以从仓库中调取之前 的快照，在工作树中打开。开发者可以通过这种方式获取以往的文件。 具体操作指令我们将在后面详细解说。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=68&annotation=2Q4M37PK))
#### git status
git status命令用于显示 Git 仓库的状态([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=68&annotation=AXX5DLS6))。 比如分支、提交状态、Untracked file等内容。

> [!NOTE] 创建README.md的命令([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=69&annotation=LBNA2N8U))
> `$ touch README.md`

#### git add
如果只是用 Git 仓库的工作树创建了文件，那么该文件并不会被记 入 Git 仓库的版本管理对象当中。因此我们用 git status命令查看 README.md 文件时，它会显示在 Untracked files 里([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=69&annotation=A75RE9F4))。
要想让文件成为 Git 仓库的管理对象，就需要用 git add命令将其加入**暂存区**（Stage 或者 Index）中。暂存区是提交之前的一个临时区域([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=69&annotation=ND4WF8DH))。

**补充：** add 操作又具体可细分为以下三种情况：

```
$ git add .    // 一次性全部添加
$ git add -A   // 只提交修改的部分文件
$ git add xxx  // 添加指定文件
$ git add *    //将所有改动过的文件添加到暂存区
$ git add -f   //强制将被git忽略的文件添加到Git暂存区
```

- git add -A 与 git add * 的区别
  git add -A 命令除了将所有改动过的文件添加到暂存区，包括.gitignore文件夹下的文件（被Git忽略的文件），另外还会将在本地目录中被删除文件从暂存区中删除；git add -A 命令会递归地检查当前工作目录中的所有子目录，将其中所有改动过的文件都添加到暂存区。
  git add * 同样是将改动的文件添加到暂存区，但不添加.gitignore文件夹下的文件，也不会从暂存区中移除在本地目录下删除的文件；git add * 命令只会检查当前工作目录下的文件，不会递归地检查子目录。
  
- git add -f
  在 Git 中，如果某个文件被添加到 .gitignore 文件中，那么 Git 就会默认将其忽略，即不会将其加入到 Git 的暂存区中。这样可以避免在 Git 仓库中添加不必要的文件，从而减小仓库的体积，并且避免对仓库造成垃圾文件的影响。
  但是，在某些情况下，我们可能需要将被 Git 忽略的文件强制添加到 Git 的暂存区中，例如需要备份或恢复某些配置文件等。这时可以使用 git add -f 命令。
  具体来说，git add -f 命令会强制将指定的被 Git 忽略的文件添加到 Git 的暂存区中。需要注意的是，由于这些文件被添加到了暂存区中，它们可能会被提交到 Git 仓库中。因此，在使用 git add -f 命令之前，需要确认这样做的后果，并谨慎操作。
  总之，git add -f 命令是 Git 中的一个命令，可以强制将被 Git 忽略的文件添加到 Git 的暂存区中，但需要注意操作的后果。
- git add -u
  git add -u 命令用于将已经被 Git 管理、也就是被追踪（tracked）的文件，即已经加入版本控制的文件，从工作目录中的修改和删除更新到暂存区中。
  git add -u 命令只会将已被Git接管的文件的修改操作或删除操作更新到 Git 的暂存区中，而不会将新增的文件添加到暂存区中。

#### git commit
git commit命令可以将当前暂存区中的文件实际保存到仓库的历史记录中。通过这些记录，我们就可以在工作树中复原文件([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=70&annotation=TFFAK7JV))。
- 记述一行提交信息([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=70&annotation=2DZX5WAD))，就用命令`git commit -m "信息描述"`
- 记述详细提交信息 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=70&annotation=JY5S442Q))，用命令`git commit`，不要-m
  当执行git commit，自动打开了一个代码编辑器 ，要添加的描述信息就写在文本文件的最上方，如图![image-20230309194902939](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309194902939.png)编辑完后保存并关闭代码编辑器即可。
- 中止提交 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=71&annotation=J9LEJU9B))
  如果在编辑器启动后想中止提交，请将提交信息留空并直接关闭编 辑器，随后提交就会被中止([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=71&annotation=NC6X5TJK))。
- `git commit -am "信息描述"`
  执行`git commit -am`命令作用上相当于执行了`git add .`加上`git commit -m "xxx"`命令，但二者还是有区别的。具体请看这篇文章[[实例说明git commit -m与git commit -am区别]]

#### git log
执行git log命令，能查看每次commit的信息，包括提交用户、时间和commit的描述。
如果commit成功，则都会被记录入日志中。如图，该仓库执行了四次git commit操作。![image-20230309195606202](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309195606202.png)

> [!NOTE] 当存在很多commit记录时，如何退出查看log模式？
> 输入<kbd>q</kbd>或<kbd>zz</kbd>

##### git log --pretty=short
- 在 git log命令后加 上 --pretty=short ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=72&annotation=AT98BIQU))，则每条commit信息会稍微精简。
  （好像是不显示commit日期了）![image-20230309200631810](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309200631810.png)
##### git log filename
- 只显示指定目录、文件的日志 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=72&annotation=IIT3G2AE))
  只要在 git log命令后加上**目录名**，便会只显示该**目录下的日志**。 如果加的是**文件名**，就会只显示与该文件相关的日志 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=72&annotation=78784Y2U))  ![image-20230309201219707](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309201219707.png)
##### git log -p filename
- 显示某文件的改动 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=73&annotation=LHPTLNBM))
  如果想查看提交所带来的改动，可以加上 -p参数，文件的前后差 别就会显示在提交信息之后 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=73&annotation=5CJ5BFGJ))。比如，执行命令`git log -p README.md`，就可以只查看 README.md 文件的提交日 志以及提交前后的差别 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=73&annotation=RYPUNH4G))。如图![image-20230309203249562](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309203249562.png)
##### git log -数字 或 git log -n数字
默认情况下，git log命令将输出对某个分支的所有提交。如果我们只希望看到一些最新的提交，而不是全部，那么我们可以使用-n ，后面跟着我们希望看到的提交数量。或者直接用参数-1，-2，-5等，则会列近1次，2次，5次的提交。
`git log -2`
`git log -n2`
##### 补充：每一次commit都有一个哈希值
在日志中，可以看到每一条commit记录的字符串“commit”旁都有一长串字母数字组合。![image-20230309195948330](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230309195948330.png)一长串字母数字组合就是这一次commit的哈希值。Git 的其他命令中，在指向提交时会用到这个哈希值([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=72&annotation=MI4KXACN))。



#### git diff
使用该命令可以查看两种差别：
1. 工作树和暂存区的差别 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=73&annotation=S8YSDQRT))
  对某文件修改了，但是还没执行git add命令让修改内容加入暂存区；
2. 工作树和最新提交的差别 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=74&annotation=TA8AE4VC))|
  对某文件修改了，也使用git add命令往暂存区添加过了，但是还没有commit，执行`git diff HEAD`命令可以查看当前暂存区与最近一次commit时库的差别。
**总结**：git diff默认比较的是当前与暂存的区别，如果是git diff HEAD ，则比的是当前与最近一次提交的差别。
**补充**：命令结果中显示的内容。“+”号标出的是新添加的行，被删除的 行则用“-”号标出 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=74&annotation=YY3AER65))。 不妨养成这样一个好习惯：在执行 git commit命令之前先执行 git diff HEAD命令，查看本次提交与上次提交之间有什么差别，等 确认完毕后再进行提交。这里的 HEAD 是指向当前分支中最新一次提交 的指针([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=74&annotation=3Y3T8V6R)) 。
### 分支
- 分支存在的目的：为了并行开发的展开（多人同时高效开发）；
- 分支的特点：
  1. master 分支是 Git 默认创建的分支，基本上所有开发都是以这个分支为中心进行的 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=75&annotation=E487CUCM))；
  2. 不同分支中，可以互不影响地同时进行完全不同的作业”([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=75&annotation=SWD23FCH))；
  3. 一个分支的作业完成后可与master分支合并。
#### git branch
##### 查看已存在的分支：git brach
显示本地仓库的分支一览表 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=76&annotation=Q335JECY))，当前分支前面有个`*`。
##### git branch -a
添加 -a 参数可以同时显示本地仓库和远程仓库的分支信息。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=94&annotation=INSXXQS9))
##### git branch -vv
`git branch -vv`用于列出所有本地分支及其与远程分支的关联情况。这个命令的输出结果可以告诉你每个本地分支当前所关联的远程分支的名称、远程分支的URL，以及本地分支与远程分支之间的关系状态（如是否是上游分支、是否有本地分支的提交需要被推送到远程分支等）。

具体来说，使用 git branch -vv 命令，会输出如下内容：
```shell
* main            5e0b692 [origin/main] Merge branch 'feature-branch'
  feature-branch  1c43e22 [origin/feature-branch] Add new feature
  bugfix-branch   96cf71c [origin/bugfix-branch: ahead 2] Fix bug in code
```
上面的输出结果表示当前本地分支为 main，并且它的远程分支是 origin/main。此外，输出结果还列出了另外两个分支 feature-branch 和 bugfix-branch，并且它们分别与 origin/feature-branch 和 origin/bugfix-branch 相关联。其中，bugfix-branch 还显示了状态为 ahead 2，表示该本地分支比它所关联的远程分支多了两个提交，需要将这些提交推送到远程分支。

##### 当前分支最后一次提交处(HEAD)创建新的分支
`git branch <branch-name>`


#### git checkout
##### 一个命令完成创建+切换：`git checkout -b feature-A`
创建名为feature-A的分支并切换至此分支。
##### 分两步实现创建+切换
先创建分支`git branch feature-A`，再切换至新创建的分支`git checkout feature-A`
##### 切换回上一个分支
连字符`-`代替分支名，切换回上一个分支。`git checkout -`
##### 创建本地分支并设置track的远程分支
`git checkout -b <local-branch> <remote/remote-branch>`;
比如 git checkout -b feature-D origin/feature-D。这个命令等于自动为本地分支feature-D设置了upstream，可通过git branch -vv命令查看到。
##### git checkout -t
- Syntex：`git checkout -t <remote>/<remote-branch>`，
- e.g. 在当前分支下，执行`git checkout -t origin/feature-branch`，Git将在本地创建一个与远程origin中已经存在的分支feature-branch同名的的本地分支，并且该本地分支将track远程orgin的feature-branch分支。
- 该命令不负责在origin中创建新的分支，只负责在本地创建同名分支，使用git fetch命令，远程分支数据就能映射到本地分支。
  
#### git switch
注意：在Git2.23版本中，引入了一个名为git switch的新命令，最终会取代git checkout,因为checkout作为单个命令有点超载（它承载了很多独立的功能）。
参考：[git switch官方文档](https://git-scm.com/docs/git-switch)
#### 魔法快照
##### 培育分支
如果feature-A 分支左侧标有`*`，表示当前分支为 feature-A。在这个状态下像正常开发那样修改代码、执行 git add命令并进行提交的话，代码就会提交至 feature-A 分支。像这样不断对一个分支（例如 feature-A）进行提交的操作，我们称为“培育分支” ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=77&annotation=U9H2LNNL))。
##### 在一个自定义分支下修改文件，不会影响master分支
详情见：切换到 master 分支 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=77&annotation=AXXCLHND))
#### 特性分支
特性分支的概念”([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=78&annotation=A6KS5JQX))
#### 主干分支
主干分支是特性分支的原点，同时也是合并的终点。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=79&annotation=LK47TBU7))
#### git merge
将特性分支feature-A合并到主干分支master，步骤：
1. 先切换至master分支；
2. `git merge --no-ff feature-A`
   
> [!NOTE] 为什么合并命令要加上参数--no-ff
> 参考文章：[[../../Inbox/Git网络教程/Git 合并时 --no-ff 的作用]]
> 只需要知道，是否使用该参数，合并后的代码是一样的，但不使用参数的快进式合并会将feature的commit历史混进master中，从而搅乱了master的commit历史，在以后退回历史版本的时候就会出现各种错乱。
> 总结：使用参数就是为了避免快进式合并造成的commit历史混乱。

#### git rebase
Rebase实际上就是取出一系列的提交记录,“复制”它们，然后在另外一个地方逐个的放下去。
Rebase的优势就是可以创造更线性的提交历史，这听上去有些难以理解。如果只允许使用Rebase的话，代码库的提交历史将会变得异常清晰。
#### git log --graph
以图表形式查看分支 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=80&annotation=YRUGKNNS))。
### 更改提交
#### git reset 回溯历史版本
书里这部分内容就是个示例演示，回溯到某一历史状态的命令是`git reset --hard 哈希值`。需要注意的是，git log命令只能查看以当前状态为终点的历史日志([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=83&annotation=N38S6NSM))，因此在当前版本下使用git log命令查询不到比当前版本更先进的版本的哈希值，那么如果你想将状态向前推进，即去到更先进的版本，需要用`git reflog`命令查看先进版本的哈希值，然后拿着这个哈希值在执行`git reset --hard 先进版本的哈希值`命令 。
书里演示的就是下图分支变化的过程。
![image-20230310005838339](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230310005838339.png)


再详细的内容书里都写了，不再赘述。

> [!NOTE] 哈希值
> 哈希值在真实的 Git 世界中也会更长（译者注：基于 SHA-1，共 40 位）。例如提交记录的哈希值可能是 fed2da64c0efc5293610bdd892f82a58e8cbc5d8。
> 但Git 对哈希的处理很智能，只需要提供能够唯一标识提交记录的前几个字符即可。因此可以仅输入fed2 而不是上面的一长串字符。



#### git commit --amend 修改提交信息
修改提交的信息，但是它只能修改最近一次提交的信息，而无法修改多个提交的信息。git rebase -i 命令则可以修改多个提交的信息，包括合并提交、拆分提交、删除提交等。
例如，如果需要修改多个提交的信息或者将多个提交合并为一个提交，那么使用 git rebase -i 命令会更加方便。此外，git rebase -i 命令还可以让我们对提交历史进行重排序、修改提交内容等高级操作，这些操作 git commit --amend 命令都无法完成。
如果只需要修改最近一次提交的信息，那么使用 git commit --amend 命令会更加方便。如果需要修改多个提交的信息，或者对提交历史进行高级操作，那么使用 git rebase -i 命令则会更加适合。
#### git rebase -i 压缩历史
 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=87&annotation=MEWQX26E))  就是将最近两次commit历史经过人为编辑修改为一次commit历史。压缩两次历史的命令就是`$ git rebase -i HEAD~2` ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=89&annotation=5K3BY3XL))，HEAD指针指向当前分支的最近一次提交，HEAD~2的意思就是最近两次提交，其中还提到了`git commit -am`命令（参考本note）。具体如何使用书里用实例描述的很清楚了，不再赘述。
### git push
#### 概念：origin 仓库  、upstream（上游）
##### origin仓库
 - ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=92&annotation=H4JHKJXM))   
 - 参考：[[../../Inbox/Git网络教程/Git 里面的 origin 到底代表啥意思？]]
 - 总结一句:
   origin代表了一个远程仓库，可以把它想象为一个远程仓库的url，只不过我们给这个远程仓库起了一个别名叫做origin，这个别名是可以更改的，但通常也没必要改。

##### upstream
- ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=92&annotation=S8YQ586J))
- 依旧没明白，粘几个链接吧，学当中可以再回来想:
  [Definition of "downstream" and "upstream"](https://stackoverflow.com/questions/2739376/definition-of-downstream-and-upstream)
  [Javatpoint--Upstream and Downstream](https://www.javatpoint.com/git-upstream-and-downstream#:~:text=The%20term%20upstream%20and%20downstream,not%20restricted%20to%20Git%20repositories.)
  [git中的upstream--陈晓锋的学习笔记](https://breeze924.github.io/2018/08/30/git%E4%B8%AD%E7%9A%84upstream/)
  studytonight上两篇写的还不错： [studytonight--Git Upstream and Downstream](https://www.studytonight.com/git-guide/git-upstream-and-downstream)  [studytonight--How to set Upstream Branch on Git?](https://www.studytonight.com/git-guide/how-to-set-upstream-branch-on-git)
  [Why do I have to "git push --set-upstream origin branch"?](https://stackoverflow.com/questions/37770467/why-do-i-have-to-git-push-set-upstream-origin-branch)
- 初步理解：
  1. upstream和downstream是相对术语，可用于描述两个仓库之间的数据流动。从一个远程仓库pull或clone得到的本地仓库称为该仓库的downstream。我们push更改内容上去的仓库称为upstream。upstream仓库通常是所有协作者贡献的中央远程仓库。在对upstream仓库进行任何更改时，我们必须小心，因为错误的更改可能会影响从该upstream拉取的所有downstream仓库；
  2. 当我们要将本地仓库push到远程仓库的时候，通常使用`git push -u <remote-repo-name> <remote-branch-name>`命令，参数-u相当于--set-upstream，即是*为本地分支设置一个上游，来控制push到哪个远程分支*。(`<remote-repo-name>`一般是origin);

#### 语法:git push -u orgin 'remote-branch'
应该是在本地已经有了分支以后，然后才能用这个命令将本地分支push到远程的同名分支。
#### 将本地仓库推到远程仓库的步骤
  1. 先在远程仓库创建一个仓库，为防止与其他仓库混淆，仓库名请与本地仓库保持一致 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=91&annotation=PHXMN3VL))；
   >⚠注意：
   >创建时请不要 勾选 Initialize this repository with a README 选项。因为一旦勾选该选项，GitHub 一侧的仓库就会自动生成 README 文件，从创建之初便与本地仓库失去了整合性([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=91&annotation=CVSFRXNK))。
  2. 使用git push命令将本地仓库推给远程仓库；
     > 如果当前本地分支还没有指定将远程仓库的哪个分支作为它的上游，则需要使用参数-u。语法为`git push -u origin <remote-branch-name>`，设置一次，下次再对同一个远程分支执行pull/push操作时就不需要重复指定，直接`git pull/git push`即可。
     > >-u参数可以在推送的同时，将 origin 仓库的 master 分支设置为本地仓库当前分支的 upstream（上游）。添加了这个参数，将来运行 git pull命令从远程仓库获取内容时，本地仓库的这个分支就可以直接从 origin 的master 分支获取内容，省去了另外添加参数的麻烦。” ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=92&annotation=6RGYHXXF))
     
#### 本地某分支推至远程同名分支
除了 origin的master分支之外，远程仓库也可以创建其他分支（例如feature-D）并将它以同名的形式push至远程仓库的（feature-D）分支。([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=93&annotation=8WSW8GQF))
### 从远程仓库获取
#### git clone
在一个新的目录下clone某项目，则进到这个目录文件夹下，右键`Git Bash Here`，git bash窗口弹出后直接执行clone指定仓库的命令，无需再指定clone的路径。下图进行了演示。
![文件夹中启动git bash 1](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/%E6%96%87%E4%BB%B6%E5%A4%B9%E4%B8%AD%E5%90%AF%E5%8A%A8git%20bash%201.gif)
#### 新建分支用于追踪远程分支
比如新建一个fix-D本地分支，用于从远程仓库的feature-D分支获取内容，`git checkout -b fix-D origin/feature-D`。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=94&annotation=B8XPA5VC))  
#### git pull
##### git pull是如何如何工作的？
- git pull ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=95&annotation=HB8DJLEE)) 是一个命令，用于使用在远程存储库中所做的更改来更新远程存储库的本地副本。它首先从远程存储库获取更改，然后将它们合并到本地存储库中，从而实现这一点。
- 以下是 git pull 命令所涉及的步骤：
  1. 首先，git pull 命令连接到本地存储库配置中指定的远程存储库；
  2. 然后，它将检索自上次使用 git fetch 命令与远程存储库同步以来对远程存储库所做的任何新更改。这不会修改本地文件；
  3. 然后，git pull 命令自动将远程存储库中的更改合并到本地存储库中；
  4. 如果远程存储库中的更改与本地更改之间存在冲突，Git 将暂停拉取过程，并要求您手动解决冲突；
  5. 合并完成后，远程存储库中的更改将应用于本地存储库；
- 需要注意的是，git pull 可能会覆盖您的本地更改，因此在从远程存储库pull之前提交更改是一个好主意。您还可以使用 git fetch 从远程存储库中获取更改，而无需合并它们，这样您就有机会在合并之前查看它们。
##### git pull语法
- `git pull <remote> <remote-brach>`
  - The syntax of the git pull command is as follows:`git pull [<options>] [<repository> [<refspec>...]]`
  
  - Here's what each part of the syntax means:
    - git pull: This is the command itself, which tells Git to fetch changes from a remote repository and merge them into the current branch.
    - `<options>`: These are optional flags that modify the behavior of the git pull command. Some commonly used options include --rebase (to rebase local changes on top of the updated remote branch), --no-commit (to fetch changes without committing them automatically), and --no-edit (to skip the merge commit message editor).
    - `<repository>`: This is the name of the remote repository that you want to pull changes from. By default, Git uses the "origin" remote that was set up when you cloned the repository, but you can specify a different remote name if you have multiple remotes.
    - `<refspec>`: This is a reference to a branch or commit that you want to pull from the remote repository. By default, Git pulls changes from the branch that is currently checked out locally (i.e., the branch that you are on when you run git pull). However, you can specify a different branch name or commit hash if you want to pull changes from a specific branch or point in history.

  - Here's an example of how you might use the git pull command to fetch and merge changes from the "master" branch of the "origin" remote:`git pull origin master`
  
- `git pull --rebase`
  “git pull--rebase” 是 “git pull” 命令的变体，它从远程存储库中提取更改，然后在提取的更改之上重新生成本地更改，而不是合并它们。这意味着，本地提交不是创建一个新的合并提交，而是将本地提交一个接一个地应用于远程更改之上，使提交历史看起来是线性的，更容易阅读。
  当处理feature branch或存储库的本地和远程版本之间存在冲突时，rebase可能很有用。它允许开发人员维护更清晰的提交历史，并更容易地解决冲突。
  需要注意的是，reabse可以修改提交历史记录，因此应谨慎使用，尤其是在与团队或共享分支合作时。rebase也可能导致需要手动解决的冲突，因此在运行 “git pull-rebase” 之前检查更改是一个好主意。
 
## 第5章 详细解说GitHub的功能
### Hotkey
- 在Github的任何页面，按下<kbd>shift</kbd>+<kbd>/</kbd>，都可以打开快捷键一览表。![image-20230429143642620](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230429143642620.png)
- 如果想直接访问当前repo中的某一个文件，可以直接用快捷键<kbd>t</kbd> 键 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=113&annotation=PXANLTRD))，然后输入要找的目录或文件的部分名称，找到后enter键查看即可。这样比靠鼠标点开查看效率高，但前提是你知道要找的目录或文件名或按照文件类型找。

### Gist功能
Gist可以理解为一个轻量级仓库/一个note/一个代码片段，支持任何语言，也支持Markdown语法，且它支持与其他用户共享和协作。但自己的gist不能直接申请合并到别人的repo里面。Gist为什么叫Gist？因为它gist这个单词的意思是“要点、要旨、精华”，暗示了它轻量级的特性。假如你只有一段代码需要和别人共享，你就可以创建一个gist。

### Watch/Star/Fork功能
Watch 之后该仓库的相关信息会在后述的 Notifications 中显示，让用户可以追踪仓库的内容，而 Star 更像是书签， 让用户将来可以在 Star 标记的列表中找到该仓库。另外，Star 数还是 GitHub 上判断仓库热门程度的指标之一。
Fork数字越大，表示参与这个仓库的开发的人越多；

### Blame功能
GitHub 中的 Blame 功能可以显示每行代码的修改历史，包括该行代码最后一次修改的作者、修改时间和提交信息等。Blame 功能可以帮助用户了解代码中每个部分的贡献者和修改历史，也可以用于代码审查、错误追踪和版本控制等方面。

具体来说，使用 Blame 功能，用户可以：

- 查看代码中每个部分的贡献者和修改历史，以便更好地理解代码的结构和功能。

- 追踪代码中的错误和问题，了解它们是如何引入的，并找到相关的提交和贡献者。

- 对代码进行审查和修改，了解每个修改的目的和作者，并跟踪代码的演化历史。

- 比较不同版本的代码，了解每个版本之间的修改和差异，以及它们是如何影响代码的功能和性能的。

在 GitHub 中，可以通过在代码文件中单击“Blame”按钮来访问 Blame 页面，也可以使用 Git 命令行工具或其他 Git 客户端来查看 Blame 信息。Blame 信息通常以行的形式呈现，每一行都包含代码作者、提交 ID、提交时间和提交信息等信息。Blame 信息也可以用于分析代码质量、评估代码风格和评估团队成员的工作效率等方面。

![image-20230429170422259](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230429170422259.png)


### 对文件代码可执行什么操作？
如图，假如我们点击第 10 行的行 号，这一行就会被高亮标记为黄色，同时 URL 末尾会自动添加 “#L10”。使用这个 URL，程序员们在交流时，就可以将讨论明确指向 某一行。另外，如果将“#L10”改成“#L10-15”，则会标记该文件的第 10 ～ 15 行。 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=113&annotation=F6F7E8IR))。![微信图片_20230429171541](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20230429171541.png)

### 查看特定repo的多种形式的差别
url格式：`https://github.com/raspberry5442/repo名/compare/`，后面加上这个compare，就定位到一个比较页面；![image-20230429182135159](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230429182135159.png)
#### 查看分支间的差别
- 方法一：可以直接使用URL跳转，比如`https://github.com/rails/rails/compare/4-0-stable...3-2-stable` ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=113&annotation=N6R4G3TS))这样的，但没必要；
- 方法二：在跳转到compare页面后，选择要比较的两个分支，如图，查看了4-0-stable分支与3-2-stable分支之间的差别，可以看到有46个人经过1848次提交，完成了3.2版本到4.0版本的升级工作。![image-20230429205829655](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230429205829655.png)
#### 查看某分支当前与几天前的差别
假如我们想查看 master 分支在最近 7 天内的差别，可以像下面这样 这样将时间加入 URL ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=114&annotation=5T3DQBEJ))`https://github.com/rails/rails/compare/master@{7.day.ago}...master`、`https://github.com/xuexiangjys/XUI/compare/master@{1.year.ago}...master`。语法就是`n.单位.ago`，单位可以是day/week/month/year。

#### 查看与指定日期之间的差别
`https://github.com/rails/rails/compare/master@{2013-01-01}...master` ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=115&annotation=U7FUE254))

#### 补充：git diff A..B 与 git diff A...B 之间的差别
1. 两点和三点之间的差别：
   在 Git 中，git diff A..B 和 git diff A...B 两者的意义是不同的。
   - git diff A..B 比较的是从 A 分支到 B 分支的差异。具体来说，它会**列出** B 分支相对于 A 分支增加或删除的文件内容以及文件的修改。
   - git diff A...B 比较的是 A 分支和 B 分支之间的共同祖先和 B 分支之间的差异。具体来说，它会找到 A 分支和 B 分支的最近共同祖先（即它们的分叉点），然后比较 B 分支相对于这个共同祖先增加或删除的文件内容以及文件的修改。
   这两个命令的主要区别在于它们比较的内容不同。git diff A..B 比较的是两个分支之间的差异，而 git diff A...B 比较的是两个分支在共同祖先之后的差异。在实际使用中，你可以根据需要选择不同的命令来比较不同分支之间的差异。
   
2. git diff A...B 与 git diff B...A 比较出来的结果不一样：
   - git diff A...B 找到 A 分支和 B 分支的最近共同祖先（即它们的分叉点），然后比较 B 分支相对于这个共同祖先增加或删除的文件内容以及文件的修改。
   - git diff B...A 找到 B 分支和 A 分支的最近共同祖先（即它们的分叉点），然后比较 A 分支相对于这个共同祖先增加或删除的文件内容以及文件的修改。
   执行这两个命令，找到的共同祖先是一样的，但是与共同祖先进行比较的分支是不同的，所以比较的结果也不同。

### Issue系统
#### 使用场景
Issue系统就是Bug Tracking System，简称bug跟踪系统。这个功能在以下情况下可以使用：
- 发现软件的 BUG 并报告；
- 有事想向作者询问、探讨；
- 事先列出今后准备实施的任务；
#### 功能特点
##### 对Issue打标签
标签可以自由创建，既可以按语言和技术分类，也可以按照bug、任务、备忘等作业类型分类；其实在 Issue 比较少的情况下不必每个都添加标签， 大可等 Issue 积攒到一定数量，需要进行筛选才能清晰把握时再添加标签。([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=118&annotation=PEFN64YT))
##### 复选列表的使用
其实就是Markdown语法中的`- [ ] todo1`，在Github中，无需打开Issue的编辑页面重新编辑，就可以直接改变todo的完成状态。![image-20230430165912958](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230430165912958.png)
##### Issue的编号
在 GitHub 上，每个 issue 都会被分配一个唯一的数字编号，这个编号可以用来快速地访问该 issue。这个编号通常显示在 issue 标题前面或者 issue 页面的 URL 中。在 issue 评论或者 pull request 描述中使用`#xx` 的形式**引用**该 issue，其中 xx 为该 issue 的编号，可以自动生成对该 issue 的链接。同样地，在 commit message 中加入 `#xx`，也可以将该 commit 自动关联到该 issue 上。

在 GitHub 上，每个 repository 中的 issue 编号是按照创建时间顺序依次递增的，也就是说，越早创建的 issue 编号越小。当一个 issue 被关闭后，它的编号将不再被使用，但是如果后续再创建新的 issue，这个编号仍然不会被重复使用，因此可以保证每个 issue 的编号都是唯一的。

![image-20230430171919212](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230430171919212.png)

##### 关闭Issue
如果想在git bash中关掉一个issue（而不是手动去GitHub页面close），那么你的commit的更改内容应该是和这个issue相关的。比如当你针对一个issue做出了修改，然后需要将修改推到到远程仓库，那么在提交时，使用命令如`git commit -m "fix #4: bug fixed"`，然后再git push一下当前分支，那么你的远程仓库里面的issue #4 就会被关闭，会在GitHub的issue #4 页面看到这样的提示。![image-20230430231307757](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230430231307757.png)其中`44e882e`就是此次提交的哈希值，点开就能看到你针对此次提交修改的内容。也就是说，如果你这次提交交代了是针对某issue的提交，就意味着提交后该issue会被关闭，同时你此次提交的修改也会作为你为了关闭该issue做出的修改。
当然，`git commit -m "..."`，`...`中的内容如果要填关闭了哪个issue，那么书写的格式可以是下面任意一种：
`fix #24`/`fixes #24`/`fixed #24`/`close #24`/`closes #24`/`closed #24`/`resolve #24`/`resolves #24`/`resolved #24`
通常来讲，fix代表修复，你可以在后面写个冒号，带个备注，说明你修复了什么。close的话就是纯关掉某issue，一般就不用些备注了。
##### Milestone功能
Milestone（里程碑） 可以用于管理项目中的任务和问题，并帮助追踪工作进展。可以将任务和问题分配到特定的 Milestone 中，以便更好地组织和管理它们。在 GitHub 中，通过在仓库的 Issues 页面上创建 Milestone 来启用这个功能，并将任务或问题与特定的 Milestone 相关联。在 Milestone 中，可以查看相关任务或问题的列表、完成进度和剩余工作等信息，以更好地管理项目的进展。
Milestone 中通常包括 issue，但也可以包括 pull request 或其他任务。在 GitHub 中，milestone 主要用于管理和跟踪团队在特定时间段内的工作进展。一个 milestone 可以代表一个版本或者一个特定的期限，通过将相关的任务和问题与其关联，可以更好地跟踪和管理工作进展。在 milestone 页面中，可以查看该 milestone 关联的所有 issue 和 pull request，以及其工作进展的图表和数据。([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=119&annotation=PTQMDYZN)) 
##### contributions的注意事项
[GitHub 社区指导方针](https://docs.github.com/zh/site-policy/github-terms/github-community-guidelines)
[设置仓库参与者指南：CONTRIBUTING.md](https://docs.github.com/zh/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
[Contributing Guidelines](https://github.blog/2012-09-17-contributing-guidelines/)
即在参与贡献时，要了解贡献时的规则 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=120&annotation=JFC5HTMY))，看人家的repo中的CONTRIBUTING.md文件，从而规范自己的issue描述方法、遵循pull request时的规则和要求。
##### 特定的 Issue 能转换为 Pull Request
在 GitHub 上，如果给 Issue 添加源代码，它就会变成我们马上要讲 到的 Pull Request。Issue 与 Pull Request 的编号相互通用，通过 GitHub 的 API 可以将特定的 Issue 转换为 Pull Request。([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=122&annotation=JFWCULTM))

### Pull Request功能
- 在 GitHub 上，pull request 一般由贡献者发起的，它表示想将自己的代码合并到仓库的某个分支中。通常，贡献者发起pull request的全过程如下：
  1. Fork 项目：在自己的 GitHub 上 fork 要贡献的项目，然后将其 clone 到本地。
  2. 创建分支：在本地创建一个新分支，用于实现要贡献的功能或修复 bug。
  3. 提交更改：在本地分支上进行更改，然后将这些更改提交到自己的 fork 上。
  4. 创建 Pull Request：在 GitHub 上创建一个 Pull Request，请求原始项目的所有者合并自己 fork 上的分支。
  5. 讨论和审查：原始项目的所有者和其他开发者可以在 Pull Request 中进行讨论和审查，并提出任何必要的更改。
  6. 合并 Pull Request：如果所有人都满意并且没有问题，则原始项目的所有者可以合并 Pull Request。
- pull request页面的三大模块：**Conversation**/**Commits**/**Files Changed**
#### 获取 diff 格式与 patch 格式的文件
这个不是很懂，不晓得diff格式的文件和patch格式的文件会在什么场景下使用，以后有机会用的时候再研究吧([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=124&annotation=4GYH4S3W))。
#### Conversation标签页
- 对当前pull request展开的相关的讨论、提交的历史记录都能在这个页面看到。
- 补充1：如果想在comment中引用上面默认的对话，选中后按R键即可在comment中引用选中的内容。![image-20230501175346980](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230501175346980.png)
- 补充2：在评论中应用表情的方法：在评论中输入“:”（冒号）便会启动表情自动补全功能。只 要输入几个与该表情相关的字母，系统就会为您筛选自动补全的对象。([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=126&annotation=STIPX5Q9))
#### Commits标签页
在 Commits 标签页中，按时间顺序列表显示了与当前 Pull Request 相关的提交 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=125&annotation=SE93LQRQ))
#### File Changed标签页
- GitHub中的pull request页面中有一个标签页叫做Files changed，它可以让你查看对比当前分支和目标分支的所有更改，包括添加、删除和修改的文件和代码行，标签上的数字表示新建及被更改的文件数 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=126&annotation=AF3SWS3B))。这个标签页是在pull request页面中很重要的一个组成部分，因为它可以让你和其他合作者更好地协作和审核代码更改。
- files changed 标签页中允许对代码的每一行进行评论。评论后，提交者可以收到有关评论的通知，从而能够及时跟进并做出相应的修改。

### Wiki功能
- 它相当于repository的一个文库，是一个适合多人共同编写的文档，Wiki文库可以直接被clone下来。；Wiki和README.md的区别是README.md通常是用于在代码仓库中提供项目说明、安装指南、使用说明等信息。而Wiki则更多地用于提供更广泛的文档和信息，例如软件产品的文档、用户手册、FAQ等。README.md更注重展示项目的概览和说明，而Wiki则更注重提供细节文档和信息，且有更强的格式化和布局能力。
- Wiki中有几个功能：Pages 标签页 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=128&annotation=KSNFJPDL))、History 标签页 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=129&annotation=XABNYLNB))。
- 补充：在 Wiki 中显示侧边栏 ([pdf](zotero://open-pdf/library/items/6VSIXIP2?page=129&annotation=SNIX6I7G))
  就是new一个title为`_sidebar`的page。然后就可以看到Wiki的home页有一个侧边栏。这个侧边栏是在跳转到Wiki的任何page都会显示的。

### Insights功能
一个仓库的导航栏里有一个Insights的选项，Insight page提供了一些分析工具，帮助用户了解仓库的活动情况。![image-20230503160527287](https://zheyu-notepic.oss-cn-beijing.aliyuncs.com/Upside/image-20230503160527287.png)
我觉得比较有用的界面是Network graph和Community standards，剩下的都是图标数据分析，看自己的仓库意义不大，看别人的仓库，这个Insight功能提供的分析数据比较有参考价值。

### Github Action & workflow
[官方文档--GitHub Actions](https://docs.github.com/zh/actions/quickstart)
GitHub Actions是GitHub在2019年推出的一项自动化工具，它可以帮助开发人员在GitHub仓库中设置自动化任务，如自动构建、测试、部署、发布等，从而提高工作效率，减少开发人员的手动操作，并且可以在GitHub仓库中直接管理和监控自动化人物的运行情况。

> 以下列举了一些GitHub Actions能做的事情。

1. 自动化测试和部署：您可以使用 GitHub Actions 在代码更改时自动运行测试和部署工作流程；
2. 定时任务：您可以设置定时任务以执行计划任务，例如备份数据或生成报告；
3. 自定义工作流程：您可以创建自己的工作流程来适应您的项目需求，并将多个工作流程链接在一起；
4. 持续集成和部署：GitHub Actions 可以自动构建、测试和部署应用程序；
5. 自动代码审核：您可以使用 GitHub Actions 自动运行代码质量分析工具、测试套件和其他工具，以确保代码符合最佳实践和标准；
6. 自动发布通知：您可以使用 GitHub Actions 发送通知到 Slack、电子邮件或其他通信平台，以通知您的团队关于新版本的发布和其他重要更新；
7. 自动化重复性任务：您可以使用 GitHub Actions 来自动执行重复性任务，例如打标签、打包和发布软件版本；
8. 与第三方服务集成：GitHub Actions 可以与许多第三方服务集成，例如 Amazon Web Services、Microsoft Azure、Google Cloud Platform、Docker 和 Kubernetes。

> GitHub Actions中的workflow是什么？GitHub Actions、workflow、Ruleset三者的关系是什么？

GitHub Actions 是一个持续集成和部署工具，它可以通过编写自定义的工作流程 (workflow) 来实现自动化测试、构建、打包和部署等任务，同时也支持自定义规则集 (Ruleset) 对工作流程进行进一步的控制和管理。

具体来说，workflow 是 Actions 的核心概念之一，表示一个由多个工作步骤 (job) 组成的自动化流程，可以在特定的事件 (例如 push、pull request 等) 触发时自动执行。每个工作步骤可以包含一个或多个任务 (action)，用于执行具体的操作，例如编译代码、运行测试、上传文件等。工作步骤还可以定义依赖关系、环境变量、运行条件等参数，以满足不同的需求。（我的理解就是类似于iOS的快捷指令、或者是自己编写的自动化脚本，将多个动作集成到一个脚本文件中，进行自动化执行。）

Ruleset 则是用于管理 workflow 的一种方式，它是一组自定义规则的集合，可以对工作流程的行为进行进一步的控制和限制。通过定义 Ruleset，可以指定哪些工作流程可以运行、哪些工作步骤需要跳过、哪些任务可以执行、哪些参数可以使用等等，从而实现对工作流程的精细化管理和控制。同时，Ruleset 还支持使用多种语言编写规则，例如 JavaScript、TypeScript、Python 等，方便用户根据实际情况进行自定义扩展。


>如果是新手，其实可以先不学GitHub Actions

初学者并且还没有涉及到需要使用 GitHub Action 和 workflow 的具体项目，那么在学习 GitHub 的基本用法之后，您可以先专注于学习项目管理、版本控制、团队协作等方面。但是，如果您在开发中需要自动化测试、持续集成、持续部署等方面的支持，那么学习 GitHub Action 和 workflow 会对您非常有帮助。

总之，GitHub Action 和 workflow 是 GitHub 提供的非常有用的功能，可以帮助您简化开发流程、提高开发效率和代码质量。因此，如果您的项目需要用到这些功能，或者您想进一步了解如何使用这些功能来提高开发效率，那么学习 GitHub Action 和 workflow 是非常有必要的。

