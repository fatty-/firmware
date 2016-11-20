koolshare Lede X64 Nuc  
===================================

## 固件特性

    1. 64位4.4.30内核，4G以上内存和多核心支持，多核NAT
    2. Intel自动省电降频，自动睿频，AES指令集加速，超线程支持
    3. 集成MTK RTL usb无线网卡驱动
    4. 默认advancedtomato主题，集成material、bootstrap满足个性化需求
    5. 集成常用软件：S^S、kcptun、广告过滤adbyby、Ngrok、pptp openvpn服务器、webshell、dnspod、wifidog、aria2、硬盘自动休眠、单wan多拨、多线负载均衡、多ISP策略路由、USB打印服务器、家长管理、miniDlna、定时唤醒、百度网盘同步。。。
    6. IPV6支持、石像鬼QOS

## 安装方法

    下载后使用winrar、7zip等解压缩，然后使用ImageWriter等工具直接将img写入U盘或者硬盘,squashfs版可在openwrt界面中直接升级。
    如果原来已经刷过openwrt系统，可将openwrt-x86-64-combined-ext4.img上传到tmp,然后使用命令： dd if=/tmp/openwrt-x86-64-combined-ext4.img of=/dev/sda写入。此命令将会清除原盘所有数据和分区，请注意备份。
    默认WEB 192.168.1.1 用户名 root 密码 koolshare
## 技术支持

BUG反馈：<http://koolshare.cn/forum-80-1.html>  （没有反馈就没有完善）   LEDE内测体验交流QQ群：103366563 <http://shang.qq.com/wpa/qunwpa?idkey=9689c491e45fdb982da6dd5dc7bb7c8dbeba427e358e289103b26fd43ca77ad0>

## 最近更新 2016-11-10
    sha256sums:
    2552df8c4b29a6ebd022566aa3e7fcf3291e0ae082d0ccf90d501f3ae807da18 *lede-X64.1.9-Update1-x86-64-combined-squashfs.img.gz


    1.增加行为管理应用-访问限制、上网记录、网址过滤（完成度50%）
    2.升级koolproxy,现在程序自带守护
    3.重新加入pptp服务器
    4.修复kcptun-plus、百度网盘同步
    5.界面调整
    6.其它bug修复
    7.去掉https强制跳转
----------------------------------
* 1.9可以直接web升级到本版本
* Nuc进去luci后点击菜单：系统-进阶设置-模式切换-nuc模式