# Enterprise Active Directory Domain Infrastructure Lab
![Windows Server 2019](https://img.shields.io/badge/Windows_Server_2019-0078D6?style=flat&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat&logo=microsoft&logoColor=white)
![Group Policy](https://img.shields.io/badge/Group_Policy-0078D4?style=flat&logo=windows&logoColor=white)
![DNS & DHCP](https://img.shields.io/badge/DNS%20%26%20DHCP-217346?style=flat&logo=microsoft&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)

## Executive Summary
This project demonstrates the deployment, administration, and security configuration of an enterprise Active Directory Domain Services (AD DS) environment using Windows Server 2019 and virtualized Windows client endpoints.

The lab simulates enterprise production conditions—covering identity lifecycle management, Role-Based Access Control (RBAC), automated Group Policy Objects (GPO), integrated network core services (DNS/DHCP), file share security, and full-stack authentication diagnostics.

## Technical Architecture

![alt text](<images/Technical Arch.png>)

## Core Capabilities & Configurations

### 1. Identity & Access Management (IAM)
* **Tiered OU Architecture:** Designed a scalable Organizational Unit hierarchy separating Administrative Accounts, Standard Users, Workstations, Servers, and Service Accounts.
* **Role-Based Access Control (RBAC):** Configured Global and Domain Local security groups to enforce the Principle of Least Privilege across domain resources.
* **User Lifecycle Management:** Implemented standardized user provisioning, automated account lockouts, credential reset workflows, and pass-through authentication policies.

### 2. Enterprise Policy Automation (GPO)
* **Security Baselines:** Configured and linked GPOs to enforce domain password complexity, account lockout thresholds, and audit logging parameters.
* **Workstation Hardening:** Centralized software restrictions, mapped drive configurations via Group Policy Preferences, desktop constraints, and local firewall deployment.

### 3. Core Network & File Services
* **DNS Administration:** Configured AD-integrated forward/reverse lookup zones, conditional forwarders, and static resource records (A, CNAME, PTR).
* **DHCP Services:** Deployed active DHCP scopes, IP address reservations, dynamic DNS update integrations, and exclusion ranges.
* **Storage & Access Control:** Managed enterprise SMB network shares leveraging Access-Based Enumeration (ABE) and granular NTFS permission structures.

### 4. Diagnostics & Troubleshooting Frameworks
* **Authentication & Joins:** Documented diagnostic steps for domain-join failures, computer account trust relationship breakage, and network stack isolation.
* **Group Policy Diagnostics:** Leveraged CLI utilities (`gpupdate /force`, `gpresult /h`) to verify policy inheritance and resolve link precedence issues.

## Main Lab Guide & Documentation

For the step-by-step configuration workflows, PowerShell commands, and detailed technical procedures, refer to the full guide:

📄 [**Active Directory Home Lab**](./main_active_directory_lab_guide.md)