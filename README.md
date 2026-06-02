<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/9d2bddb5-ff0d-4fc0-aa9e-4b31591e5ace" />



### 📘 Overview

This lab simulates a **real-world enterprise security breach investigation**, requiring full-spectrum Blue Team analysis across host, network, and SIEM data sources.

The project replicates a SOC analyst workflow responding to a phishing-based compromise, focusing on identifying attacker behavior, correlating telemetry, and producing actionable findings.

**Key Objectives**
- Investigate a simulated phishing-based security breach  
- Identify indicators of compromise (IOCs) across multiple data sources  
- Correlate host, network, and SIEM data  
- Develop remediation and detection recommendations  

---

### 🧰 Tools & Technologies  

| Tool | Purpose |
|---|---|
| Splunk | Log collection, correlation, and SIEM analysis |
| Wireshark | Network traffic analysis |
| TCPDump | Command-line packet inspection |
| Autopsy | Digital forensics and disk analysis |
| DeepBlueCLI | Windows event log threat detection |
| Mandiant Redline | Host-based investigation and artifact analysis |
| Nmap | Network reconnaissance and scanning |
| Linux CLI | System interaction and analysis |

---

### 🏗️ Lab Environment  

| System | Role |
|---|---|
| SOC01 | SIEM / Log Analysis Platform |
| WIN-ENDPT | Compromised User Workstation |
| ATTACK-SIM | Simulated External Threat |
| ANALYSIS-VM | Forensics Workstation |

**Additional Details**
- Segmented internal lab network  
- Logs, PCAPs, and host artifacts used for investigation  

---

### ⏱️ Attack Timeline  

| Time | Activity |
|---|---|
| 09:12 | Phishing email delivered to user |
| 09:15 | Malicious attachment executed |
| 09:17 | Outbound connection to attacker infrastructure |
| 09:25 | Persistence established via registry |
| 09:40 | Suspicious authentication attempts detected |
| 10:05 | Potential lateral movement observed |

---

### 🚶 Walkthrough  

⚙️ **1. Environment Setup**  
**Tasks Performed**
- Deployed lab systems  
- Configured networking and connectivity  
- Installed core analysis tools  

**Outcome**  
Established a stable and functional investigation environment.

---

🔧 **2. Configuration & Administration**  
**Tasks Performed**
- Configured Splunk data ingestion  
- Loaded logs and event data  
- Prepared forensic analysis tools  

**Outcome**  
Enabled centralized monitoring and analysis capability.

---

💻 **3. Automation / Scripting**  
**Tasks Performed**
- Utilized Splunk queries for event filtering  
- Ran TCPDump for targeted packet inspection  
- Leveraged CLI tools for rapid analysis  

**Outcome**
Accelerated detection and correlation of suspicious activity.

---

### 🔍 4. Monitoring / Analysis  

**Tasks Performed**
- Investigated logs within Splunk  
- Analyzed PCAP traffic using Wireshark  
- Examined disk artifacts using Autopsy  
- Validated findings using DeepBlueCLI and Redline  

**Key Indicators of Compromise (IOCs)**
- Malicious IP: `185.243.115.84`  
- Suspicious Domain: `secure-login-update[.]com`  
- File Hash (MD5): `3f5d8a9b2c4e1d6f8a7b9c0d12345678`  
- Suspicious Process: `invoice_viewer.exe`  

**Outcome**  
Confirmed compromise via phishing, with follow-on persistence and outbound communication.

---

### 🔐 5. Validation / Security Testing  

**Tasks Performed**
- Validated detection of malicious activity  
- Verified visibility across SIEM and network tools  
- Confirmed persistence mechanisms  

**Outcome**  
Validated effectiveness of detection and monitoring controls.

---

### 🧠 Security Concepts Demonstrated  

- Incident Response Lifecycle  
- Log Correlation and SIEM Analysis  
- Network Traffic Analysis  
- Digital Forensics and Artifact Analysis  
- Threat Detection and Analysis  

---

### 🛠 Skills Gained  

- Security incident investigation  
- SIEM query development and log correlation  
- Packet-level network analysis  
- Host-based forensic investigation  
- Threat hunting and IOC analysis  
- Documentation and reporting of findings  

---

### 🔍 Results  

- Identified phishing as the initial access vector  
- Correlated activity across host, network, and logs  
- Detected persistence via registry modification  
- Observed outbound command-and-control traffic  
- Produced actionable remediation steps  

---

### 🛡️ Security Analysis / Key Takeaways  

This lab highlights the importance of **multi-source correlation** when investigating security incidents. Individual signals may appear benign, but combined analysis reveals the full attack chain.

**Key Insights**
- SIEM visibility is critical for identifying authentication anomalies  
- Network analysis exposes command-and-control communication  
- Host forensics reveals persistence and execution artifacts  

This exercise reinforces that effective Blue Team operations rely on:
- Strong analytical thinking  
- Cross-domain technical knowledge  
- Familiarity with attacker behavior patterns  

---

### 💼 Resume Bullets  

- Investigated a simulated enterprise security incident using SIEM, network, and forensic tools  
- Performed log correlation and threat detection using Splunk  
- Identified command-and-control traffic via network analysis  
- Conducted host-based forensic analysis to identify persistence mechanisms  
- Developed actionable remediation recommendations based on findings  

---

### 📎 References  

- Security Blue Team Training Material  
- Splunk, Wireshark, and Autopsy Documentation  


