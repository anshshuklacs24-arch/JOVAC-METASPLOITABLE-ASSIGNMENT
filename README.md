# 🔐 Metasploitable 2 Vulnerability Assessment

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Metasploitable%202-blue" />
  <img src="https://img.shields.io/badge/OS-Kali%20Linux-red" />
  <img src="https://img.shields.io/badge/Tool-Nmap-success" />
  <img src="https://img.shields.io/badge/Tool-Nessus-success" />
  <img src="https://img.shields.io/badge/Framework-Metasploit-green" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" />
</p>

---

# 📖 Overview

This repository contains a **professional Vulnerability Assessment Report** performed on the **Metasploitable 2** virtual machine within a controlled laboratory environment.

The assessment follows a structured Vulnerability Assessment and Penetration Testing (VAPT) methodology, including reconnaissance, service enumeration, vulnerability analysis, controlled exploitation, post-exploitation, and remediation planning.

The objective of this project is to demonstrate practical cybersecurity skills by identifying critical security weaknesses, validating them in a safe environment, and documenting appropriate mitigation strategies.

---

# 🎯 Objectives

- Discover active services on the target
- Perform service enumeration
- Identify security vulnerabilities
- Validate vulnerabilities through controlled exploitation
- Assess overall security risk
- Recommend remediation strategies
- Produce a professional vulnerability assessment report

---

# 🛠 Tools Used

| Tool | Purpose |
|-------|----------|
| Nmap | Network Scanning & Service Enumeration |
| Nessus Essentials | Automated Vulnerability Assessment |
| Enum4linux | SMB Enumeration |
| Searchsploit | Exploit Verification |
| Metasploit Framework | Controlled Exploitation |
| Kali Linux | Attacker Machine |

---

# 📂 Repository Structure

```
Metasploitable2-Vulnerability-Assessment/
│
├── Metasploitable2_Vulnerability_Assessment.pdf
├── README.md
└── Screenshots/
```

---

# 📚 Report Contents

- Introduction
- Executive Summary
- Methodology
- Information Gathering
- Network Scanning
- Service Enumeration
- Vulnerability Analysis
- Risk Assessment
- Controlled Exploitation
- Post-Exploitation
- Security Recommendations
- Conclusion
- References

---

# 🔎 Assessment Methodology

```
Information Gathering
          │
          ▼
Network Scanning
          │
          ▼
Service Enumeration
          │
          ▼
Vulnerability Analysis
          │
          ▼
Risk Assessment
          │
          ▼
Controlled Exploitation
          │
          ▼
Post-Exploitation
          │
          ▼
Recommendations
          │
          ▼
Final Report
```

---

# 🚨 Critical Vulnerabilities Identified

| Vulnerability | CVE | Severity |
|--------------|------|----------|
| vsFTPd 2.3.4 Backdoor | CVE-2011-2523 | 🔴 Critical |
| Samba Username Map Script RCE | CVE-2007-2447 | 🔴 Critical |
| UnrealIRCd Backdoor | CVE-2010-2075 | 🔴 Critical |
| Java RMI Server Misconfiguration | N/A | 🔴 Critical |
| Default Bindshell | N/A | 🔴 Critical |
| VNC Default Password | N/A | 🔴 Critical |
| Weak SSL/TLS Configuration | N/A | 🟡 Medium |

---

# 🎯 Skills Demonstrated

- Vulnerability Assessment
- Network Reconnaissance
- Service Enumeration
- Risk Assessment
- Vulnerability Validation
- SMB Enumeration
- Nmap Scripting Engine (NSE)
- Nessus Vulnerability Scanning
- Metasploit Framework
- Technical Documentation
- Cybersecurity Reporting

---

# 📄 Report

The complete assessment report is available in this repository:

**📄 Metasploitable2_Vulnerability_Assessment.pdf**

---

# ⚠ Disclaimer

This repository is intended **strictly for educational purposes**.

All assessments and proof-of-concept exploit demonstrations were performed in an isolated virtual laboratory environment against the intentionally vulnerable **Metasploitable 2** machine.

Do **NOT** attempt these techniques against systems without explicit authorization.

---

# 👨‍💻 Author

**Ansh Shukla**

B.Tech Computer Science & Engineering

Cybersecurity Enthusiast

---

# ⭐ Support

If you found this project useful, consider **starring** ⭐ this repository.

---

```
███╗   ███╗███████╗████████╗ █████╗ ███████╗██████╗ ██╗      ██████╗ ██╗████████╗ █████╗ ██████╗ ██╗     ███████╗
████╗ ████║██╔════╝╚══██╔══╝██╔══██╗██╔════╝██╔══██╗██║     ██╔═══██╗██║╚══██╔══╝██╔══██╗██╔══██╗██║     ██╔════╝
██╔████╔██║█████╗     ██║   ███████║███████╗██████╔╝██║     ██║   ██║██║   ██║   ███████║██████╔╝██║     █████╗
██║╚██╔╝██║██╔══╝     ██║   ██╔══██║╚════██║██╔═══╝ ██║     ██║   ██║██║   ██║   ██╔══██║██╔══██╗██║     ██╔══╝
██║ ╚═╝ ██║███████╗   ██║   ██║  ██║███████║██║     ███████╗╚██████╔╝██║   ██║   ██║  ██║██████╔╝███████╗███████╗
╚═╝     ╚═╝╚══════╝   ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝     ╚══════╝ ╚═════╝ ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═════╝ ╚══════╝╚══════╝

                 🛡️  Secure • Assess • Learn • Improve
```
