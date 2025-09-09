 --- Netowork Monitoring and Traffic Capture --- 
# Capture [ping.png]
- Analyze normal traffic (ping and simple browsing).
- Checking network connectivity between both vm's using command ping -c 4 ip
# Capture [icmp.png] [icmp2.png]
- Traffic ICMP traffic with tcpdump using command: sudo tcpdump -i eth0 icmp
- i eth0 = indicates the network interface (it may be enp0s3 instead of eth0, confirm with ip a).
- icmp = filters just icmp packages
# Capture [tcp.png]
- TCP Handshake (3 way handshake) with command (in main vm): sudo tcpdump -i tcp port 8080 -vv
- Using curl http://192.168.56.102:8080 in lab main.
# Capture [udp.png]
- Traffic UDP (DNS query)
- Using command: sudo tcpdump -i eth1 udp port 5353 -vv
