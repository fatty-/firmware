## R7000_380.61-X7.0.trx
 
##### File: R7000_380.61_X7.0.trx
##### Size: 
##### Modified: 
##### MD5: 
##### SHA1: 
##### CRC32: 

* * *
从7.0版本固件开始，网件机型的代码会跟随Votex的代码

需要说明的是，华硕在最近的官方固件中，加入了固件校验机制，并且刷写了最新华硕固件和merlin固件的朋友，不能通过web进行降级；
不过Votex大神再代码上做了破解，绕过了这个机制，所以此次7.0改版固件将不存在这个问题，刷了7.0的能轻松的在web页面上降级6.6，5.6等版本。
### 更新日志(R7000)：
1. 在7.0基础上，修复无线专业设置页面不可用问题
2. 在7.0基础上，修复V大固件功率调节无效的bug，附送`merlin改版固件X7.0无线功率对照表.xlsx`
3. 在7.0基础上，修复单线双拨无效问题（并且去掉以前的并发双拨，现在是非并发方式）
4. 版本号保持不变，其它机型7.0默认修复以上问题

### 刷机须知：
* 刷机有风险，刷机前请做好准备，如果刷机变砖，华硕机型可以使用救援模式救砖，网件机型可以使用[http://koolshare.cn/thread-63587-1-1.html](http://koolshare.cn/thread-63587-1-1.html)此贴的方法救砖；
* 刷机后一定格式化一次jffs分区，进入[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面，勾选Format JFFS partition at next boot，然后点击应用本页面设置，待设置保存后，重启路由器；
* 格式化jffs分区后请确保[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面的 Enable JFFS custom scripts and configs勾选是.
* 刷机后强烈建议恢复出厂设置一次，恢复后请手动配置各个项目，不要用以前的配置备份来恢复，可以避免很多小问题，比如无线功率调节问题

* 此版本超频命令（频率根据实际情况设置）：
###### nvram set clkfreq=1200,800
###### nvram commit
###### reboot



