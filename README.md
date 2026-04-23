# Wordlist_gen.py
#Wordlist_gen.py
# CYB-SUPERNOVA Toolkit 🛡️

Python cybersecurity tools built 100% on Android in Kaduna, Nigeria. Zero frameworks. All audit-grade with CSV logging.

## Tools Included

### 1. Password Audit CLI
Tests password strength against real attack rules: length, character sets, common-password list. 
`>> Logs all attempts to audit.csv for compliance tracking`

### 2. Port Scanner v3 - Speed Demon  
Threaded network recon tool. Scans top 20 ports in ~1.5s using 50 threads.
- Service identification: FTP, SSH, HTTP, SMTP, DNS, etc
- Context-aware alerts: Detects Hotspot/VPN DNS on localhost
- Full audit trail: Saves timestamp, target, port, service to `scan_log.csv`

### 3. Log Analyzer v1.1
Threat intelligence engine. Reads `scan_log.csv` and outputs:
- Total findings + unique targets
- Port frequency statistics  
- Hotspot/VPN detection count
- Latest scan timestamp

## Tech Stack
`Python 3` `socket` `threading` `csv` `datetime` `Pydroid 3`

## Legal Notice
Only scan systems you own or have explicit permission to test. `scanme.nmap.org` is provided by Nmap for legal testing.

## Author
Built by Isaac [@cyb-supernova] from scratch on mobile. 
Learning DevSecOps + Cybersecurity. Open to internships/mentorship.

---
*If you're a recruiter: I build tools, not tutorials. Check the commit history.*

