# Help Desk Ticket Scenarios 

## Overview

This project simulates real-world (Tier 1 / Tier 2) IT Help Desk ticket workflows within a Windows environment. The goal is to demonstrate structured troubleshooting, clear technical documentation, and professional ticket resolution practices commonly expected in entry-level IT support and technical writing roles.

Each ticket follows a consistent incident-management format, including:

* Issue Identification
* User Impact
* Environment 
* Troubleshooting & Diagnostics
* Root cause analysis
* Resolution 
* Preventative recommendations

All scenarios were executed and documented within a controlled **Active Directory home lab** environment to reflect real enterprise workflows.

## Environment Summary

* **Operating Systems:** Windows 10 Enterprise, Windows Server 2019/2022
* **Directory Services:** Active Directory Domain Services (AD DS)
* **Core Services:** DNS, DHCP, SMB File Services
* **Management Tools:** ADUC, Group Policy Management, PowerShell
* **Authentication & Access Control:** Domain accounts, security groups, NTFS & share permissions

## Ticket Scenarios

### 1. 📁[Account Lockout Incident (INC-2026-001)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/INC-2026-001(Account_Lockout).md)
**Key Skills Demonstrated:**

* Active Directory account management
* Security log analysis
* Group Policy lockout policy validation
* User communication and credential education

### 2. 📁[No Internet Connectivity – DNS Resolution Failure (INC-2026-002)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/INC-2026-002(No_Internet_DNS).md)
**Key Skills Demonstrated:**

* Network connectivity testing (IP vs DNS)
* DNS configuration validation
* DHCP lease renewal and cache flushing
* Layered network troubleshooting methodology

### 3. 📁[APIPA Address Assignment – No Network Connectivity (INC-2026-003)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/INC-2026-003(APIPA_Issue).md)
**Key Skills Demonstrated:**

* DHCP failure detection
* IP configuration analysis
* Network adapter troubleshooting
* Enterprise connectivity restoration

### 4. 📁[Network Drive Not Appearing / Not Mapping (INC-2026-004)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/INC-2026-004(Network_Drive_Not_Mapping).md)
**Key Skills Demonstrated:**

* Group Policy Preferences (Drive Maps)
* Active Directory group-based access control
* NTFS and share permission validation
* SMB file services troubleshooting

### 5. 📁[Password Reset & Account Access Restoration (REQ-2026-001)](https://github.com/water-fountain/IT-Portfolio/blob/main/Help-Desk-Ticket-Scenarios/Tickets/REQ-2026-001(Password_Reset).md)
**Key Skills Demonstrated:**

* Secure password reset procedures
* Active Directory account validation
* User identity verification workflows
* Security best practices and documentation

## Documentation & Methodology

Each ticket was written to reflect:

* Clear, professional technical communication
* Realistic enterprise incident escalation logic (P1–P3)
* Auditable troubleshooting steps suitable for knowledge base or ticketing systems
* Resume-ready demonstration of applied IT support skills

## Notes
All usernames, departments, and identifiers are fictional and used solely for educational and portfolio demonstration purposes.
