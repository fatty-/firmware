koolshare Lede X64 Nuc  
===================================

## 固件特性

    1. 64位4.9.14内核，4G以上内存和多核心支持，多核NAT
    2. Intel自动省电降频，自动睿频，AES指令集加速，超线程支持
    3. 集成MTK RTL usb无线网卡驱动
    4. 默认advancedtomato主题，集成material、bootstrap满足个性化需求
    5. 集成常用软件：S^S、kcptun、广告过滤koolproxy、adbyby、Ngrok、SoftEthervpn、webshell、dnspod、aliddns、cloudxns、aria2、硬盘自动休眠、单wan多拨、多线负载均衡、多ISP策略路由、USB打印服务器、家长管理、miniDlna、定时唤醒、百度网盘同步、行为控制。。。
    6. IPV6支持、石像鬼QOS

## 安装方法

    下载后可直接在LEDE WEB升级。也可解压缩后使用ImageWriter等工具直接将img写入U盘或者硬盘。
    如果原来已经刷过openwrt系统，可将Lede-*.img上传到tmp,然后使用命令： dd if=/tmp/Lede-*.img of=/dev/sda写入。此命令将会清除原盘所有数据和分区，请注意备份。
    默认WEB 192.168.1.1 用户名 root 密码 koolshare
## 技术支持

BUG反馈：<http://koolshare.cn/forum-97-1.html>     LEDE内测体验交流QQ群：103366563 <http://shang.qq.com/wpa/qunwpa?idkey=9689c491e45fdb982da6dd5dc7bb7c8dbeba427e358e289103b26fd43ca77ad0>

## 最近更新 2017-03-13
    sha256sums:
    f9d02d4120d3d6fb3a6e079bda93ea31cca18bcf8974faf8c7f5e4425f0f352c *lede-v1.9-update9-r4053-54e64d8-x86-64-combined-squashfs.img

* 升级内核到4.9.14
* 增加一些声卡驱动，文件管理器
* 修复s*s识别错误的问题
* 修复重置按钮报错的问题
* 修复aria2设置问题
----------------------------------
* 1.9可以保留配置直接web升级到最新版本，建议先备份配置。
* 如需要写盘或者转虚拟盘请使用update4,然后再升级到最新版本。
* Nuc点击菜单：系统-进阶设置-模式切换-nuc模式