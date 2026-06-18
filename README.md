<div align="center">

# Shankar Baral
### Junior Cyber Security Analyst | SOC | Microsoft Sentinel | Splunk | KQL | Azure

**Australian Permanent Resident · Canberra, ACT · Open to Sydney / Remote**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-shankarbaral1-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shankarbaral1)
[![Email](https://img.shields.io/badge/Email-shankarbaral1@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:shankarbaral1@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Pre_Security_✓-212C42?style=flat&logo=tryhackme&logoColor=white)](https://tryhackme.com/certificate/THM-W0IURVWPR8)
[![GitHub](https://img.shields.io/badge/GitHub-shank078-181717?style=flat&logo=github&logoColor=white)](https://github.com/shank078)

</div>

---

## 👋 About Me

Master of Information Technology (Cyber Security) graduate **(GPA 4.92)** working as an IT Support Specialist at Extratech while transitioning into a dedicated SOC analyst role.

I don't just study security — I build systems, expose them to live internet threats, and engineer the detections to stop them.

- 🛡️ Running a **live Azure honeypot** — 1,400+ real brute-force attempts captured, enriched, and mapped from 6+ countries
- 🔭 Built a **Dual SIEM Detection Lab** — identical detection logic across Microsoft Sentinel (KQL) and Splunk Enterprise (SPL) simultaneously
- ⚡ Deployed **zero-touch SOAR pipelines** — automated Jira ticketing via Logic Apps and piloting AI-driven tier-1 triage via IBM watsonx Orchestrate agents
- 📚 Pursuing **CompTIA Security+** (July 2026) · **SC-200** (Q3 2026) · **BTL1** (Q4 2026)
- 🎯 Targeting **Junior SOC Analyst** roles in Australia

---

## 🛠️ Tech Stack

**Security & SIEM**

![Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-00B4D8?style=flat&logo=microsoftazure&logoColor=white)
![SPL](https://img.shields.io/badge/SPL-FF6B35?style=flat&logo=splunk&logoColor=white)
![MITRE](https://img.shields.io/badge/MITRE_ATT%26CK-E63946?style=flat&logo=shield&logoColor=white)
![Log Analytics](https://img.shields.io/badge/Log_Analytics-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**Cloud & Identity**

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Intune](https://img.shields.io/badge/Microsoft_Intune-0078D4?style=flat&logo=microsoft&logoColor=white)
![M365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat&logo=microsoftoffice&logoColor=white)
![Fabric](https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=flat&logo=microsoft&logoColor=white)

**Automation & Tools**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Logic Apps](https://img.shields.io/badge/Logic_Apps-5C2D91?style=flat&logo=azure&logoColor=white)
![watsonx](https://img.shields.io/badge/watsonx_Orchestrate-DF2A5C?style=flat&logo=ibm&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-00A651?style=flat&logo=servicenow&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat&logo=cisco&logoColor=white)

---

## 🚀 Projects

### 🛡️ Dual SIEM Detection Lab
> **Microsoft Sentinel · Splunk Enterprise · KQL · SPL · MITRE ATT&CK · Azure**

Live Windows Server 2022 honeypot simultaneously ingesting into **both** Microsoft Sentinel and Splunk Enterprise. 5 detection rules built in KQL and SPL — brute force, account lockout, geo-anomaly, privilege escalation, persistence. 4 real incidents auto-generated in Sentinel. Real attacker IPs. No simulated data.

**→ Cross-platform query parity across KQL and SPL on live attacker traffic**

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/shank078/Dual-SIEM-Detection-Lab)

---

### 🌍 Global Threat Intelligence Lab — Azure Sentinel & Honeypot
> **Microsoft Sentinel · KQL · PowerShell · Azure Workbooks · IP Geolocation API**

Exposed a Windows Server 2022 VM to the raw internet, then built a full SIEM pipeline with custom PowerShell scripts enriching every failed RDP event with geolocation data. Visualised on a live SOC dashboard with dual-state urgency logic (🔴 last 30 min / 🟡 last 24h).

**→ 1,400+ real brute-force attempts from 6+ countries mapped in real time**

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/shank078/azure-sentinel-honeypot-siem)

---

### ⚡ Cloud-Native SOAR Pipeline — Sentinel to Jira
> **Microsoft Sentinel · Azure Logic Apps · Jira REST API · KQL · SOAR**

Zero-touch incident response pipeline — Sentinel detects a brute-force attack, fires an analytic rule, triggers a serverless Logic App playbook, and autonomously creates a fully contextualised Jira ticket in the SOC queue. No analyst touch required from detection to ticket.

**→ Mean Time to Ticket: seconds. Manual effort: zero.**

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/shank078/azure-sentinel-jira-soar-pipeline)

---

### 🔐 Azure Identity Security & Incident Response Lab
> **Microsoft Entra ID · MFA · Sign-in Logs · Audit Logs · Incident Response**

Full red team compromise and blue team recovery — one person, both hats. Exploited the MFA *enabled* vs MFA *enforced* gap to perform a complete account takeover using credential theft and MFA hijacking. Then switched hats: detected impossible travel (Australia → Seattle), rebuilt the full attack timeline from Sign-in and Audit Logs, and executed a complete IR cycle — Contain → Eradicate → Recover → Document.

**→ Zero malware. Zero exploits. Just timing, stolen credentials, and a misconfigured control.**

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/shank078/azure-identity-security-lab)

---

### 🔎 Splunk SOC Detection Lab
> **Splunk Enterprise · SPL · Windows Security Events · Azure · Incident Response**

Standalone Splunk Enterprise SIEM deployment on Azure catching live brute-force attacks against an exposed Windows Server. Custom SPL queries correlating EventID 4625 → 4740 (failed login → lockout lifecycle). 28,963+ events ingested. 4 attacker IPs across 3 countries isolated. Emergency account recovery via Azure RunCommand when the attacker succeeded in locking out the admin.

**→ 28,963 events ingested · 4 attacker IPs isolated · live incident response executed**

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/shank078/splunk-soc-detection-lab)

---

### 🚌 Real-Time Fleet Telemetry Pipeline — Microsoft Fabric
> **Microsoft Fabric · KQL · Data Activator · Eventhouse · Eventstream**

Built a real-time anomaly detection pipeline on live streaming transit telemetry — same architecture as a Sentinel analytic rule but on Fabric's Eventstream engine. Iterated through 3 versions of KQL detection logic and resolved alert fatigue through threshold tuning (0 threshold → 15 spam alerts in minutes → >1h too strict → >30min optimal). Case solved ✅

**→ Same KQL pattern used in Microsoft Sentinel analytic rules — applied to live IoT streaming data**

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/shank078/fabric-fleet-telemetry-pipeline)

---

## 📜 Certifications

| Certification | Issuer | Status |
|---|---|---|
| 🔵 Blue Team Level 1 (BTL1) | Security Blue Team | In Progress — Target Q4 2026 |
| 🔵 SC-200: Security Operations Analyst | Microsoft | In Preparation — Target Q3 2026 |
| 🔵 CompTIA Security+ | CompTIA | Exam Booked — July 2026 |
| ✅ Pre Security | TryHackMe | Completed May 2026 |

---

## 🎓 Education

**Master of Information Technology (Cyber Security)**
Charles Sturt University · GPA 4.92
*Digital Forensics · Cloud Security · Threat Intelligence · Dark Web · Data Mining*

**Bachelor of Computer Science & Mathematics**
Birendra Multiple Campus · First Division

---

## 💼 Experience

**IT Support Specialist** — Extratech *(June 2025 – Present)*
30+ daily escalations · IAM & RBAC via Entra ID · Endpoint management via Intune · ASD Essential Eight alignment

**Operations Support Specialist** — Calvary Hospital *(July 2022 – May 2025)*
Clinical data integrity · 100% Australian Privacy Principles compliance · Zero breaches across entire tenure

---

<div align="center">

*Always building. Always learning. Open to Junior SOC Analyst opportunities in Australia.*

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shankarbaral1)

</div>
