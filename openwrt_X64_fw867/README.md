koolshare openwrt X64  
===================================

## 固件特性

    1. 64位4.4.14内核，4G以上内存和多核心支持，多核NAT
    2. Intel自动省电降频，自动睿频，AES指令集加速，超线程支持
    3. 集成QCA、BCM、Intel主流pcl-e无线网卡，MTK RTL usb无线网卡驱动
    4. 默认advancedtomato主题，集成material、bootstrap满足个性化需求
    5. 集成常用软件：S^S、kcptun、广告过滤adbyby、Ngrok、pptp openvpn服务器、webshell、dnspod、wifidog、aria2、硬盘自动休眠、单wan多拨、多线负载均衡、多ISP策略路由、USB打印服务器、家长管理、miniDlan、定时唤醒、百度网盘同步。。。
    6. IPV6支持、石像鬼QOS

## 安装方法

    下载后使用winrar、7zip等解压缩，然后使用ImageWriter等工具直接将img写入U盘或者硬盘,squashfs版可在openwrt界面中直接升级。
    如果原来已经刷过openwrt系统，可将openwrt-x86-64-combined-ext4.img上传到tmp,然后使用命令： dd if=/tmp/openwrt-x86-64-combined-ext4.img of=/dev/sda写入。此命令将会清除原盘所有数据和分区，请注意备份。
    默认WEB 192.168.1.1 用户名 root 密码 koolshare
## 技术支持

BUG反馈：<http://koolshare.cn/forum-80-1.html>  （没有反馈就没有完善）   未来将转向LEDE,优先内测体验QQ交流群：103366563 <http://shang.qq.com/wpa/qunwpa?idkey=9689c491e45fdb982da6dd5dc7bb7c8dbeba427e358e289103b26fd43ca77ad0>

## 最近更新 2016-09-13
    a75038ac4d15c7101ebf4f64278102dc *openwrt-x86-64-combined-ext4.img
    5436aed405a395e022f0a143caaa3c43 *openwrt-x86-64-combined-ext4.vmdk
    636476ebbbd9929266e668cc64382d6d *openwrt-x86-64-combined-squashfs.img




* 修复1.6 开机DNS问题等N多天坑，已经记不全了。。。
* 优化石像鬼、QOSv4、策略路由。。。等界面和脚本
* 增加miniDLAN、百度网盘同步，定时唤醒、全新aria2下载控制器
* aria2默认配置支持PT下载
* 家长管理使用本地时间，不再是UTC时间