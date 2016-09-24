## Usage:

koolproxy -h

koolproxy -a chinalist_easylist.txt -p 3000

iptables -t nat -A PREROUTING -p tcp -s 192.168.1.0/24 --dport 80 -j REDIRECT --to-ports 3000、


移除程序，插件已发布
