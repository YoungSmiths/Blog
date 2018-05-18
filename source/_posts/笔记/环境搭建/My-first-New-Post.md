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
去年在一个偶然的情况下发现同学QQ的主页竟然有点不同，画风如此简洁，于是就调研了一下，原来是自己在GitHub上部署的一个静态博客，但是基于时间问题和严重的拖延症就拖到了现在。折腾了一段时间，终于有点小成果了。
哦，我那位同学主页： [一位前端妹子](http://blog.oulafen.com/ )。
<!-- more -->
## 常用命令
- hexo new "postName" #新建文章
- hexo new page "pageName" #新建页面
- hexo generate #生成静态页面至public目录
- hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
- hexo deploy #将.deploy目录部署到GitHub
- hexo help  # 查看帮助
- hexo version  #查看Hexo的版本

## 简写
```
hexo n == hexo new
hexo g == hexo generate
hexo s == hexo server
hexo d == hexo deploy
hexo clean && hexo g && hexo s
```


参考博客:
- [hexo搭建较好的博客](https://www.jianshu.com/p/76ce3729746d)
- [leancloud](https://leancloud.cn/dashboard/applist.html#/apps)
- [这篇博客有点帮助](https://www.zhihu.com/question/21193762)
- [博主](http://tc9011.com/tags/Hexo/)
- [HEXO进阶](http://baixin.io/2016/06/HEXO_Advanced/)
- [中文教程](https://hexo.io/zh-cn/docs/index.html)
- [Config.yml 的配置](http://blog.csdn.net/xuezhisdc/article/details/53130383)
- [使用Hexo搭建个人博客(基于hexo3.0)](http://opiece.me/2015/04/09/hexo-guide/)

