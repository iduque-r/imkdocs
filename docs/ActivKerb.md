- Enumerar: Powerview

- Permisos de acceso: ACL/ACE Control Listas de Acceso, y Control Entradas de Acceso.

* [Abuso de ACL/ACE](https://www.ired.team/offensive-security-experiments/active-directory-acls-aces)

* [Cuentas Privilegiadas y Tokens](https://www.ired.team/offensive-security-experiments/active-directory-kerberos-abuse/privileged-accounts-and-token-privileges)

* ACL/ACE Kerberoasting --> [Powesploit](https://powersploit.readthedocs.io/en/latest/Recon/Invoke-Kerberoast)

- DCSync:  Volcar Hashes controlador de dominio
- DCShadow: Convertirse en controlador de dominio
* [Link](https://www.elladodelmal.com/2018/03/dcshadow-y-dcsync-enganando-al-domain.html)

- Verificar tickets disponibles ---> Klist

- Golden Ticket
    - Mimikatz: Hash KRBTGT, lsadump::lsa
    - Mimikatz: Ticket falsificado--> kerberos::golden

- Silver Ticket

* [Mimikatz](https://adsecurity.org/?page_id=1821)
