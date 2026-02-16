About This Report	4

Phase 1: Recognition and collection of evidence.  
Suspicious file found on /etc/cron.daily/apt-compat  
/etc/cron.daily/apt-compat Suspicious code  
/usr/lib/apt/apt.systemd.daily Suspicious code.	 
/etc/cron.daily/man-db Suspicious code.  	
Conclusions  
  
Phase 2: Detect Vulnerabilities.  
Preparing the Working Station.  
Network Recognition	  
Known Vulnerabilities and Classifications  
Gobuster Fuzzing http://192.168.1.232/  
SSH Connection using default credentials  
FTP Connection  
WpScan  
Exploring the Server Machine	
Wordpress Security Analysis  	
Wordpress 6.9.1 Known Vulnerabilities  
Using the Command Find  
/var/log/README  
/usr/share/doc/systemd/README.logs  
/var/log/journal  
Command Journalctl.  
Command Journalctl -b -4	  
Suspicious file compat.php compat-utf8.php  
Exploiting a vulnerability Metaexploit  	
Another Suspicious Findings  
  
Phase 3: Patching Vulnerabilities & Hardening Tools  
Removing the Reverse Shell Exploit  
Script to Update all services and installed apps  	
Creating an Update Service  
Deleting the Users with Weak Passwords	  
Blocking the Port 21 ftp Service. UFW	  
Sanitizing Unicode Scripts	  
Installing a Monitoring Tool, Wazuh	  
Installing an Antivirus, ClamAV	  
Fixing the Wordpress Ownership and setting Default Settings	  
Sanitizing the Port 22 SSH, UFW	  
Opening the Port 443	  
Changing the Generic password	  
Installing rkhunter.	  
Conclusions  
Summary of Findings	  
Further compounding the breach were fundamental security misconfigurations:	  
Remediation Outcomes	  
Key Aspects that made this possible	  
Final Statement	  
  
INCIDENT RESPONSE PLAN AND ISMS (MANAGED SECURITY – ISO 27001:2022)	  
1st Creating the Incident Response Plan  
2nd Development of Detailed Procedures (Playbooks)  
3rd Implementation of Data Protection Mechanisms (ISO 27001:2022 Annex A Controls)  
4th Integration with ISO 27001:2022 ISMS  
Step 5: Data Loss Prevention (DLP) Recommendations - Control A.8.12  
Conclusion and References  
  
Annex  
Information Sources and Exploited Tools	  
Regulation Sources   
