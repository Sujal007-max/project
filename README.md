# 🔐 Network Security Assessment Report

> **Cybersecurity Internship Project — Option 1**  
> Conducted by: Junior Security Analyst  
> Organization: TechSoft Solutions Pvt. Ltd. *(Hypothetical — for academic purposes only)*  
> Date: June 26, 2026

---

## 📋 Project Overview

This project is part of a **Cybersecurity Internship** program. The objective was to act as a **Junior Security Analyst** and perform a complete network security review for a small organization.

The assessment was conducted **ethically and academically** — no real systems were tested or scanned. All findings are based on documentation, analysis, and application of cybersecurity concepts.

---

## 📁 Repository Structure

```
network-security-assessment/
│
├── 📄 README.md                          ← You are here
├── 📄 LICENSE                            ← MIT License
├── 📄 .gitignore
│
├── 📂 report/
│   └── 📝 Network_Security_Assessment_Report.docx   ← Main deliverable
│
├── 📂 docs/
│   ├── 📄 methodology.md                 ← Assessment methodology details
│   ├── 📄 risk-matrix.md                 ← Risk rating framework
│   └── 📄 network-topology.md            ← Hypothetical network diagram (text)
│
├── 📂 assets/
│   └── 📄 vulnerability-summary.md       ← Quick reference of all findings
│
└── 📂 scripts/
    └── 📄 checklist.md                   ← Security hardening checklist
```

---

## 🎯 Project Tasks Completed

| Task | Status |
|------|--------|
| ✅ Identify network components | Done |
| ✅ List possible network threats | Done |
| ✅ Analyze risks (open ports, weak passwords, unsecured Wi-Fi) | Done |
| ✅ Recommend defensive measures | Done |
| ✅ Write professional assessment report | Done |

---

## 📊 Risk Summary

| Risk Level | Count | Description |
|------------|-------|-------------|
| 🔴 **Critical** | 3 | Immediate action required |
| 🟠 **High** | 4 | Address within 30 days |
| 🟡 **Medium** | 5 | Address within 90 days |
| 🟢 **Low** | 2 | Address as resources permit |
| **Total** | **14** | Vulnerabilities identified |

---

## 📑 Report Structure

The main report (`/report/Network_Security_Assessment_Report.docx`) follows this structure:

1. **Executive Summary** — Risk scorecard and overview
2. **Introduction** — Purpose, methodology, and approach
3. **Scope of Assessment** — Network components and boundaries
4. **Identified Risks** — 14 vulnerabilities with risk ratings
5. **Analysis & Explanation** — Detailed breakdown of each finding
6. **Recommended Security Measures** — 12 actionable recommendations
7. **Conclusion** — Phased action plan (0–90 days)
8. **Appendix** — Glossary and references

---

## 🛡️ Key Vulnerabilities Found

### 🔴 Critical
- **V-01** — Flat network topology (no segmentation) — affects entire network
- **V-02** — Unpatched operating systems and software — workstations & servers
- **V-03** — Unsecured Guest Wi-Fi on same network segment — wireless APs

### 🟠 High
- **V-04** — Default/weak passwords on network devices
- **V-05** — No Multi-Factor Authentication (MFA)
- **V-06** — Open and unmonitored ports (Telnet 23, FTP 21, RDP 3389)
- **V-07** — No Intrusion Detection System (IDS/IPS)

### 🟡 Medium
- **V-08** — Unencrypted HTTP traffic
- **V-09** — No backup and recovery policy
- **V-10** — Outdated WPA2/TKIP Wi-Fi encryption
- **V-11** — No employee cybersecurity awareness training
- **V-12** — IoT devices not isolated

### 🟢 Low
- **V-13** — Physical access to server room not restricted
- **V-14** — No formal Acceptable Use Policy

---

## ✅ Top Recommendations

| Priority | Recommendation | Timeline | Cost |
|----------|---------------|----------|------|
| 🔴 Critical | Implement VLANs for network segmentation | 0–30 days | Low |
| 🔴 Critical | Change all default credentials | Immediate | Free |
| 🔴 Critical | Patch all systems and software | 0–30 days | Free |
| 🟠 High | Close unnecessary ports (Telnet, FTP, RDP) | 0–30 days | Free |
| 🟠 High | Enable MFA on all accounts | 30–60 days | Low |
| 🟠 High | Deploy IDS/IPS (Snort/Suricata/Wazuh) | 30–60 days | Free |
| 🟡 Medium | Enforce HTTPS/TLS everywhere | 30–90 days | Free |
| 🟡 Medium | Implement 3-2-1 backup strategy | 30–60 days | Medium |
| 🟡 Medium | Employee cybersecurity training | 60–90 days | Low |

---

## 🔧 Tools & Concepts Applied

- **Network Analysis**: VLAN design, firewall rules, port scanning concepts
- **Risk Assessment**: NIST risk rating framework (Likelihood × Impact)
- **Security Frameworks**: NIST CSF 2.0, CIS Controls v8, OWASP Top 10
- **Defensive Technologies**: IDS/IPS, MFA, TLS/HTTPS, VPN, network segmentation
- **Compliance**: India IT Act 2000, general data protection principles

---

## ⚖️ Ethical Guidelines Followed

> ✔️ No real or live systems were tested or scanned  
> ✔️ All analysis is based on a **hypothetical** network scenario  
> ✔️ Report is created strictly for academic and learning purposes  
> ✔️ All recommendations follow legal and ethical security practices  
> ✔️ No exploitation or active attack techniques were used

---

## 📚 References

- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [CIS Controls v8](https://www.cisecurity.org/controls/v8)
- [Verizon DBIR 2024](https://www.verizon.com/business/resources/reports/dbir/)
- [India IT Act, 2000](https://meity.gov.in/content/information-technology-act)
- [Snort IDS](https://www.snort.org/)
- [Wazuh SIEM](https://wazuh.com/)

---

## 👤 Author

**Junior Security Analyst**  
Cybersecurity Internship Program  
*June 2026*

---

<div align="center">

**⭐ If this project helped you, please star the repository!**

*This project was created for educational purposes only. Not for use in production environments.*

</div>
