## Frameworks
	
	* BurpSuite, OwaspZAP

## Auditoria

	OWASP-ZAP
	- Escaner Pasivo: Seguro, inofensivo
	- Escaner Activo: Modifica datos, inserta scripts maliciosos.
	- Modo de Escaneo: 
				- Estandar
				- Ataque
				- Seguro
				- Protegido
	- Contexto: Enfocar sitio, descartar otros con Scope.
	- Controlar ventana de Solicitudes y Respuestas, Headers, Body, Parametros.
	- Alertas, controlar falsos positivos.
	- Navegacion proxy Web, exploración manual.
	- Araña Automática, Attack - Spider - Scope
	- Politica de escaneo.
	- Fuzzer Ataques de diccionario.
	- Navegación Forzada: Attack Forced Browse Directory, Diccionario.
	- Break: Interrupción de solicitudes para su modificación.
	- Informes: HTML, XML, JSON...

	Nikto
	- nikto -update
	- nikto -h <IP>
	- nikto -h <IP> -ssl

	WPScan
	- wpscan --url http://192.168.1.100/wordpress/

	Whatweb
	- ./whatweb -v ejemplo.com

	HttpX
    - httpx -l list -tittle -status-code -tech-detect -follow-redirects   
    - subfinder -d web.com | httpx -tittle -status-code - tech-detect
	

[HttpX](https://github.com/projectdiscovery/httpx)
	
[Whatweb](https://github.com/urbanadventurer/WhatWeb)

[Nikto](https://ciberseguridad.com/herramientas/software/nikto/)

[WPScan](https://www.hackingarticles.in/wpscanwordpress-pentesting-framework/)

[Owasp-Zap](https://volosoft.com/Blog/Running-Penetration-Tests-for-your-Website-as-a-Simple-Developer)

## Metodología

	- Info: Inspector, Debugger, codigo.

	- Contenido: Robots.txt, sitemap.xml, Headers, Dorking, OSINT, Info empleados, correos.

	- Herramientas de Contenido: ffuf, wfuzz,  dirb, Gobuster.

	- Subdominios, Directorios: Google Dorks, DnsRecon, ffuf, Gobuster.

	- Escaner: Nmap, nikto, Metasploit-WNAPCode, Xray, Sqlmap, WPScan.

	- Auth Bypass: Fuerza bruta, Volcado, Hydra, Hashcat, John The Ripper.

	- Vuln y Exploit: Nmap, Searchsploit, Metasploit-WNAP, GTFObins Exploit-db, Buffer Overflow.

	- Shell: /Share/Webshells, Pentestmonkey, Msfvenom, NC, Python.

	- Tunel / Proxy: Chisel, Proxychains, NC, Tor.

## Puertos

- Puerto 21 (FTP)
- Puerto 22 (SSH)
- Puerto 25 (SMTP)
- Puerto 53 (DNS)
- Puerto 80/443 (HTTP/HTTPS)
- Puerto 110 (POP3)
- Puerto 111 (RPCINFO)
- Puerto 137.138.139 (NetBIOS)
- Puerto 445 (SMB)
- Puerto 389 (LDAP)
- Puerto 1433 (MSSQL)
- Puerto 2049 (NFS)
- Puerto 3306 (MYSQL)
- Puerto 3389 (RDP)
- Puerto 5900/5800 (VNC)

## VULNS

	- RCE		
	- SQLI			
	- XSS			
	- LFI/RFI
	- XEE
	- HTML Inject
	- Broken Auth
	- Command Inject
	- Banner Grabbing
	- CSRF
	- File Upload
	- Patch Transversal
	- Cookies
	- ClickJacking
	- CSS Injection
	- 

[Owasp-Zap](https://volosoft.com/Blog/Running-Penetration-Tests-for-your-Website-as-a-Simple-Developer)

[Nikto](https://github.com/sullo/nikto/wiki/Basic-Testing)

[Xray](https://docs.xray.cool/#/tutorial/prepare)	
