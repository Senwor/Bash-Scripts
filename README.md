# Bash-Scripts
A series of bash scripts that time-save for various activities (HackTheBox, CTF's, Pentesting, messing around, etc.) Most scripts are scrapped together from other scripts that I have found useful w/ added personal touch. 

## http
Runs python SimpleHTTPServer on designated interface, port & location. Usage: http \<ip\> \<location\>

## johnRocks
Runs john against the given hash with rockyou.txt. Can take additional flages. Usage: johnRocks \<file\> \<flags\>

## smb
Runs smbserver.py from impacket. Usage: smb <smb-share> <directory-to-share>

## tun0
Runs ifconfig and cuts out the shit. Simple script that displays your tun0 IP address.
