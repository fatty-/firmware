## R7000_380.61-X7.0.trx
#### [发布链接](http://koolshare.cn/thread-44661-1-1.html)
 
##### File: R7000_380.61_X7.0.trx
##### Size: 31715328 字节
##### Modified: 2016年9月11日, 17:03:00
##### MD5: 9563AFCA8E8A9C22B029C90B18D642B3
##### SHA1: 15209C9092F4BAC4E44086D4968F3CE9CB3B5D11
##### CRC32: 107D8A02

* * *
从7.0版本固件开始，网件机型的代码会跟随Votex的代码

需要说明的是，华硕再最近的官方固件中，加入了固件校验机制，并且刷写了最新华硕固件和merlin固件的朋友，不能通过web进行降级；
不过Votex大神再代码上做了破解，绕过了这个机制，所以此次7.0改版固件将不存在这个问题，刷了7.0的能轻松的在web页面上降级6.6，5.6等版本。
### 更新日志：
1. 固件本身的更新日志，主要参考Votex更新日志，版本号基于merlin 380.61
2. 本次固件和以往固件不同，网件机型使用了基于V大的代码重做了R7000,并由8万大神重新移植了R6300V2，网件的机型无线部分完全沿用v大的移植
3. 合并了koolshare坛友thesadboy的修改梅林首页增加部分系统信息页面，http://koolshare.cn/thread-61065-1-1.html
4. 修复了httpd文件上传的一个bug，修复后webshell上传文件和软件中心离线安装能正常使用
5. arm机型使用内置最新$$，和软件中心
6. $$侧边栏入口默认关闭
7. 我们选用了梅林的 59 版本。
8. 增加了htop作为任务管理器（可以在ssh，telnet客户端使用，不能在webshell中使用）

### 刷机须知：
* 刷机有风险，刷机前请做好准备，如果刷机变砖，华硕机型可以使用救援模式救砖，网件机型可以使用[http://koolshare.cn/thread-63587-1-1.html](http://koolshare.cn/thread-63587-1-1.html)此贴的方法救砖；
* 刷机后一定格式化一次jffs分区，进入[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面，勾选Format JFFS partition at next boot，然后点击应用本页面设置，待设置保存后，重启路由器；
* 格式化jffs分区后请确保[http://router.asus.com/Advanced_System_Content.asp](http://router.asus.com/Advanced_System_Content.asp)此页面的 Enable JFFS custom scripts and configs勾选是.

