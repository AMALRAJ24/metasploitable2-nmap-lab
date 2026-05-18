# Metasploitable 2 – Nmap Training Lab

## Overview

This repository contains my hands-on cybersecurity lab work completed using the Metasploitable 2 vulnerable machine and Nmap.

The objective of this lab was to gain practical experience in:

* Network reconnaissance
* TCP port scanning
* Service enumeration
* Vulnerability identification
* NSE scripting
* Basic exploitation concepts
* Linux user enumeration

This project helped strengthen my understanding of how attackers identify vulnerable services and how defenders can analyze and secure systems.

---

## Tools Used

* Nmap
* Linux
* Metasploitable 2
* NSE (Nmap Scripting Engine)

---

## Skills Practiced

### Network Discovery

Performed host discovery and subnet scanning.

### TCP SYN Scanning

Used stealth SYN scans to identify open ports.

### Service & Version Enumeration

Enumerated services and detected versions running on target ports.

### NSE Scripting

Used Nmap scripts for:

* FTP enumeration
* HTTP enumeration
* Vulnerability scanning

### Vulnerability Analysis

Identified vulnerable services including the vsftpd backdoor vulnerability.

### Linux Enumeration

Enumerated system users using `/etc/passwd`.

---

## Sample Commands Used

```bash
nmap -sn 192.168.56.0/24

nmap -sS 192.168.56.101

nmap -sV 192.168.56.101

nmap -p- 192.168.56.101

nmap --script vuln -p21 192.168.56.101

nmap --script ftp-anon 192.168.56.101
```

---

## Learning Outcomes

Through this lab, I gained practical exposure to:

* Real-world reconnaissance workflows
* Service enumeration techniques
* Vulnerability discovery methodologies
* Basic exploitation awareness
* Defensive security thinking

This project represents part of my ongoing cybersecurity learning journey focused on practical, hands-on skill development.

---

## Notes

Detailed handwritten notes and lab observations are included in the `/notes` directory.

---

## Ethical Disclaimer

This project was completed in a safe and authorized training environment using intentionally vulnerable machines for educational purposes only.

The techniques demonstrated here should never be used on systems without explicit authorization.

---

## Acknowledgment

Special thanks to Sigma Iota Ltd for providing the interactive cybersecurity training lab and learning resources.

Lab Resource:
https://sigmaiota.uk/student-resources/scan-lab/
