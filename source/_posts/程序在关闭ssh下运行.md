---
title: 程序在关闭ssh下运行
date: 2016-11-08 20:55:50
tags: Technique
---
参考以下链接
http://wenku.baidu.com/link?url=df_aOas-Mc-wzcmMrumeJLbc8jPDJc1ATa60o9na07cT5ugOJ0cQ4fy7HCz4TBvSqvvYabivTJVmWpECBrZy3Nu5ecV4C2JoSGuHlrFCWiq
有两种方式
1.命令加nohup的方式太暴力了，不推荐
2.用screen的工具
ssh连接上服务器之后
screen 进入子页面
启动服务器
按下crtl+A+d返回主页面，可以exit退出ssh连接

下一次登入之后
screen -ls 可以看到子界面的代号
screen -r 子界面代码进入上一次的页面，可以进行服务器的维护
如：screen -r 19366.pts-3.hd12 
