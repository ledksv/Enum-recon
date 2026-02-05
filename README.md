Recon + Enumeration Framework

A Bash script for automated reconnaissance and enumeration during authorized penetration tests.
It performs passive OSINT, port scanning, service detection, web enumeration, and basic vulnerability checks, while organizing all output into a clean project folder.

⚠️ Authorized use only.

Requirements

Required
	•	nmap
	•	gobuster
	•	nikto
	•	whatweb
	•	curl
	•	dig
	•	openssl
	•	whois

Optional (auto-detected)
	•	amass / subfinder
	•	enum4linux
	•	snmpwalk
	•	theHarvester

How to use:
1)nano recon.sh #paste script and save
2)chmod +x recon.sh (making the script executable)
3)./recon.sh
4)Enter:
	•	Project name
	•	Target (IP or domain)



