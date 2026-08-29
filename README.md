# Technical Systems Portfolio | Brandon Fontaine
Systems Administration • Technical Documentation • IT Automation

A collection of enterprise infrastructure deployments, automated system auditing tools, and comprehensive technical documentation.

## IT Projects Overview

📁 [Active Directory Project](https://github.com/water-fountain/IT-Portfolio/blob/main/AD-Project/main_active_directory_lab_guide.md)

![Windows Server 2019](https://img.shields.io/badge/Windows_Server_2019-0078D6?style=flat&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat&logo=microsoft&logoColor=white)
![Group Policy](https://img.shields.io/badge/Group_Policy-0078D4?style=flat&logo=windows&logoColor=white)
![DNS & DHCP](https://img.shields.io/badge/DNS%20%26%20DHCP-217346?style=flat&logo=microsoft&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)

<strong>More Information:</strong>
Architected a virtualized enterprise domain environment utilizing Windows Server 2019 to implement secure identity lifecycles and resilient network services.

### Core Deliverables:
* Identity Management: Role-Based Access Control (RBAC) and OU structural design.
* Policy Automation: Enterprise-wide configuration enforcement via Group Policy Objects (GPOs).
* Network Services: Integrated DNS, DHCP, and secure NTFS file sharing.
* Diagnostics: Full-stack authentication and domain-join troubleshooting frameworks.

📁 [Sentinel-Health Auditer](https://github.com/water-fountain/Portfolio/blob/main/SentinelHealth-Auditor/SentinelHealth.ps1)

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![WMI / CIM](https://img.shields.io/badge/WMI%20%2F%20CIM-0078D4?style=flat&logo=windows&logoColor=white)
![REST API Webhooks](https://img.shields.io/badge/REST_API-Webhooks-5865F2?style=flat&logo=discord&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

<strong>More Information:</strong>
A custom PowerShell tool designed to monitor system health and send automated alerts. This project involved building an end-to-end pipeline that gathers hardware data, evaluates system status, and generates both a local visual dashboard and remote cloud alerts.

### Key Skills Demonstrated:

- Logic & Automation: Built a workflow that pulls hardware metrics via CIM/WMI and pushes JSON-formatted alerts to a Discord Webhook.
- Infrastructure Troubleshooting: Identified and fixed a common Windows reporting flaw where "Fast Startup" (Hiberboot) caused incorrect uptime data.
- Data Accuracy: Refined resource monitoring by sampling real-time CPU usage and normalizing the data for multi-core processors.
- Front-End Presentation: Designed a modern, dark-mode HTML/CSS dashboard to make technical reports readable for non-technical users.
- AI Collaboration: Leveraged AI as a "technical peer" to assist with CSS design, troubleshoot character encoding issues, and refactor complex logic for better performance.

📁 [Help Desk Ticket Scenarios](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/README.md)

![ITIL](https://img.shields.io/badge/ITIL-Framework-0052CC?style=flat&logo=atlassian&logoColor=white)
![Windows 10/11](https://img.shields.io/badge/Windows_10%2F11-0078D6?style=flat&logo=windows&logoColor=white)
![Incident Management](https://img.shields.io/badge/Incident-Management-D9381E?style=flat&logo=atlassian&logoColor=white)
![Troubleshooting](https://img.shields.io/badge/Troubleshooting-Diagnostic-2EA44F?style=flat&logo=github&logoColor=white)

<strong>More Information:</strong>
Simulates real-world IT help desk incidents to demonstrate structured troubleshooting, documentation, and resolution of common Windows and user access issues within an enterprise support context.

### Key Skills demonstrated:

- Incident and problem documentation
- Windows operating system troubleshooting
- Account and access issue resolution
- Step-by-step diagnostic workflows
- Technical communication and escalation criteria

📁 [Windows-Lockout-Recovery-Guide](https://github.com/water-fountain/IT-Portfolio/blob/main/Windows-Lockout-Recovery-Guide/windows_lockedout_recovery_guide.md)

![ITIL](https://img.shields.io/badge/ITIL-Framework-0052CC?style=flat&logo=atlassian&logoColor=white)
![Windows 10/11](https://img.shields.io/badge/Windows_10%2F11-0078D6?style=flat&logo=windows&logoColor=white)
![Incident Management](https://img.shields.io/badge/Incident-Management-D9381E?style=flat&logo=atlassian&logoColor=white)
![Troubleshooting](https://img.shields.io/badge/Troubleshooting-Diagnostic-2EA44F?style=flat&logo=github&logoColor=white)

<strong>More Information:</strong>
Allows access to a Windows system or Windows Active Directory account, if you are locked out due to a forgotten password using the utilman.exe workaround. 

### Key Skills Demonstrated:

- Windows Account Management: Understanding local and Active Directory accounts, permissions, and policies
- Password & Lockout Recovery: Safe application of the utilman.exe workaround to regain access to account
- Troubleshooting & Problem Solving: Diagnosing lockout causes and implementing effective solutions
- System Administration: Modifying system files, using administrative privileges, and working with Windows utilities
- Security Awareness: Maintaining system integrity and protecting data during recovery procedures

## 📝 Technical Writing & Documentation

🗄️[Stop Buying New Gear: Turn Your Dusty Old Laptop into a High-Power Home Server](https://github.com/water-fountain/IT-Portfolio/blob/main/Tech-Writing-Samples/Laptop-Pi-Home-Server-Guide.md)

<strong>More Information:</strong>
A conversational yet technical guide on how to convert an "obsolete" laptop into a functional home server with the simple addition of a Raspberry Pi.

### Key Skills Demonstrated:
* **Remote Management**: Configuring Headless OS deployments with pre-authenticated SSH access.
* **Network Troubleshooting**: Using ICMP (ping) and DHCP client lists to verify node connectivity.
* **Linux Administration**: Basic CLI interaction, package management (apt update), and service security (UFW).

🗄️[Forgotten Your Windows Password? Here's How to Break Back In](https://github.com/water-fountain/Portfolio/blob/main/Tech-Writing-Samples/Windows-Recovery-Guide.md)

<strong>More Information:</strong>
A last "ditch" technical guide detailing how to regain system access using the Windows Recovery Environment (WinRE) to bypass the login screen without any data loss.

### Key Skills Demonstrated:
* **System Recovery & Logic**: Navigating WinRE and using `diskpart` to identify shifted drive letters in a pre-boot environment.
* **Advanced Command Line**: Executing file system "swaps" and using `net user` commands to override administrative credentials.
* **Security Posture:** Explicitly documenting the "Restore to Factory" phase to ensure no permanent security backdoors are left on the system.
* **Instructional Design**: Using a "Safety First" approach with clear warnings and post-recovery "Safety Net" tips for the user.

🗄️[Why Your USB-C Cable Doesn’t Work (And How to Avoid Buying the Wrong One)](https://github.com/water-fountain/Portfolio/blob/main/Tech-Writing-Samples/USBC-Differences-Guide.md)

<strong>More Information:</strong>
A comprehensive feature breaking down the often-invisible logic behind USB-C hardware and Power Delivery (PD) protocols.

### Key Skills Demonstrated:

* **Hardware Protocol Analysis**: Explaining the distinction between physical connectors (USB-C) and underlying data standards like USB 3.2 and USB4.
* **Power Delivery (PD) Expertise**: Detailing the negotiation process between chargers and devices, specifically the role of E-Marker chips in high-wattage (100W+) cables.
* **Consumer Advocacy**: Translating "alphabet soup" specifications into actionable buying advice for charging, data transfer, and Alt-Mode video output.
* **Technical Clarity**: Using a "Visual Identification" approach to help readers navigate unlabelled cables and mismatched hardware specifications.

### About Me

Aspiring IT Support/Help Desk Technician with hands-on experience in device imaging, QA, and enterprise IT deployments. CompTIA Network+ certified, with a strong focus on troubleshooting, documentation, and continuous learning.

🔗 Contact & Links

GitHub: https://github.com/water-fountain

LinkedIn: https://www.linkedin.com/in/bfountains/
