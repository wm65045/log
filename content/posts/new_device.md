---
title: "新设备"
date: 2022-04-27T21:40:44+08:00
tags: ""
weight:
---

记录，换了**新的设备**之后，需要做的事情。

目的是，随时拿到一个新的设备之后，怎么**快速恢复**自己的工作学习环境

## ubuntu20.04

2021年12月开始日常使用

软件

+ vscode github绑定，自动同步
+ xournal++ [github](https://github.com/xournalpp/xournalpp) ，wacom手写板直接可用笔锋，pdf标注会另外生成一个标注文件，不会直接在原pdf上标记
+ microsoft edge 微软账号，自动同步
+ chrome 谷歌账号，自动同步
+ 坚果云
+ 火焰截图flameshot [github](https://github.com/flameshot-org/flameshot)
+ pinta 修图软件，缺点是对4K屏适配不好
+ 茄子cheese  摄像头软件
+ git-cola ，git的gui软件
+ SMplayer，播放器
+ mpv播放器
+ 搜狗拼音输入法，根据官网的安装指导安装就行
+ WPS，替代office软件
+ 节能模式设置,cpu软件indicator-cpufreq，cpu软件cpufrequtils，电池工具tlp， [csdn](https://blog.csdn.net/lzp_k2/article/details/97272282)

硬件

+ 博通网卡驱动
+ 博通蓝牙驱动
+ nvidia显卡驱动
+ wacom驱动 [github-最好直接用命令行安装，不要自己编译](https://github.com/linuxwacom/xf86-input-wacom/wiki/Building-The-Driver)

系统设置

+ 文件路径必须为`英文`，保留文件名为`Documents` `Downloads`等
+ zsh
+ power10k
+ nerd字体

## windwos

浏览器

## 配置

+ git匿名邮箱
 
 ```
 git config --global user.name "usernameeeee"

git config --global user.email "ID+username@users.noreply.github.com”


```