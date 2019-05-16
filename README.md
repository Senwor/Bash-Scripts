# Bash-Scripts
A series of bash scripts that time-save for various activities (HackTheBox, CTF's, Pentesting, messing around, etc.) Most scripts are scrapped together from other scripts that I have found useful w/ added personal touch or bug-fixed. 

## http
Runs python SimpleHTTPServer on designated interface, port & location. Usage: http \<ip\> \<location\>

## johnRocks
Runs john against the given hash with rockyou.txt. Can take additional flages. Usage: johnRocks \<file\> \<flags\>

## phpShell
Modifies the [pentestmonkey reverse shell](http://pentestmonkey.net/tools/web-shells/php-reverse-shell) with your IP, given port and output name (including .php).  Usage: phpShell \<port\> \<output\>

## smb
Runs smbserver.py from impacket. Usage: smb <smb-share> <directory-to-share>

## tun0
Runs ifconfig and cuts out the shit. Simple script that displays your tun0 IP address.

## wtf
Where the fuck?? This literally runs find. I use find so often that I cba typing it out. Usage: wtf \<file-to-find\>
