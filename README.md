# WiFi_DoS_w/_MAC_Spoofing
Simple shell script to realize an WiFi DoS with MAC Spoofing attack

# Requirements:

- WiFi interface in monitor mode (if not, you can do it by airmon-ng)

- Aircrack-ng
- MACCHANGER

For Debian-based linux distros, both can be installed by "apt-get install aircrack-ng macchanger"

# How to execute this script:

1- Check if the file has execution autorization (if not, just do "chmod +x [file name]")

2- ./[file name] [interface name] [target channel] [target MAC adress]

# How does this script works:

1- Set the target channel
   
2- Start an infinite loop

2.1- Change interface MAC adress to a random one

2.2- Send 3 deauthentication packets 
