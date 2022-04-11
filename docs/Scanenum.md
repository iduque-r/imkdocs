
## Reconocimiento Pasivo

	- whois para consultar servidores WHOIS
	- nslookup para consultar servidores DNS
	- dig para consultar servidores DNS
	- DnsDumper
	- Shodan.io

## Reconocimiento activo

	- Ping
	- Traceroute
	- Telnet
	- Netcat

## NMAP	

	General

	- nmap -vv -Pn -A -sC -Sv -sS -sO -T 4 -p- 10.0.0.1
* Verbose, syn, Todos pruertos, Todos  scripts, Version,SO,  no ping.

	- nmap -v -sS -A -T4 x.x.x.x
* Verbose, SYN Stealth, Version info, Escaneo agesivo 4 de 5.

	- nmap –script smb-check-vulns.nse –script-args=unsaf
* Script SMB Vulnerables

	- nmap --Script ftp-

## Net Discover

	- netdiscover -r 192.168.1.0/24

## SSH
	- SSH IP 22

## SMTP

	- nc -nvv IP 25
	- nmap --script smtp-
	- telnet IP 25
## RPC 
	
	- rpcinfo -p IP
	
## SMB/RPC (139/445)

	- enum4linux -a IP
	- impacket
	- smbclient -L IP
	- nmap IP --scrip smb-enum

## DNS
	
	- nslookup
	- dig
	- dnsrecon




