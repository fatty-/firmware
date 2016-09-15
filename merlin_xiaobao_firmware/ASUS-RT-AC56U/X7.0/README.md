## RT-AC56U_380.61_X7.0.trx
#### 
 
##### File: RT-AC56U_380.61_X7.0.trx
##### Size: 31617024 字节
##### Modified: 2016年9月15日, 9:48:07
##### MD5: 57E4CA99BDCE611B5C2B6A01381FC638
##### SHA1: 5BE6AA8BDB1575EE380E3E9C033B2E2D3AEA5737
##### CRC32: DBD73E66

* * *
### 说明
华硕在最近的官方固件中，加入了固件校验机制，并且刷写了最新华硕固件和merlin固件的朋友，不能通过web进行降级；

不过我们借鉴了Votex的破解方法，绕过了这个机制，所以此次7.0改版固件将不存在这个问题，刷了7.0的能轻松的在web页面上降级6.6，5.6等版本。
### 更新日志(RT-AC56U)：
1. 固件本身的更新日志，主要参考Votex更新日志，Rmerlin的更新日志，固件版本号基于merlin 380.61
2. 和网件机型不同的是，华硕固件侧边栏的一级菜单并没有减少内容，还是原来的配方，还是熟悉的味道~华硕毕竟亲儿子嘛~
3. 合并了koolshare坛友thesadboy的修改梅林首页增加部分系统信息页面，[http://koolshare.cn/thread-61065-1-1.html](http://koolshare.cn/thread-61065-1-1.html)，在此感谢thesadboy
4. 修复了httpd文件上传的一个bug，修复后webshell上传文件和软件中心离线安装能正常使用
5. arm机型使用内置最新$$，和软件中心；软件中心更新到最新版本后，可以配合7.0固件对插件进行离线安装，当然可以用来方便的回滚$$；
6. $$侧边栏入口默认关闭，现在默认$$的入口在软件中心，如果需要开启侧边栏显示，请在$$的附加设置页面进行设置；
7. 增加了htop作为任务管理器（可以在ssh客户端使用，不能在webshell和telnet客户端中使用）；
8. 和网件机型采用Votex大的无线代码和设置不同，华硕机型统一采用了Rmerlin的代码和设置。也就是说从7.0开始，网件部分有V大的调教和koolshare的修复（无线功率调节），华硕机型有华硕攻城师和Rmerlin的调教，koolshare对华硕的无线部分不做任何改动。 需要说明的是关于区域选择，因为网件固件默认是全区域，而且最大功率可以调教到708mw，所以就没有选区的必要了；而华硕机型因为koolshare是原样承袭merlin固件，加上华硕机型默认不是全区，所以就有改区的选项，不同区域有不同的最大功率限制（但仍然受到cfe限制），这里我个人推荐澳大利亚（不同的cfe可能会出现不同的国家列表，这个固件目前不能控制）；
9. 将修改单线双拨从并发双拨改为非并发双拨。

### 刷机须知：
* 刷机有风险，刷机前请做好准备，如果刷机变砖，华硕机型可以使用救援模式救砖，网件机型可以使用[http://koolshare.cn/thread-63587-1-1.html](http://koolshare.cn/thread-63587-1-1.html)此贴的方法救砖；
* 刷机后一定格式化一次jffs分区，进入[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面，勾选Format JFFS partition at next boot，然后点击应用本页面设置，待设置保存后，重启路由器；
* 格式化jffs分区后请确保[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面的 Enable JFFS custom scripts and configs勾选是.
* 刷机后强烈建议恢复出厂设置一次，恢复后请手动配置各个项目，不要用以前的配置备份来恢复，可以避免很多小问题，比如无线功率调节问题

* 此版本超频命令（频率根据实际情况设置）：
###### `nvram set clkfreq=1200,800`
###### `nvram commit`
###### `reboot`
