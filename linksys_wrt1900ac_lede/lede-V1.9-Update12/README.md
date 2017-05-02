### koolshare linksys_wrt1900ac_lede
===================================

## 固件特性（1.9-update12）：
1.9-update12
    0. linux 4.9.20内核
    1. 默认advancedtomato主题
    2. 集成常用软件：koolss、kcptun、koolproxy、webshell、koolddns、aria2、tranmision，netdata等
    3. 支持cpu，wifi温度显示；
    4. IPV6支持、石像鬼QOS

1.9-update12.1：
    1. 更改默认时区为东八区
    2. 修复ddnspod不能更新ip
    3. luci添加ssl支持
    4. 增加LED配置
    5. 删除多的USB打印服务
    6. 添加samba支持

1.9-update12.2：
    1. 增加upnp支持
    2. 增加硬盘休眠
    3. 增加ngrok穿透
    4. 修复cloudxdns
    5. 无线驱动更新到mwlwifi-10.3.4.0-20170421


## 安装方法
    1.官方固件直接在web中上传对应机型的img后缀固件，刷机过程中路由器会自动重启。
    2.openwrt、lede固件上传sysupgrade.bin固件包，第一次刷写本固件请勿保留配置。
    3.1.9-Update4升级到1.9-Update12建议不保留配置升级
    4.如果之前刷写过本固件的V1.9-Update2版本，请开关路由三次，切换到另一个固件后上传img后缀固件进行刷写。
    默认WEB 192.168.1.1 用户名 root 密码 koolshare
## 技术支持

BUG反馈：<http://koolshare.cn/forum-80-1.html>     LEDE内测体验交流QQ群：103366563 <http://shang.qq.com/wpa/qunwpa?idkey=9689c491e45fdb982da6dd5dc7bb7c8dbeba427e358e289103b26fd43ca77ad0>

## 鸣谢
	* 感谢fw867大大提供源码