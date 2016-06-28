### OpenWrt Nemo 集成版固件 1.4

此版本主要移除了 ChinaDNS，采用 crwnet 的 Shadowsocks 方案

### 新增内容

* 无线驱动采用 10.3.0.17-20160523（不是最新的，但 5G 相对稳定）
* 移除了 ChinaDNS，采用 crwnet 制作的 [Shadowsocks](https://github.com/crwnet/openwrt-15.05/tree/master/package/crwsoft/luci-app-shadowsocks)
* 新增 adbyby 一键安装脚本，luci 同样来自 crwnet

### 关于 Adbyby

Adbyby 是一款优秀的广告过滤软件。但它并不是一款开源软件。之前的版本没有加入，一方面因为我本人对于广告过滤没有什么需求，另外一方面，它不开源，也不符合这个固件的定位。但是长期以来，需要的朋友很多，所以应求在这个版本里加入了安装脚本。固件本身不集成此软件，请有需要的朋友自行判断是否安装。

安装方法：进入菜单栏的 “系统 - 自定义命令”，点击运行 Install Adbyby。等待一会，出现提示就安装成功了。

### 简介

这是一个基于 OpenWrt 稳定 Release 版本，针对 Linksys WRT1900AC v1、WRT1900AC v2、WRT1900ACS 以及 WRT1200AC 制作的集成固件。秉承保留 OpenWrt 自由开放原态的理念，不做大而全，只集成可靠的开源软件，稳定是第一目标。
因为是基于官方编译的打包，所以完全可以使用官方软件源，内置包管理已经替换成速度很好的国内镜像，安装软件非常方便。
希望可以为中级以上水平的 Linux 使用者提供一个良好的折腾系统的基础，同时也能给不喜欢折腾的朋友提供一个比较完善的 OpenWrt。

### 集成内容

基于 OpenWrt Chaos Calmer 15.05.1 正式版

中文界面

无线驱动（mwlwifi）使用 10.3.0.17-20160523

默认软件源替换为中科大 opkg 源

ShadowVPN、Shadowsock

自动挂载：block-mount

文件系统：Ext4、exFAT、HFS+

文件分享：Samba、DLNA

BT 下载：Transmission

文件下载：aria2 1.21.0（支持 BT）、wget-full

UPNP

DDNS

SMQ QoS

自定义命令：luci-app-commands

主题风格：luci-theme-material

Vim: vim-full

### 如何升级

从 1.3 版升级，建议不保留配置。


### 注意事项
请仔细观察文件名，选择对应的版本，选错有可能会变砖。路由器代号：

WRT1900AC v1 : mamba

WRT1900AC v2 / WRT1900ACS : cobra

WRT1200AC : caiman

WRT1900ACS : shelby

从原版固件更新到 Openwrt 使用 factory.img；从 Openwrt 刷到 Openwrt 使用 sysupgrade.tar。请使用有线连接路由器来刷系统，否则会有极大的可能性变砖！

[讨论帖](http://koolshare.cn/thread-50350-1-1.html)