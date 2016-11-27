### koolshare linksys_wrt1900ac_lede
===================================

## 固件特性
    0. linux 4.4.32内核
    1. 默认advancedtomato主题，集成material、bootstrap满足个性化需求
    2. 集成常用软件：S^S、kcptun、广告过滤adbyby、广告过滤koolproxy、Ngrok、pptp openvpn服务器、webshell、dnspod、aria2、硬盘自动休眠、单wan多拨、多线负载均衡、多ISP策略路由、USB打印服务器、家长管理、定时唤醒、百度网盘同步...
    3. 支持cpu，wifi温度显示；
    4. IPV6支持、石像鬼QOS

## 安装方法

    1.官方固件直接在web中上传对应机型的img后缀固件，刷机过程中路由器会自动重启。
    2.openwrt、lede固件上传sysupgrade.bin固件包，第一次刷写本固件请勿保留配置。
    3.如果之前刷写过本固件的V1.9-Update2版本，请开关路由三次，切换到另一个固件后上传img后缀固件进行刷写。
    默认WEB 192.168.1.1 用户名 root 密码 koolshare
## 技术支持

BUG反馈：<http://koolshare.cn/forum-80-1.html>     LEDE内测体验交流QQ群：103366563 <http://shang.qq.com/wpa/qunwpa?idkey=9689c491e45fdb982da6dd5dc7bb7c8dbeba427e358e289103b26fd43ca77ad0>

## 鸣谢
	* 感谢fw867大大提供源码
	* 感谢狂风邪影提供内核优化方案