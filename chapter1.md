# 第一章: 为树莓派安装系统

树莓派的官方为我们提供了几种树莓派的操作系统,访问[树莓派官网](https://www.raspberrypi.org/)的DOWNLOADS页面可以看到几个常用的系统.

## NOOBS
树莓派上用于管理多个操作系统的一个简单的软件,由于本人没有用到,就留给日后用到时介绍

## Raspbian
从名字可以看出,Raspbian是一个基于Debian的操作系统,我主要使用的就是这个版本的系统,它预装了很多常用的编辑器和编译器.以及,一些py小游戏

### Raspbian的安装
在官方下载ZIP压缩包以后使用Etcher写入SD卡镜像,插入树莓派后开机即可.要注意的是首次设置树莓派需要连接显示器,因为在官方某个版本后为了防止大量的树莓派设备被入侵,默认关闭了树莓派的SSH功能.如果没有显示器,就需要在开机前对系统文件进行修改,开启SSH后通过IP进行连接.  
需要注意的是,前代的树莓派可以通过串口登陆,而树莓派3由于有板载蓝牙的缘故,无法直接通过串口登陆,需要在禁用蓝牙后通过修改文件将串口通信启用  

## 树莓派的启动
在树莓派启动后,如果之前未修改过SSH配置,在图形配置界面将SSH开启.之后就可以通过PuTTY进行SSH连接.树莓派自带很多的IDE工具和编程学习工具.至此,树莓派系统的安装完成,可以开搞了!