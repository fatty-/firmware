* KoolProxy 是一个免费软件，著作权归属 KoolProxy.com，用户可以非商业性地复制和使用 KoolProxy，但禁止将 KoolProxy 用于商业用途。
* KoolProxy 可以对 https 网络数据进行识别代理，使用 https 功能的用户需要自己提供相关证书，本程序提供的证书生成脚本仅供用户参考，证书的保密工作由用户自行负责。
* 使用本软件的风险由用户自行承担，在适用法律允许的最大范围内，对因使用本产品所产生的损害及风险，包括但不限于直接或间接的个人损害、商业赢利的丧失、贸易中断、商业信息的丢失或任何其它经济损失，KoolProxy.com 不承担任何责任。

##### 静态规则地址：https://rules.ngrok.wang/koolproxy.txt
##### 视频规则地址：https://rules.ngrok.wang/1.dat
##### 规则校验文件：https://rules.ngrok.wang/config.json.js

```shell
KoolProxy By Xiaobao & Crwnet v3.2.1

USAGE:
  koolproxy [options] [arguments...]

OPTIONS:
  -p value             listen port, default value is 3000
  -l value             log level (DEBUG, INFO, AD, WARNING, ERROR), default value is ERROR
  -c value             thread count, default value is the number of cpus
  -b value             data path, default is './data'
  -t value             ttl mode, set the socket ttl when connect to remote host. default is 0 (disable)
  -e                   load video rule and user rule only
  -d                   run as daemon mode
  -h                   show help
```