# SentinelHealth Auditor v1.4
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Windows Architecture](https://img.shields.io/badge/Windows-Server%2F10%2F11-0078D6?style=flat&logo=windows&logoColor=white)
![HTML5 / CSS3](https://img.shields.io/badge/HTML5%2FCSS3-Dashboard-E34F26?style=flat&logo=html5&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-Webhooks-2EA44F?style=flat&logo=github&logoColor=white)

Automated System Monitoring & Infrastructure Reporting

## Executive Summary
SentinelHealth is an automated, PowerShell-based auditing suite designed to deliver real-time visibility into Windows endpoint health. The tool bridges the gap between raw system metrics and actionable administrative alerting by generating localized HTML5 diagnostic dashboards and dispatching automated JSON payloads to remote cloud webhooks.

## Core Capabilities & Features

* **Real-Time Resource Monitoring:** Leverages `Get-Counter` sampling for accurate CPU tracking, normalizing data across total processor cores to prevent inflated cumulative load reporting.
* **Accurate System Uptime Detection:** Queries the Windows "Fast Startup" (`Hiberboot`) registry key to differentiate between true kernel reboots and hybrid shutdowns.
* **Multi-Channel Alerting:** Serializes system metric payloads to JSON and transmits instant alerts via Webhook API when endpoints cross critical thresholds (e.g., low disk space, elevated RAM usage).
* **Modern Local Reporting:** Dynamically renders dynamic, high-contrast HTML5/CSS dashboards designed for technical staff and IT management.
* **Cross-Environment Compatibility:** Built using .NET environment classes for path resolution, preventing execution errors on systems with redirected Desktop folders (OneDrive) or customized user profiles.

## Engineering Collaboration & Optimization

Developed with advanced technical scripting techniques, focusing on:

* **UI/UX Refinement:** Engineered responsive CSS layouts to transform raw text output into clear, scannable visual dashboards.
* **Encoding & Performance:** Resolved character encoding edge cases (UTF-8) that caused rendering hangs across varied browser engines.
* **Resource Efficiency:** Optimized polling frequency and array handling within PowerShell to minimize script execution overhead.

## Execution Guide

1. **Configuration:** Add your Webhook URL to the `$WebhookUrl` parameter inside [**SentinelHealth.ps1**](./SentinelHealth.ps1).
2. **Execution:** Run the script in an elevated PowerShell session (requires Administrator privileges for registry and service checks):
   ```powershell
   .\SentinelHealth.ps1
3. Review: Open the generated `SentinelHealth_Report.html` on the local Desktop, or check your configured notification channel for the automated alert payload.