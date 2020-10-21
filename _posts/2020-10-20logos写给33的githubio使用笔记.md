---
layout: post
title: logos写给33的githubio使用笔记
date: 2020-10-20
categories: essay
tags: [随笔]
description: 超详细，听一遍就学会了w
---



# 写给33的github.io使用笔记  

其实整个网站就是一个project，保存在github上面
你可以先下载一个github desktop(推荐），登录自己的账号，把github上这个project（github
上叫repositories）下载到本地
github desktop下载地址：https://desktop.github.com/
所以如果你要改变网站的内容，你要做的事情是，先在本地改变内容（比如修改博文），然后把
修改的内容推到github上（用github desktop就可以完成)
然后这个网站长啥样呢，就长这样



其中_post放的是你的博文，about放的是左边的那个关于，_config.yml放的是网站的一系列设置
关于_config.yml中的各种configuration，可以参考
https://jekyllrb.com/docs/configuration/和注释
博文要如何撰写呢？需要有一定的格式，所以你需要熟悉一下markdown语法来写东西，这里推
荐Typora软件来写markdown文档，你可以看到博文的后缀是md，这就代表这是一个
markdown文档



markdown入门指南：https://www.jianshu.com/p/q81RER
其实你平时写markdown文档随便写就好，但是如果你要传上网站的话，就必须有这个header



可以看看 2020-10-20-firstblog.md 是如何在网站中展现内容的
然后下面就可以用markdown语法来写东西啦，markdown语法是很简单的，随便学一下就会的
了，而且你用typora的话是有可视化界面让你去编辑的。
写完东西，也就是修改了网站的内容，这个时候先在github desktop这里commit。



commit之后就代表在本地确认了修改内容，但是这时候还没传上服务器



再在这里push上去， 再过几分钟，网站的内容就有变化啦。  






