## RT-AC66U_380.59_alpha1-X6.5.2.trx
#### 发布日期：2016-4-9 23:41:47
#### 发布链接：[https://koolshare.cn/thread-41156-1-1.html](https://koolshare.cn/thread-41156-1-1.html)
## 
### 固件特色：

* merlin固件源码380.59_alpha1
* koolshare内置$$，除了游戏模式，游戏模式v2，pcapDNSproxy，其余一致
* ssr支持，各种混淆，随便挑，随便选（最新ssr源码编译）
* 原版shadowsocks-libev的OTA支持（最新ss源码编译）
* $$在线更新，以后有问题可以通过在线更新修复，[观摩地址](https://github.com/koolshare/koolshare.github.io/tree/master/shadowsocks_mips)
* 小宝原创webshell支持
* 无线区域解锁支持

### 固件没有的特色：
* 对比arm机型，游戏模式肯定是无望了，因为mips机型linux内核太旧太旧的原因，没有Tproxy支持啊；
* 同理游戏模式V2也是无望了，一个原因是Tproxy没有，另一个原因是Mips平台不支持go语言；
* 再同理，软件中心也几乎没有了，说几乎是因为目前的软件中心基本上是基于ARM平台开发的，就算强行编译进去，也是用不了的哦，不过未来也许可以在arm的软件中心成熟后，再网MIPS平台移植（槽，我又挖了个大坑），不过还是有个好消息，目前软件中心，迅雷快鸟是支持mips平台的哦，不过就是需要点动手能力，自己手动装啦．如果你的功力更强，可以编译软件中心的一些软件的ｍｉｐｓ版本，给ｍｉｏｐｓ平台做同样的插件哦；
* 对比arm机型的$$，pcapDNSproxy也是没了，我个人测试过，对mipsel路由负担太大，砍掉！
