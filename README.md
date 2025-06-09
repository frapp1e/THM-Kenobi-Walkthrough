# TryHackMe - Kenobi Walkthrough

This walkthrough covers the exploitation of the **Kenobi** machine on TryHackMe.  
It focuses on **FTP exploitation (ProFtpd 1.3.5)**, **NFS mounting**, and a **privilege escalation** technique using **PATH variable manipulation**.

## 🔧 Tools Used
- Nmap
- smbclient
- smbget
- Netcat
- Searchsploit
- SSH
- Linux commands

## 💡 Techniques Demonstrated
- Enumerating Samba shares
- Exploiting ProFtpd with SITE CPFR/CPTO
- Mounting NFS shares to extract SSH keys
- Gaining SSH access with private key
- Privilege escalation via SUID binary and manipulated PATH

## 🏁 Flags Captured
- user.txt
- root.txt

