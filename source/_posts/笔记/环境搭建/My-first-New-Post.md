---
title: hexo个人博客初步搭成
tags:
  - hexo
  - 技术
  - 博客
  - 笔记
categories:
  - 笔记
  - 环境搭建
date: 2017-02-18 00:00:00
---
参考:[hexo搭建较好的博客](https://www.jianshu.com/p/76ce3729746d)
[leancloud](https://leancloud.cn/dashboard/applist.html#/apps)
[博主](http://tc9011.com/tags/Hexo/)
去年在一个偶然的情况下发现同学QQ的主页竟然有点不同，画风如此简洁，于是就调研了一下，原来是自己在GitHub上部署的一个静态博客，但是基于时间问题和严重的拖延症就拖到了现在。折腾了一段时间，终于有点小成果了。哦，我那位同学主页： [一位前端妹子](http://blog.oulafen.com/ )。
<!-- more -->
### 对hexo的理解
搭建的过程中确实遇到了不少问题，虽然网上有不少优秀的博客作指导，但是由于对hexo搭建博客原理的理解不够，导致搭建的整个过程都很折腾。
总结一下，hexo是基于node.js的一个静态博客的平台，所以我们首先要安装node.js，然后在通过node.js 安装hexo的Module。之后，就是hexo的一些基本操作，生成静态网页，这里我们可以通过本地部署查看效果。如果本地没有什么问题的话，接下来就是将本地的静态网页部署到GitHub上了。注意：是将hexo生成的静态网页部署在与GitHub账号同名的仓库的master分支中，hexo本身的文件可以放在另一个分支，也可以放在另一个仓库。
### 一路走来遇到的坑

#### 问题1：如果不了解，不怎么了解 node.js ，使用node.js安装Module的时候遇到的问题会不知所以然。

#### 问题2：hexo安装成功，并且正确运行，但是localhost:4000不能访问。
启动hexo s 的时候，用这个命令，换一个端口。

### 问题3：ssh的连通性测试出现问题
这里，我刚开始用的是GitHub，然后根据网上的各种博客，看得我有点凌乱，安装git和GitHub的处理情况好像有点一样。

### 哦，还有部署到GitHub上master和分支的处理问题

[这篇博客有点帮助](https://www.zhihu.com/question/21193762)


## 折腾过程中，查阅的博客中比较好的几篇
[HEXO进阶](http://baixin.io/2016/06/HEXO_Advanced/)
[中文教程](https://hexo.io/zh-cn/docs/index.html)
[Config.yml 的配置](http://blog.csdn.net/xuezhisdc/article/details/53130383)
[使用Hexo搭建个人博客(基于hexo3.0)](http://opiece.me/2015/04/09/hexo-guide/)

### 比较喜欢的主题，还没有配置上，日后有空再换
[Maupassant](https://github.com/tufu9441/maupassant-hexo/)
[例子](https://www.haomwei.com/)