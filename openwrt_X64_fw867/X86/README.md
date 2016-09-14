koolshare openwrt X86  
===================================

## 固件特性

    1. 32位4.4.14内核，适用于不支持64位的处理器，或者intel atom,如N2600
    2. Intel自动省电降频，自动睿频，AES指令集加速，超线程支持
    3. 集成QCA、BCM、Intel主流pcl-e无线网卡，MTK RTL usb无线网卡驱动
    4. 默认advancedtomato主题，集成material、bootstrap满足个性化需求
    5. 集成常用软件：S^S、kcptun、广告过滤adbyby、Ngrok、pptp openvpn服务器、webshell、dnspod、wifidog、aria2、硬盘自动休眠、单wan多拨、多线负载均衡、策略路由。。。
    6. IPV6支持、石像鬼QOS

## 安装方法

    下载后使用winrar、7zip等解压缩，然后使用ImageWriter等工具直接将img写入U盘或者硬盘,squashfs版可在openwrt界面中直接升级。
    如果原来已经刷过openwrt系统，可将openwrt-x86-combined-ext4.img上传到tmp,然后使用命令： dd if=/tmp/openwrt-x86-combined-ext4.img of=/dev/sda写入。此命令将会清除原盘所有数据和分区，请注意备份。
    默认WEB 192.168.1.1 用户名 root 密码 koolshare
## 技术支持

BUG反馈：<http://koolshare.cn/forum-80-1.html>  （没有反馈就没有完善）   QQ交流群：103366563 <http://shang.qq.com/wpa/qunwpa?idkey=9689c491e45fdb982da6dd5dc7bb7c8dbeba427e358e289103b26fd43ca77ad0>

## 最近更新 2016-09-13
    89e3b192fb0c82629742166eccc4c1cc *openwrt-x86-generic-combined-ext4.img
    a87af93caf42ccc8c47f6d131586ce1a *openwrt-x86-generic-combined-squashfs.img





* 修复1.6 开机DNS问题等N多天坑，已经记不全了。。。
* 优化石像鬼、QOSv4、策略路由。。。等界面和脚本
* 增加miniDLAN、百度网盘同步，定时唤醒、全新aria2下载控制器
* aria2默认配置支持PT下载
* 家长管理使用本地时间，不再是UTC时间