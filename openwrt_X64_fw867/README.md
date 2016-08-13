koolshare openwrt X64  
===================================

## 固件特性

    1. 64位4.4.14内核，4G以上内存和多核心支持
    2. Intel自动省电降频，自动睿频，AES指令集加速，超线程支持
    3. 集成QCA、BCM、Intel主流pcl-e无线网卡，MTK RTL usb无线网卡驱动
    4. 默认advancedtomato主题，集成material、bootstrap满足个性化需求
    5. 集成常用软件：S^S、kcptun、广告过滤adbyby、Ngrok、pptp openvpn服务器、webshell、dnspod、wifidog、aria2、硬盘自动休眠、单wan多拨、多线负载均衡、策略路由。。。
    6. IPV6支持、石像鬼QOS

## 安装方法

    下载后使用winrar、7zip等解压缩，然后使用ImageWriter等工具直接将img写入U盘或者硬盘
    如果原来已经刷过openwrt系统，可将openwrt-x86-64-combined-ext4.img上传到tmp,然后使用命令： dd if=/tmp/openwrt-x86-64-combined-ext4.img of=/dev/sda写入。此命令将会清除原盘所有数据和分区，请注意备份。

## 技术支持

论坛链接：<http://www.koolshare.cn> 

## 最近更新 2016-08-13

* 加入更多网卡支持，虚拟机支持
* md5sum caa82a35d3bf663c4e3f1793f3a307de