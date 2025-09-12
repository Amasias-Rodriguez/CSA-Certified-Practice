--- Event Correlation and SOC alerts ---
# Capture [analysis.png]
- Preparing captures to analysis, using commands:
  mkdir ~/SOC_lab_captures
  mv ~/nivel3_scan.pcap ~/nivel3_ftp_bruteforce.pcap ~/nivel4_exfiltracion.pcap   ~/SOC_lab_captures/
# Capture [tcpsyn.png]
- Filtered TCP SYN packets in Wireshark:
  `tcp.flags.syn == 1 && tcp.flags.ack == 0`
- Identified port scanning activity from Kali to Metasploitable
