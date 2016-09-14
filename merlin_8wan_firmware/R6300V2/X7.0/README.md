## R6300V2_380.61_X7.0.trx
#### 
 
##### File: R6300V2_380.61_X7.0.trx
##### Size: 
##### Modified: 
##### MD5: 
##### SHA1: 
##### CRC32: 

* * *
### 说明
从7.0版本固件开始，网件机型的代码会跟随Votex的代码

需要说明的是，华硕在最近的官方固件中，加入了固件校验机制，并且刷写了最新华硕固件和merlin固件的朋友，不能通过web进行降级；
不过Votex大神再代码上做了破解，绕过了这个机制，所以此次7.0改版固件将不存在这个问题，刷了7.0的能轻松的在web页面上降级6.6，5.6等版本。
### 更新日志(RT-AC68U)：
1. 固件本身的更新日志，主要参考Votex更新日志，固件版本号基于merlin 380.61
2. 和华硕机型不同的是，网件固件侧边栏的一级菜单精简了不少内容，因为这些都是华硕提供的相关服务，我们遵循Vetox的做法，使用了精简的样子~毕竟华硕才是亲儿子嘛~
3. 合并了koolshare坛友thesadboy的修改梅林首页增加部分系统信息页面，[http://koolshare.cn/thread-61065-1-1.html](http://koolshare.cn/thread-61065-1-1.html)，在此感谢thesadboy
4. 修复了httpd文件上传的一个bug，修复后webshell上传文件和软件中心离线安装能正常使用
5. arm机型使用内置最新$$，和软件中心；软件中心更新到最新版本后，可以配合7.0固件对插件进行离线安装，当然可以用来方便额回顾$$；
6. $$侧边栏入口默认关闭，现在默认$$的入口在软件中心，如果需要开启侧边栏显示，请在$$的附加设置页面进行设置；
7. 增加了htop作为任务管理器（可以在ssh客户端使用，不能在webshell和telnet客户端中使用）；
8.  需要说明的是关于区域选择，因为网件固件默认是全区域，而且最大功率可以调教到708mw，所以就没有选区的必要了；大家调整功率可以参考附件中的无线功率对照表，建议选区合适的功率，过大的功率也是会导致断流的。

### 刷机须知：
* 刷机有风险，刷机前请做好准备，如果刷机变砖，华硕机型可以使用救援模式救砖，网件机型可以使用[http://koolshare.cn/thread-63587-1-1.html](http://koolshare.cn/thread-63587-1-1.html)此贴的方法救砖；
* 刷机后一定格式化一次jffs分区，进入[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面，勾选Format JFFS partition at next boot，然后点击应用本页面设置，待设置保存后，重启路由器；
* 格式化jffs分区后请确保[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面的 Enable JFFS custom scripts and configs勾选是.
* 刷机后强烈建议恢复出厂设置一次，恢复后请手动配置各个项目，不要用以前的配置备份来恢复，可以避免很多小问题，比如无线功率调节问题

* 此版本超频命令（频率根据实际情况设置）：
###### `nvram set clkfreq=1200,800`
###### `nvram commit`
###### `reboot`


