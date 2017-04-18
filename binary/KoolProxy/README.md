* KoolProxy 是一个免费软件，著作权归属 KoolProxy.com，用户可以非商业性地复制和使用 KoolProxy，但禁止将 KoolProxy 用于商业用途。
* KoolProxy 可以对 https 网络数据进行识别代理，使用 https 功能的用户需要自己提供相关证书，本程序提供的证书生成脚本仅供用户参考，证书的保密工作由用户自行负责。
* 使用本软件的风险由用户自行承担，在适用法律允许的最大范围内，对因使用本产品所产生的损害及风险，包括但不限于直接或间接的个人损害、商业赢利的丧失、贸易中断、商业信息的丢失或任何其它经济损失，KoolProxy.com 不承担任何责任。

证书生成请参考如下脚本：https://github.com/koolproxy/merlin-koolproxy/blob/master/koolproxy/koolproxy/data/gen_ca.sh


#### 由于大量koolproxy下载请求，几乎全部都是mipsel架构的，不仅导致现在的服务器爆了流量，还爆了信用卡，而服务器还要提供固件下载服务，所以 经过考虑，决定撤下http://firmware.koolshare.cn/binary/KoolProxy/这里的 koolproxy二进制文件，老毛子固件，部分luci用户，部分lede用户可能会受到影响。
#### koolproxy 将于近期更新3.4版本，集成二进制自动更新功能，且使用cdn服务，固件、插件作者、用户都不需要再关心二进制版本的升级。