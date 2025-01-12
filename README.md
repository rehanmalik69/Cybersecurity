Cybersecurity Firmware Analysis

Project Overview:
This project focuses on firmware analysis, leveraging advanced tools and techniques for identifying vulnerabilities in hardware-associated software. It provides insights into control, monitoring, and operational functionalities of devices embedded with firmware.

What is Firmware?
Firmware is a specialized type of software embedded into hardware or stored on non-volatile memory like ROM, flash memory, or EEPROM. It bridges the gap between hardware and software, ensuring operational functionality and control.

 Tools and Environment:
- Operating System: Kali Linux
- Additional Tools: Nmap, Netcraft, and other vulnerability scanning utilities.

Key Features:
1. Identifying Vulnerable Applications
- Task: Locate applications susceptible to SQL injection.
- Outcome: Successfully accessed admin login portals for multiple websites.

2. Vulnerability Analysis
a. Live Camera Exploits
- Identified vulnerable live cameras and successfully gained access.

b. Subdomain Enumeration
- Target: `https://www.youtube.com/in`
- Tools Used: Netcraft DNS search.
- Outcome: Discovered 62 subdomains and associated operating systems.

 3. Nmap Scanning for Open Ports
- Target: `netcraft.in`
- Steps:
  1. Launched a virtual Kali Linux environment.
  2. Executed Nmap commands to analyze open ports and version details.
- Results:
  - A detailed list of open ports and services.
  - Successfully retrieved service versions for enhanced vulnerability assessment.

Results Summary:
- SQL injection vulnerabilities identified and exploited.
- Successful enumeration of subdomains and live camera vulnerabilities.
- Comprehensive Nmap scans conducted to reveal open ports and version details.

How to Use:
1. Set Up Environment:
   - Install and configure Kali Linux on a virtual machine.
   - Ensure root access for executing advanced commands.
2. Run Vulnerability Tests:
   - Use tools like Netcraft for DNS enumeration.
   - Execute Nmap for scanning open ports and services.
3. Analyze Results:
   - Interpret scan outputs for actionable insights on system vulnerabilities.

Screenshots:
SQL Injection Success
![SQL Injection](path-to-screenshot-1)

Subdomain Enumeration
![Subdomain Results](path-to-screenshot-2)

Nmap Scan Output:
![Nmap Scan](path-to-screenshot-3)

License:
This project is licensed under the [MIT License](LICENSE).
