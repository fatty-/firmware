## R6300V2_380.62_X7.1.trx
 * * *
##### File: R6300V2_380.62_X7.1.trx
##### Size: 28479488 bytes
##### Modified: 2016年9月30日, 星期五, 13:51:12
##### MD5: 813CD4522AC03A90CCA86B43B5A96DC3
##### SHA1: 316FEC4DCD215A7C31B6763AD7A3182EE8923293
##### CRC32: FBC2455A
* * *
## 插播广告：发固件，庆国庆，改版固件讨论qq群开群3天：438983449
* * *
### 说明
基于最新380.62编译，相关日志请参阅merlin。
SS取消固化，移除webshell，因为我们已经有了更好的shell插件。
得益于以上改进，非华硕机型MTD固件空间恢复32M。带来的好处就是无需再刷64M固件空间的特制固件就能直接刷入koolshare固件，而且JFFS可用空间接近90M。
###### `刷机前备份设置，刷完请清空JFFS，否则不可用！`
###### `刷机前备份设置，刷完请清空JFFS，否则不可用！`
###### `刷机前备份设置，刷完请清空JFFS，否则不可用！`

### 刷机须知：
* 刷机有风险，刷机前请做好准备，如果刷机变砖，华硕机型可以使用救援模式救砖，网件机型可以使用[http://koolshare.cn/thread-63587-1-1.html](http://koolshare.cn/thread-63587-1-1.html)此贴的方法救砖；
* 刷机后一定格式化一次jffs分区，进入[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面，勾选Format JFFS partition at next boot，然后点击应用本页面设置，待设置保存后，重启路由器；
* 格式化jffs分区后请确保[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面的 Enable JFFS custom scripts and configs勾选是.
* 刷机后强烈建议恢复出厂设置一次，恢复后请手动配置各个项目，不要用以前的配置备份来恢复，可以避免很多小问题，比如无线功率调节问题

* 此版本超频命令（频率根据实际情况设置）：
###### `nvram set clkfreq=1200,800`
###### `nvram commit`
###### `reboot`


