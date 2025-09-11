 --- Scanning ports from Kali to Metasploit --- 
# Capture [traffcap.png]
- Traffic capture before scanning with commands:
-  -i eth1 = Kali interface inside the internal red
-   -w nivel3_scan.pcap = saving the capture to analyze it with Wireshark
# Capture [portscan.png]
- Scanning ports with command:
- -sS = SYN scan, common in recognition attacks
-  -p 1-1000 = Scanning most used ports 
