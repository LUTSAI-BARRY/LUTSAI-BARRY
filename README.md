python3 << 'EOF'
content = """# Barry Lutsai — SOC Analyst & Cybersecurity Consultant

## 🛡️ About Me

I'm a SOC Analyst and Systems Administrator based in Nairobi, Kenya, with hands-on experience in multi-site network infrastructure management, threat detection, and incident response. I'm also the founder of **Guiardzen Cybersecurity Consultancy**, providing SOC monitoring, security audits, and awareness training to SMEs across East Africa.

Currently pursuing a **BSc in Information & Cybersecurity** at Riara University (2027) and actively building toward **CySA+** and **EC-Council CSA** certifications.

---

## 🚀 Featured Projects

### [Executive Account Threat Monitor](https://github.com/LUTSAI-BARRY/exec-account-monitor)
Real-time SOC monitoring system detecting attacks on executive accounts — brute force, impossible travel, MFA tampering, phishing, and suspicious forwarding rules. Built with Python, Elasticsearch, and Kibana.

### [SME Threat Intelligence Dashboard](https://github.com/LUTSAI-BARRY/SME-Threat-Intel)
Live network threat detection platform for East African SMEs. Pulls real threat feeds from abuse.ch, detects C2 beacons, ransomware C2, data exfiltration, and botnet activity. Built with Python and Flask.

---

## 🛠️ Skills

**SOC & Detection:** SIEM (Wazuh, Splunk, Elasticsearch/Kibana), Threat Hunting, Incident Response, MITRE ATT&CK, Log Analysis, IDS/IPS

**Infrastructure:** Network Administration (Ruijie/Reyee), Multi-site Network Management, Linux (Ubuntu, Kali), Windows Server

**Offensive Security:** Penetration Testing, Bug Bounty (HackerOne: lutsai007 | Bugcrowd: 7UT5A1), Burp Suite, Metasploit, Nmap

**Development:** Python, Bash, REST APIs, Docker, Git

---

## 📜 Certifications

- ✅ CompTIA Security+
- ✅ ISO/IEC 27001:2022 Lead Auditor
- ✅ Cisco CCST Cybersecurity
- 🔄 CompTIA CySA+ (in progress)
- 🔄 EC-Council CSA (in progress)

---

## 🐛 Bug Bounty

Active researcher on HackerOne and Bugcrowd targeting web application vulnerabilities.
- **HackerOne:** [lutsai007](https://hackerone.com/lutsai007)
- **Bugcrowd:** [7UT5A1](https://bugcrowd.com/7UT5A1)

---

## 🌍 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/barrylutsai/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/LUTSAI-BARRY)

📧 jermainlutsai@gmail.com
🏢 Guiardzen Cybersecurity Consultancy — Nairobi, Kenya
"""

with open("/home/barry/sme-threat-intel/PROFILE_README.md", "w") as f:
    f.write(content)
print("Profile README written")
EOF
