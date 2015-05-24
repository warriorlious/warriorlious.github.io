---
layout: post
title: JennyPrinter2.4
category: 开发版
tags: [JP2]
keywords: JennyPrinter
description: JennyPrinter2.4 开发版本
---
一台机器使用Windows和Linux一般有以下几个方式：

- Windows和Linux真正的双系统，开机两个引导
- Linux下虚拟Windows（一般是xp）
- Windows下虚拟Linux

除了以上几个，还有一些其他方法，都没啥映像，在此不讨论。

选择两个系统无非是因为工作原因，Linux下开发，Windows下娱乐或者Word等。出现这种矛盾实在是纠结，在尝试过上述三种方案以后，我选择了在Windows下虚拟一个Linux，原因如下：

- 使用Vmware虚拟实在是比Virtual Box好用（主要是功能）
- Windows下的软件体验真的不错，而且是越来越好。虽然Linux下有各种开源软件功能一点都不差，但是你无法逃避的现实就是，用户体验真的不够。
- 双系统经常切换非常麻烦
- Windows系统问题，虚拟出来的真的不好用
- Linux真正需要的，字符界面就够用，所以一般不需要占太大资源

根据这几点，结果就定了，那么Windows下虚拟Linux怎样做最好呢?

## 配置

1. 安装vmware
    安装过程不多说，提醒一点就是，记得在配置中设置，关闭vmware后不关闭运行的虚拟机，原因待会说。
2. 安装ubuntu server 
