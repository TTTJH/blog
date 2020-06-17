---
title: linux记录
date: 2020-03-16 18:59:02
index_img: /img/linux_logo.jpg
tags:
---
# deepin美化记录
<iframe width='100%' height='400px' src="//player.bilibili.com/player.html?aid=92947592&cid=158680564&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

# deepin使用技巧
	* ctrl + 滚轮　提高终端透明度使得看到下层内容
	* 截图后大量以往截图中快速找到方才的截图
	* 右上角的矩形通知使用右键快速关闭
	* 终端上可以进行远程控制管理
# linux命令行连接wifi
* 参考博客 [博客1](https://linux.cn/article-9269-1.html?pr)  [博客2](https://www.jianshu.com/p/82b20e72f853)
* ifconfig查看网卡名称
* ifconfig 网卡名 up   点亮网卡
* iw 网卡名称 scan  搜索wifi
* wpa_passphrase wifi名称 密码 >> /etc/wpa_supplicant/wpa_supplicant.conf   写入wifi配置文件
* wpa_supplicant -i 网卡名称 -c /etc/wpa_supplicant/wpa_supplicant.conf -B  根据配置文件连接wifi
* dhclient 网卡名称 为网卡分配ip

