tcpdump静态编译版本，适用于merlin等arm固件

如果希望抓包能在windows上用wireshark分析，可以适用以下命令：
`tcpdump -i br0 -s 0 -w test.pcap`