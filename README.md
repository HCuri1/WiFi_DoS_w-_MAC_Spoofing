# WiFi_DoS_w/_MAC_Spoofing
Simple shell script to realize an WiFi DoS with MAC Spoofing attack

Requirements:

- Aircrack-ng
- MACCHANGER

For Debian-based linux distros, both can be installed by "apt-get install aircrack-ng macchanger"

How to execute this script:

1- Check if the file has execution autorization (if not, just do "chmod +x [file name])

2- ./[file name] [interface name] [target channel] [target MAC adress]
