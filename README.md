# nmap-portscan-task

Objective --------
to scan the ipaddress and identify the ports and services running on it
TOOLS USED - NMAP

entering the following command
nmap -sS 192.168.29.162/24 -oN scan_result.txt

this will scan the ip and write the results to a text file for easier analysis

RESULTS 
80/tcp   open   http
443/tcp  open   https
1900/tcp open   upnp
2869/tcp closed icslap
7443/tcp open   oracleas-https
8002/tcp closed teradataordbms
8080/tcp open   http-proxy
8200/tcp closed trivnet1
8443/tcp open   https-alt

more on the screenshot attatched
