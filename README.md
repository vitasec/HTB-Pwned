# HTB-Pwned: Penetration Testing Lab Notes

![Security Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Platform](https://img.shields.io/badge/Platform-HackTheBox-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

This repository serves as a centralized documentation hub for my methodology, exploit chains, and technical findings while navigating various **Hack The Box** machines.

---

## 🛡 Methodology

My approach follows the standard Penetration Testing Execution Standard (PTES):

1.  **Reconnaissance:** Passive and active information gathering.
2.  **Enumeration:** In-depth service analysis (Nmap, SNMP, LDAP, Web).
3.  **Vulnerability Analysis:** Identifying misconfigurations and known CVEs.
4.  **Exploitation:** Developing or tailoring exploits for Initial Access.
5.  **Privilege Escalation:** Vertical and horizontal movement within the system.
6.  **Post-Exploitation:** Loot collection and persistence analysis.

---

## 📂 Repository Structure

```text
.
├── Active-Machines/       # Ongoing investigations (Hidden/Encrypted)
├── Retired-Machines/      # Complete write-ups and scripts
│   ├── Linux/
│   │   └── [Machine-Name]/
│   └── Windows/
│       └── [Machine-Name]/
├── Scripts/               # Custom automation & exploit wrappers
└── Templates/             # Reusable report and scan templates
