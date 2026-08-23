<div align="center">

# Shankar Baral

**Junior SOC / Cyber Security Analyst** | Microsoft Sentinel · Splunk · KQL · SPL · Azure

Canberra, ACT, Australia · Australian Permanent Resident · open to relocation and remote

[![LinkedIn](https://img.shields.io/badge/LinkedIn-shankarbaral1-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shankarbaral1)
[![Email](https://img.shields.io/badge/Email-shankarbaral1@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:shankarbaral1@gmail.com)

</div>

---

## About

I have a Master of Information Technology in Cyber Security from Charles Sturt University (GPA 4.92) and work in IT support at Extratech in Canberra. Most of my security experience comes from labs I have built and run myself, mainly around SIEM, detection engineering and incident response with Microsoft Sentinel and Splunk.

- Currently working towards a junior SOC analyst role in Australia
- Preparing for the Microsoft SC-200 exam, planned for Q4 2026
- Day job covers Entra ID access management, Intune and general IT operations

The six projects below are the best picture of what I can do. Each repository documents the setup, the queries I wrote, the problems I hit, and screenshots of the results.

## Tech stack

**Security and SIEM**

![Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-00B4D8?style=flat&logo=microsoftazure&logoColor=white)
![SPL](https://img.shields.io/badge/SPL-FF6B35?style=flat&logo=splunk&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-E63946?style=flat&logo=shield&logoColor=white)

**Cloud and identity**

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Intune](https://img.shields.io/badge/Microsoft_Intune-0078D4?style=flat&logo=microsoft&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat&logo=microsoftoffice&logoColor=white)

**Automation**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Logic Apps](https://img.shields.io/badge/Logic_Apps-5C2D91?style=flat&logo=azure&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)

## Projects

**[Dual-SIEM Detection Lab](https://github.com/shank078/Dual-SIEM-Detection-Lab)** — Sentinel · Splunk · KQL · SPL · MITRE ATT&CK

A Windows Server honeypot on Azure sending the same Windows Security Events to Microsoft Sentinel and Splunk Enterprise at the same time. I wrote five detections in both KQL and SPL, covering brute force, account lockout, geo-anomaly, privilege escalation and new-user persistence, and mapped each one to MITRE ATT&CK. The Sentinel analytic rule generated incidents on its own from real traffic. The repo also has a write-up comparing how the two platforms handled the same detection logic.

**[Azure Sentinel Honeypot SIEM](https://github.com/shank078/azure-sentinel-honeypot-siem)** — Sentinel · KQL · PowerShell · Azure Workbooks

An intentionally exposed Windows Server 2022 VM that recorded over 1,400 failed RDP logins from more than six countries during the observation window. I wrote a PowerShell script that enriches each failed logon event with geolocation data from an API, ingested the output into a custom Log Analytics table, and built a Sentinel workbook that plots the attack sources on a map.

**[Azure Sentinel to Jira SOAR Pipeline](https://github.com/shank078/azure-sentinel-jira-soar-pipeline)** — Sentinel · Logic Apps · Jira REST API · KQL

An automated path from detection to ticket. A KQL analytics rule picks up repeated failed Entra ID sign-ins, a Sentinel automation rule triggers a Logic App playbook, and the playbook creates a Jira ticket through the REST API with the incident details already mapped into the fields. I built it to understand how SOAR automation cuts down the manual steps between an alert firing and a ticket existing.

**[Azure Identity Security Lab](https://github.com/shank078/azure-identity-security-lab)** — Entra ID · MFA · Sign-in and Audit Logs · Incident Response

An account-takeover exercise in Entra ID. I used the gap between MFA being enabled and MFA being enforced to take over a test account, then investigated it from the defender side: found the impossible-travel sign-in, rebuilt the timeline from the Sign-in and Audit logs, and worked through containment and recovery (session revocation, removing the rogue MFA method, password reset), following the NIST 800-61 incident response phases.

**[Splunk SOC Detection Lab](https://github.com/shank078/Splunk-SOC-Detection-Lab)** — Splunk Enterprise · SPL · Windows Security Events · Azure

A standalone Splunk Enterprise deployment on an Azure Windows Server that was exposed to the internet. Splunk ingested 28,963 Windows Security events during the exposure window, and my SPL queries isolated four attacker IPs from that volume. I correlated failed logins (event 4625) with the resulting account lockout (event 4740), and when the brute-force attempts locked out the admin account I recovered it out-of-band with Azure RunCommand.

**[Fabric Fleet Telemetry Pipeline](https://github.com/shank078/fabric-fleet-telemetry-pipeline)** — Microsoft Fabric · KQL · Data Activator

KQL practice on streaming data through the Kusto Detective Agency challenge. The part worth reading is the query iteration: my first rule had no threshold and sent 15 alerts in under ten minutes, and I worked through three versions before landing on one that only fired on real anomalies. Same tuning process a Sentinel analytics rule needs, just on bus telemetry instead of security logs.

## Certifications

| Certification | Issuer | Status |
|---|---|---|
| CompTIA Security+ | CompTIA | [Completed, August 2026](https://www.credly.com/badges/05f0affe-6096-4799-ae2e-7470b3d3c9aa/public_url) |
| Google Cybersecurity Professional Certificate | Coursera | [Completed, July 2026](https://www.coursera.org/verify/professional-cert/H85P6FVY3LZP) |
| Pre Security | TryHackMe | [Completed](https://tryhackme.com/certificate/THM-W0IURVWPR8) |
| SC-200: Security Operations Analyst | Microsoft | Preparing, exam planned Q4 2026 |

## Education

**Master of Information Technology (Cyber Security)** — Charles Sturt University, GPA 4.92
Coursework included digital forensics, cloud security, threat intelligence and data mining.

**Bachelor of Computer Science and Mathematics** — Birendra Multiple Campus

## Experience

**IT Support Specialist — Extratech** (June 2025 to present)

- Handle 30+ support escalations a day across an enterprise Microsoft environment
- User and access management in Entra ID (IAM and RBAC) and endpoint management with Intune
- Work aligned to the ASD Essential Eight

**Operations Support Specialist — Calvary Hospital** (July 2022 to May 2025)

- Handled clinical and administrative data under the Australian Privacy Principles
- Focused on data accuracy and correct handling of sensitive information

---

<div align="center">

[LinkedIn](https://linkedin.com/in/shankarbaral1) · [Email](mailto:shankarbaral1@gmail.com) · [GitHub](https://github.com/shank078)

</div>
