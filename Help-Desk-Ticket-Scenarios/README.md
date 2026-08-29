# Help Desk Ticket Scenarios & Incident Resolution
![ITIL](https://img.shields.io/badge/ITIL-Framework-0052CC?style=flat&logo=atlassian&logoColor=white)
![Windows 10](https://img.shields.io/badge/Windows_10_Enterprise-0078D6?style=flat&logo=windows&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server_2019%2F2022-0078D6?style=flat&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat&logo=microsoft&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)

## Overview
This project simulates real-world Tier 1 / Tier 2 IT Help Desk ticket workflows within a Windows environment. The goal is to demonstrate structured troubleshooting, clear technical documentation, and professional ticket resolution practices commonly expected in entry-level IT support and technical writing roles.

All scenarios were executed and documented within a controlled **Active Directory home lab environment** to reflect real enterprise workflows.

## Environment Summary

* **Operating Systems:** Windows 10 Enterprise, Windows Server 2019/2022
* **Directory Services:** Active Directory Domain Services (AD DS)
* **Core Services:** DNS, DHCP, SMB File Services
* **Management Tools:** ADUC, Group Policy Management, PowerShell
* **Authentication & Access Control:** Domain accounts, security groups, NTFS & share permissions

## Ticket Scenarios

### 1. 📁[Account Lockout Incident (INC-2026-001)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/INC-2026-001(Account_Lockout).md)
**Key Skills Demonstrated:**

* **Active Directory account management:** Unlocking accounts, credential resets, and user verification.
* **Security log analysis:** Auditing domain controller security logs to trace failed authentication attempts.
* **Group Policy validation:** Verifying and testing account lockout threshold configurations.
* **User communication:** Guiding end users on credential hygiene and security best practices.

### 2. 📁[No Internet Connectivity – DNS Resolution Failure (INC-2026-002)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/INC-2026-002(No_Internet_DNS).md)
**Key Skills Demonstrated:**

* **Network connectivity testing:** Isolating issues using IP pinging vs. domain name resolution tests.
* **DNS configuration validation:** Auditing client network adapter settings and preferred DNS server assignments.
* **DHCP & Cache Management:** Flushing DNS caches (`ipconfig /flushdns`) and executing DHCP lease renewals.
* **Layered network troubleshooting:** Applying OSI model principles to systematically diagnose physical through application layer issues.

### 3. 📁[APIPA Address Assignment – No Network Connectivity (INC-2026-003)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/INC-2026-003(APIPA_Issue).md)
**Key Skills Demonstrated:**

* **DHCP failure detection:** Identifying automatic private IP assignment (`169.254.x.x`) failure states.
* **IP configuration analysis:** Diagnosing network adapter settings, scope exhaustion, and relay configuration.
* **Network adapter troubleshooting:** Resetting network stacks (`netsh winsock reset`) and updating driver bindings.
* **Enterprise connectivity restoration:** Re-establishing dynamic IP lease acquisition from the DHCP server.

### 4. 📁[Network Drive Not Appearing / Not Mapping (INC-2026-004)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/INC-2026-004(Network_Drive_Not_Mapping).md)
**Key Skills Demonstrated:**

* **Group Policy Preferences:** Auditing Drive Maps GPO settings and targeting rules.
* **Active Directory group-based access control:** Validating user membership in security groups required for share access.
* **NTFS and share permission validation:** Confirming proper Effective Access permissions across network storage.
* **SMB file services troubleshooting:** Testing file share reachability and resolving UNC path mapping conflicts.

### 5. 📁[Password Reset & Account Access Restoration (REQ-2026-001)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/REQ-2026-001(Password_Reset).md)
**Key Skills Demonstrated:**

* **Secure password reset procedures:** Performing administrative resets adhering to identity verification protocols.
* **Active Directory account validation:** Auditing user account flags (e.g., "Password Never Expires", "User Must Change Password at Next Logon").
* **User identity verification workflows:** Verifying request authenticity before issuing temporary credentials.
* **Security best practices:** Documenting administrative audit trails and updating knowledge base procedures.

## Documentation & Methodology

Each ticket scenario adheres to industry-standard ITSM and technical writing practices:

* **Professional Technical Communication:** Structured messaging tailored for both technical escalation teams and end-user communication.
* **Enterprise SLA & Escalation Logic:** Priority-based categorization (P1–P3) following ITIL incident management frameworks.
* **Auditable Troubleshooting Records:** Step-by-step diagnostic workflows formatted for direct integration into IT Knowledge Base (KB) or ticketing systems (e.g., ServiceNow, Jira Service Management).
* **Applied Technical Execution:** Verifiable hands-on troubleshooting performed within an Active Directory home lab environment.

## Notes
All usernames, departments, and identifiers are fictional and used solely for educational and portfolio demonstration purposes.
