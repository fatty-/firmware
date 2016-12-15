koolshare Lede X64 Nuc  
===================================

## 固件特性

    1. 64位4.4.36内核，4G以上内存和多核心支持，多核NAT
    2. Intel自动省电降频，自动睿频，AES指令集加速，超线程支持
    3. 集成MTK RTL usb无线网卡驱动
    4. 默认advancedtomato主题，集成material、bootstrap满足个性化需求
    5. 集成常用软件：S^S、kcptun、广告过滤koolproxy、adbyby、Ngrok、SoftEthervpn、webshell、dnspod、aliddns、cloudxns、aria2、硬盘自动休眠、单wan多拨、多线负载均衡、多ISP策略路由、USB打印服务器、家长管理、miniDlna、定时唤醒、百度网盘同步、行为控制。。。
    6. IPV6支持、石像鬼QOS

## 安装方法

    下载后可直接在LEDE WEB升级。也可解压缩后使用ImageWriter等工具直接将img写入U盘或者硬盘。
    如果原来已经刷过openwrt系统，可将openwrt-x86-64-combined-ext4.img上传到tmp,然后使用命令： dd if=/tmp/openwrt-x86-64-combined-ext4.img of=/dev/sda写入。此命令将会清除原盘所有数据和分区，请注意备份。
    默认WEB 192.168.1.1 用户名 root 密码 koolshare
## 技术支持

BUG反馈：<http://koolshare.cn/forum-80-1.html>     LEDE内测体验交流QQ群：103366563 <http://shang.qq.com/wpa/qunwpa?idkey=9689c491e45fdb982da6dd5dc7bb7c8dbeba427e358e289103b26fd43ca77ad0>

## 最近更新 2016-12-09
    sha256sums:
    9189812e4d6899757190d1f93a00f0dab30c4946d425bfc4c88d8863b7136f0f *lede-V1.9-Update4-x86-64-combined-squashfs.img.gz
* 升级内核到4.4.36
* dnspod、cloudxns、aliddns合并为koolddns,支持无限子域名和主域名同步，aliddns改用https传输数据。
* root分区调整为512M
* 修复bugs
----------------------------------
* 1.9可以保留配置直接web升级到最新版本，建议先备份配置。
* Nuc点击菜单：系统-进阶设置-模式切换-nuc模式