# Hi, I'm Gatanna (Gatan)

**Security analyst focused on threat detection, incident response and malware analysis.**
BSc Computer Science, Strathmore University (2026) · Kenya

I attack my own lab, then build the detections and hunts that would have caught me.

<a href="https://www.linkedin.com/in/gatanna-waruinge-807413290"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?style=flat-square&logo=linkedin&logoColor=white" /></a>

---

### Certifications
CompTIA **CySA+** · CompTIA **Security+** · Africahackon 6-month cybersecurity training program

---

### Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [**DeepPhish**](https://github.com/Gatan501st/DeepPhish) | Explainable multimodal phishing detection: fine-tuned BERT for email text, an MLP URL classifier (16 features), VirusTotal enrichment, attachment hash checks, and Gmail / Proton Mail extensions | Python, Flask, PyTorch, Transformers, scikit-learn, Supabase |
| [**Home SOC Lab**](https://github.com/Gatan501st/home-soc-lab) | Segmented lab (Kali, Windows 11, Windows 10 Enterprise, FLARE VM, REMnux) feeding Wazuh with Sysmon telemetry; custom detection rules mapped to MITRE ATT&CK; endpoint hunting with Velociraptor | Wazuh, Sysmon, Velociraptor, VirtualBox |
| [**crAPI API Pentest**](https://github.com/Gatan501st/crapi-api-pentest) | Full penetration test report with 9 findings (BOLA, SSRF, mass assignment, JWT flaws, data exposure) mapped to the OWASP API Security Top 10 (2023) | ffuf, jwt_tool, Arjun, mitmproxy, Postman |
| [**Azure RDP Honeypot**](https://github.com/Gatan501st/azure-rdp-honeypot) | Internet-exposed VM sending failed RDP logons to Microsoft Sentinel, enriched with geolocation by a PowerShell script and plotted on a live attack map | Azure, Microsoft Sentinel, KQL, PowerShell |
| [**Ransomware IR Mapping**](https://github.com/Gatan501st/ir-ransomware-mapping) | ATT&CK techniques from a ransomware kill chain mapped to NIST CSF 2.0 functions and CIS Controls v8 for an incident response report | MITRE ATT&CK, NIST CSF 2.0, CIS v8 |

### Currently building
- **Cowrie SSH honeypot + Pi-hole** on a Raspberry Pi 4, with a dashboard for attacker sessions and DNS data
- **AI-assisted SOC tooling:** a Wazuh alert triage assistant, a Cowrie session analyst, and a CISA KEV → Velociraptor hunt pipeline with human approval before any hunt runs

---

### Toolkit

**Detection & response:** Wazuh · Microsoft Sentinel (KQL) · Sysmon · Velociraptor
**Malware analysis:** FLARE VM · REMnux
**Adversary emulation (for purple teaming):** Kali Linux · Metasploit · PowerShell Empire · C2 concepts (Sliver, Mythic, Havoc)
**Web & API testing:** OWASP Web & API Top 10 · ffuf · jwt_tool · mitmproxy · Postman
**Frameworks:** MITRE ATT&CK · NIST CSF 2.0 · CIS Controls v8
**Languages:** Python · PowerShell · Bash

---

<sub>All offensive work is done in isolated labs or on intentionally vulnerable targets.</sub>
