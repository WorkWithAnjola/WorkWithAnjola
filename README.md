### Hi 👋, I'm Anjolaoluwa Toriola

**Cybersecurity | IT Support | Security Operations · Detection · Risk**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat&logo=wazuh&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat&logo=virtualbox&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat&logo=markdown&logoColor=white)

I investigate, I document, and I don't stop until the root cause makes sense. My work spans defensive security operations, DFIR triage, host telemetry auditing, SIEM engineering, and enterprise access governance.
---

### 🚀 Featured Work

🛡️ **[Home SOC Lab](https://github.com/WorkWithAnjola/home-soc-lab)**
Deployed a Wazuh SIEM from the ground up, simulated an SSH bruteforce attack, and caught something most tutorials skip: a real detection failure. Traced it to the root cause, not a rule bug, not a config error, but a monitoring service that hadn't started yet and documented the full investigation with timeline, IOCs, and MITRE ATT&CK mapping.

⚡ **[PowerShell Threat Hunting & Telemetry Engineering](https://github.com/WorkWithAnjola/suspicious-powershell-threat-hunt)**
Enabled Windows Script Block Logging (EID 4104) via GPO to solve visibility gaps around Base64-obfuscated stagers and memory-resident web cradles. Extracted compiled, de-obfuscated script blocks from raw event logs and engineered automated threat hunt queries alongside vendor-agnostic Sigma rules.

☣️ **[Ransomware Investigation Playbook & Triage Simulation](https://github.com/WorkWithAnjola/ransomware-investigation-playbook)**
Simulated LockBit 3.0 precursor tradecraft and data encryption workflows aligned with NIST SP 800-61 Rev. 2. Configured Windows process auditing (EID 4688) to capture living-off-the-land recovery inhibition attacks (`vssadmin`), engineered an automated PowerShell incident triage engine, and authored production-ready Sigma detection rules.

🔍 **[Vendor Risk Assessment](https://github.com/WorkWithAnjola/vendor-risk-assessment)**
Ran a full thirdparty risk review on a SaaS vendor handling payroll data: security questionnaire, SOC 2 report critique, a scored risk register, and a risk acceptance memo with concrete remediation asks, the exact deliverable a GRC team hands to leadership before signing a contract.

📊 **[Splunk Authentication & Brute-Force Detection Dashboard](https://github.com/WorkWithAnjola/splunk-brute-force-dashboard)**
Engineered an operational SOC dashboard in Splunk Enterprise to monitor authentication telemetry and detect distributed brute-force attacks. Built SPL search queries, statistical aggregations, and threshold-based alerting to surface anomalous failed logon spikes (Event ID 4625) and track targeted user accounts.

🌐 **[OSINT Reconnaissance & Attack Surface Mapping](https://github.com/WorkWithAnjola/osint-recon-brightleaf)**
Conducted passive external reconnaissance against a target organization to map its public-facing digital footprint. Enumerated subdomains, identified misconfigured DNS records, harvested employee metadata, and evaluated external exposure risks without active network scanning.

---

### 🔑 [JML Access Audit](https://github.com/WorkWithAnjola/jml-access-audit)
Simulated joiner, mover, and leaver access events for a fictional org in Microsoft Entra ID, then audited the results. Caught two realistic gaps most companies miss: an internal transfer that never had its old access revoked, and a departed employee whose account stayed active days after their last day. Findings mapped to NIST SP 800-53 (AC-2), with full evidence and remediation recommendations.

🎣 **[Phishing Email Forensics](https://github.com/WorkWithAnjola/phishing-email-forensics)**
Investigated a simulated Business Email Compromise attempt targeting a finance manager, using header analysis and SPF/DKIM/DMARC authentication checks to confirm a spoofed sender and lookalike domain. Full writeup includes IOCs, verdict, and remediation recommendations, including a real DMARC policy gap that let the message through undetected.


### 🧰 What I Work With

* **SIEM & Detection:** Splunk Enterprise (SPL, Dashboards, Alerting), Wazuh SIEM, Sigma Rules, Windows Event Telemetry (EID 4625, 4688, 4104), Sysmon, MITRE ATT&CK.
* **Forensics & Threat Hunting:** DFIR Triage, PowerShell Scripting, Host Artifact Analysis, Network Packet Inspection (Wireshark), Passive OSINT.
* **Identity & Governance:** Microsoft Entra ID (Azure AD), NIST SP 800-53, NIST SP 800-30, SOC 2 Type I/II Reviews, Vendor Risk Management.
* **Systems:** Linux (Ubuntu Server), Windows 11 Enterprise, VirtualBox virtualization.
---

### 📇 Contact me

• Email: workwithanjy22@gmail.com
• LinkedIn: https://www.linkedin.com/in/anjolaoluwa-toriola-115211423?utm_source=share_via&utm_content=profile&utm_medium=member_ios
---

![GitHub stats](https://github-readme-stats.vercel.app/api?username=WorkWithAnjola&show_icons=true&theme=default&hide_title=true)

