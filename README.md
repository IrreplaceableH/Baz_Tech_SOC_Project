# Baz_Tech_SOC_Project
 BazTech SOC Project – Simulated Security Operations in a Segmented Network. This project demonstrates the design and implementation of a **Security Operations Center (SOC)** simulation for BazTech Inc.,  a startup exploring ways to strengthen visibility, detection, and response across segmented infrastructure.  
Project Overview
- **Objective:** Build a segmented network with SOC monitoring using **pfSense, Wazuh, Ubuntu, Windows 10, and Kali Linux**.  
- **Focus Areas:**
  - Network segmentation & firewall rules
  - Centralized log collection with Wazuh
  - Attack simulation & detection
  - Threat reporting & recommendations
  -  Workflow
1. Created segmented networks in pfSense (WAN, LAN, IT Dept, DMZ).  
2. Installed Wazuh Manager in the IT Dept & agents on endpoints.  
3. Launched brute-force SSH attacks with Kali Linux.  
4. Collected `/var/log/auth.log` and Windows Event Logs.  
5. Correlated events in Wazuh dashboards.
6. Key Insights
-  **Unauthorized Access Detection**: SSH brute-force attempts flagged.  
- **Lateral Movement**: Detected cross-segment attempts.  
-  **Log Correlation**: Abnormal login times + IP mismatches revealed.  
##  Skills Demonstrated
- Defensive Security (Blue Team operations)  
- SIEM Configuration & Monitoring (Wazuh)  
- Log Analysis & Threat Correlation  
- pfSense Firewall Configuration  
- SOC Reporting & Recommendations  
## Author
👤 MONICA  
🔗 https://www.linkedin.com/in/monique-i-ik
📧 freebirdinfinity@outlook.com 

⭐ If you found this project helpful, consider giving the repo a **star**!  


