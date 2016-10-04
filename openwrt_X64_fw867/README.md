koolshare openwrt X64  
===================================

## 固件特性

    1. 64位4.4.23内核，4G以上内存和多核心支持，多核NAT
    2. Intel自动省电降频，自动睿频，AES指令集加速，超线程支持
    3. 集成QCA、BCM、Intel主流pcl-e无线网卡，MTK RTL usb无线网卡驱动
    4. 默认advancedtomato主题，集成material、bootstrap满足个性化需求
    5. 集成常用软件：S^S、kcptun、广告过滤adbyby、Ngrok、pptp openvpn服务器、webshell、dnspod、wifidog、aria2、硬盘自动休眠、单wan多拨、多线负载均衡、多ISP策略路由、USB打印服务器、家长管理、miniDlna、定时唤醒、百度网盘同步。。。
    6. IPV6支持、石像鬼QOS

## 安装方法

    下载后使用winrar、7zip等解压缩，然后使用ImageWriter等工具直接将img写入U盘或者硬盘,squashfs版可在openwrt界面中直接升级。
    如果原来已经刷过openwrt系统，可将openwrt-x86-64-combined-ext4.img上传到tmp,然后使用命令： dd if=/tmp/openwrt-x86-64-combined-ext4.img of=/dev/sda写入。此命令将会清除原盘所有数据和分区，请注意备份。
    默认WEB 192.168.1.1 用户名 root 密码 koolshare
## 技术支持

BUG反馈：<http://koolshare.cn/forum-80-1.html>  （没有反馈就没有完善）   未来将转向LEDE,优先内测体验QQ交流群：103366563 <http://shang.qq.com/wpa/qunwpa?idkey=9689c491e45fdb982da6dd5dc7bb7c8dbeba427e358e289103b26fd43ca77ad0>

## 最近更新 2016-10-05
       de19f2e4e2247e4fd65e80583fccf950db3f62cdc5d583c0524473c3a38f06fc *lede-x86-64-combined-squashfs.img


* 主题配色及兼容性优化
* S*S增加负载均衡、自动更新规则、连接状态显示
* 修复QOS V4及石像鬼QOS设置后需要重启才生效的问题
* 全新流量监控，更加详细的数据显示
* 修复一些定时任务的错误
* 加强并发多拨
* 增加阿里ddns

## 从这个版本开始全面转向LEDE开发，原Openwrt不再更新。（LEDE T7以前的所有版本升级到1.8R1不可以保留配置或者升级完成后导入以前的配置）