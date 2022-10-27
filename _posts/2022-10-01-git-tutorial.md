---
title: 'How to use Git'
date: 2022-10-01
permalink: /posts/2022/10/git-tutorial/
tags:
  - software
  - git
  - tutorial
---

[保姆级Git入门教程，万字详解](https://cloud.tencent.com/developer/article/1885681)

首先要明确一点，对git的操作是围绕3个大的步骤来展开的

- 1. 从git取数据（git clone）

- 2. 改动代码

- 3. 将改动传回git（git push）

这3个步骤又涉及到两个repository，一个是remote repository，再远程服务器上，一个是local repository，再自己工作区上。

- master 这个很好理解，它代表本地的某个分支名，你运行 git init 时本地默认的起始分支名字
- origin 在clone完成之后，Git 会自动为你将此远程仓库命名为origin（origin只相当于一个别名，运行git remote –v 或者查看.git/config可以看到origin具体指代的仓库地址). 详细解释可以参考：https://www.zhihu.com/question/27712995
- origin/master：是当本地的 master 分支同步到服务时的名字，如果分支名称为 name、当分支同步到服务器时、会看到服务器上的名字为 origin/name。也可以表示从远程拉取代码后在本地建立的一份拷贝（因此也有人把它叫作本地分支）
- origin master 代表着两个仓库，前面的 origin 代表远程名，后面的 master 代表远程分支名


