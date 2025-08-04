Commands used:
nmap -sV 192.168.28.136 -oN detailed_scan.txt
nmap -sV 192.168.28.136 
sudo nmap -sS 192.168.28.136/24
ip a
sudo apt update && sudo apt install nmap -y



Security Analysis of the open ports:
🔸 Port 80 – HTTP

    Service: Apache HTTP Server

    Version: 2.4.65

    OS: Debian

    Risk:

        HTTP is unencrypted (no HTTPS).

        May be running a default web page, a test site, or an app.

        Could be vulnerable to:

            Information disclosure

            Directory listing

            Old/unpatched web application exploits
