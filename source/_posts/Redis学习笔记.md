---
title: Redis学习笔记
date: 2016-11-16 23:42:08
tags: Technique
---

## 用Redis的动机
本来想为网站添加一个统计同时在线人数的功能：）并不是因为网站用户太多，需要改善性能
觉得这些数据没有必要放在关系型数据库里，所以就放在内存里好了
内存数据库这些年来越来越火SAP的HANA是一个，Redis开源免费，所以为什么不是它哪？

## 使用教程
当然，首先是要安装Redis，可以装在本机也可以用远程服务器上的，都是有办法连接的
然后第二步是在node里面添加redis的模块调用模块提供的一些方法，在redis的数据库里面添加修改数据
这个你至少要对redis常用的一些数据类型数据结构有点了解吧，姿势补起来
第三步最后就是根据具体的需要来使用这些数据了

<!--more-->

## 参考资料
Redis包含的数据类型可以参考：
官网：http://redis.io/
当然也有中文教程
http://www.redis.cn/
中文入门菜鸟教程
http://www.runoob.com/redis/redis-conf.html

node里面redis模块的API:
https://github.com/NodeRedis/node_redis

也有一些实战的教程：
https://www.sitepoint.com/using-redis-node-js/
http://blog.csdn.net/billfeller/article/details/40960613
http://zhanfang.github.io/2015/05/04/redis%E7%BB%9F%E8%AE%A1express%E5%9C%A8%E7%BA%BF%E4%BA%BA%E6%95%B0/
