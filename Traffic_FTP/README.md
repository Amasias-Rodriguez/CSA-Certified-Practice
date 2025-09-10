--- Traffic FTP in plain text ---
# Capture [server-ftp.png]
- Installing and setting up a FTP server
- Using command: sudo apt update && sudo apt install -y vsftpd
sudo systemctl start vsftpd
# Capture [conect-server.png]
- Conecting to the server in the vm lab with command: ftp 192.168.56.102
# File Transfer in Plain Text
# Capture [transfer.png]
- Creating a file test with command: echo "This is a secret test file" > secret.txt
# Capture [test.png] 
- Connecting the server to test the files previously sent
- Using command: ftp 192.168.56.102
- Command put = loading the file from vm main to the FTP server
- Command ls = file list in the FTP server
- Command get = download the new file 
