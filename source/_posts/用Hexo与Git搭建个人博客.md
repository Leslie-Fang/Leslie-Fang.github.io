---
title: 用Hexo与Git搭建个人博客
date: 2016-11-02 13:50:24
tags: Technique
---
## 教程
本实践教程讲述如何利用hexo与git进行个人博客的搭建

### 配置

在这里我已经在ubuntu下面配置好了git以及nodejs
在ubuntu14.04下的hexo的安装参考：
[参考1](http://www.jianshu.com/p/465830080ea9)
[参考2](https://www.npmjs.com/package/hexo)
主要需要在_config.xml 里面配置和github的仓库关联
git的设置主要是需要创建特定名字的仓库：我的github的账号+git+io

### 新建文章

可以hexo new 文章名字 一篇文章
post:标题属性可以配置
正文用markdown的语法去书写正文

### 生成以及部署

之后需要 hexo generate重新生成一下
然后hexo deploy部署到github
之后不需要启动hexo的本地服务器就可以在浏览器直接输入
https://仓库名/
来访问我的博客
