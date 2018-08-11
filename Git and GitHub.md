# 教程1：git和GitHub

## 我们要解决什么问题？

0基础的小伙伴可能并不清楚为什么开发者都在使用git这种版本控制系统。在这里，我们使用最少的文字向大家讲解最基本的概念。

在一个多人合作项目中，针对同一个文件，会出现多个人同时修改同一个文件的情况。对于普通的文本文档还好，而修改代码时，两个人修改的内容就会起冲突。另外，就算是个人项目，比如你在写论文，可能会出现你创造了很多个版本之后，突然觉得过去的某个版本更好，或者想要比较一下和过去某个版本之间自己修改了什么。

这就是git应运而生的需求。而在此之上，GitHub提供了一个GUI界面（即不再是命令行，而是你可以点点点就搞定任务的界面），github.com提供了一个你可以提交代码（或者你的论文，任何东西都可以）的仓库。而我们的开发，就在github.com提供的代码仓库中进行。

因此，使用git进行多人协作（或者自己工作）时，流程是：github.com上存放的是某个你觉得已经阶段性完成的版本（比如说，你的论文完成了第一章，或者你的程序即将开始一次大改），你接下来想要修改，先从github.com上pull你的repository（意思是，通过git下载你存储在github.com上的代码到你的本机），然后随意修改你的代码（或者论文，任何东西），然后使用git确认你的修改，然后再次push（即上传）到github.com这个仓库。这样，你的文件内容就更新了。

我们最推荐的是使用git命令行，然而对于0基础小白，看见命令行就头大我也很清楚。因此我仅介绍GitHub网站的使用。

### 参考教程

git: https://guides.github.com/introduction/git-handbook/
GitHub: https://guides.github.com/activities/hello-world/

希望新手在熟悉GitHub后尽快过渡到使用git命令行。

### GitHub

#### 新建你自己的repository

先进入我们的项目网址：https://github.com/jihezhi
然后单击右上角的New：

![New](https://files.gitter.im/jihezhi/Lobby/ptny/image.png "New")

然后在框里输入你的repository的名字（英文）：

![Create repository](https://files.gitter.im/jihezhi/Lobby/LGhl/image.png "Create repository")

将下面的Initialize this repository with a README打上勾。

然后单击Create repository。

### 修改你的README

单击你的README.md，然后单击右侧的小铅笔图标即可开始修改。

修改完毕后，单击下面的Commit changes按钮即可提交。

![Readme](https://guides.github.com/activities/hello-world/commit.png)

### 新建/上传你的文件

在你的repository页面中，单击右侧的Create new file以新建文件，或者Upload files来上传文件（比如你的go程序源代码）。

![New](https://files.gitter.im/jihezhi/Lobby/i4Dj/image.png)

这样一来你就可以开始使用GitHub提交你的代码了。你可以十分随意地提交代码，提交带来的影响很小，你的半成品都可以随意提交，你可以将其理解成同步内容。

各位开始提交自己的代码吧！0基础的新手也可以尝试提交一些简单的HTML或者go程序，尝试一下GitHub的功能吧！
