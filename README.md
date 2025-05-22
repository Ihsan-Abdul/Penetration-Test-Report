# Penetration-Test-Report
This repository contains a penetration test report from a simulated engagement performed as part of a cybersecurity training program. The assessment was conducted in a controlled lab environment and emulates a real-world black-box penetration test for a fictional company: **Rekall Corp**.

##  Objectives
The goal of this project was to:
Discover and exploit vulnerabilities across a mixed-OS environment
Escalate privileges and access sensitive data
Document technical findings and provide remediation recommendations
Simulate real-world ethical hacking under PTES and MITRE ATT&CK frameworks

## Tools Used
- **Reconnaissance**: Nmap, Domain Dossier, crt.sh
- **Exploitation**: Metasploit, Nessus, John the Ripper, Kiwi
- **Web Testing**: Manual input fuzzing, SQL payloads, custom scripts
- **Documentation**: Professional-style PDF report with detailed technical breakdowns

# Vulnerabilities Identified

### Web Application
- Reflected and Stored XSS
- SQL Injection (login bypass)
- Command Injection (DNS/MX check)
- Local File Inclusion / Malicious File Uploads
- Credential Disclosure via HTML Source
- Insecure brute-force protections

### Linux Targets
- Shellshock (CVE-2014-6271)
- Apache Tomcat RCE (CVE-2017-12617)
- Struts RCE (CVE-2017-5638)
- Drupal RCE (CVE-2019-6340)
- WHOIS and SSL Certificate data exposure

### Windows Targets
- FTP Anonymous Access (Port 21)
- SLMail Buffer Overflow Exploit (Port 110)
- Password hash cracking using Kiwi
- Scheduled Task Persistence
- Sensitive Data Exposure

## Severity Overview
-**Critical**: 14
-**High**:3
-**Medium**: 3

> Vulnerabilities were rated based on business impact and ease of exploitation, aligned with PTES and general CVSS logic.


[Download the Full Report (PDF)](./Rekall_Penetration_Test_Report.pdf)


## ⚠️ Disclaimer

> This project was conducted entirely in a **simulated lab environment**. No real systems or external companies were involved. The purpose of this work is strictly educational and professional portfolio development.

---
