# End-to-End-Penetration-Test-on-Metasploitable2 (with CVSS Reporting)

This repository documents a complete penetration test simulation conducted on the Metasploitable2 virtual machine using Kali Linux. The project includes recon, exploitation, privilege escalation, and professional reporting with CVSS scoring and remediation recommendations.

## 🧰 Lab Setup

- Attacker: Kali Linux
- Target: Metasploitable2
- Network: Host-only (VirtualBox)
- Tools: Nmap, Gobuster, WhatWeb, Metasploit, Linux Exploit Suggester

## 🔍 Reconnaissance & Enumeration

- Nmap scan, Gobuster directory bruteforce, WhatWeb fingerprinting
- Key services: FTP, HTTP, Tomcat, DVWA, Mutillidae

## 💥 Exploitation

- vsFTPd 2.3.4 Backdoor (CVE-2011-2523)
- Tomcat Manager WAR Upload Shell
- SQLi on DVWA Login
- Command Injection in Mutillidae

## 🧗 Privilege Escalation

- Kernel-level local exploit to root via searchsploit

## 📄 Report

- DOCX report with CVSS scoring and remediation
- Screenshots included in `/screenshots`

## ✍️ Author

Kamlesh Suthar – [LinkedIn](https://www.linkedin.com/in/kamlesh-suthar-378764356) | [Medium](https://medium.com/@kamlesh140501)
