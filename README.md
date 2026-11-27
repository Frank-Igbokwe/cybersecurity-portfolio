# Frank N. Igbokwe — Applied Cybersecurity & Threat Intelligence Portfolio

[![Live Portfolio](https://img.shields.io/badge/Live_Site-GitHub_Pages-0ea5e9?style=for-the-badge&logo=github)](https://frank-igbokwe.github.io/cybersecurity-portfolio/)
[![SANS ISC Diary](https://img.shields.io/badge/SANS_ISC-Diary_%2333306-10b981?style=for-the-badge)](https://isc.sans.edu/diary/33306)
[![GIAC Certified](https://img.shields.io/badge/GIAC-7x_Certified-38bdf8?style=for-the-badge)](https://github.com/Frank-Igbokwe)
[![Sponsor](https://img.shields.io/badge/GitHub-Sponsors-f472b6?style=for-the-badge&logo=githubsponsors)](https://github.com/sponsors/Frank-Igbokwe)

> **Live Interactive Portfolio:** [https://frank-igbokwe.github.io/cybersecurity-portfolio/](https://frank-igbokwe.github.io/cybersecurity-portfolio/)

Applied Cybersecurity Engineer, Cloud Penetration Tester, Threat Intelligence & MSSP Architect, SANS Internet Storm Center (ISC) Intern & Co-Author, and U.S. Army & Air Force Veteran (Operation Noble Eagle).

---

## About & CTF Reflection

With 18+ years in clinical healthcare operations as a Licensed Practical Nurse (LPN) and service in the U.S. Army and U.S. Air Force, I bring mission-critical discipline, calm triage under pressure, and respect for system availability into cybersecurity as a B.S. in Applied Cybersecurity candidate at the SANS Technology Institute.

Competing in Capture The Flag (CTF) exercises—including the National Cyber League (NCL) Fall 2026 season and the 2026 NSA Codebreaker Challenge—has sharpened my ability to filter noisy telemetry, test hypotheses under time constraints, and automate repetitive analysis in Python. In compliance with CTF rules, I do not publish public NCL challenge write-ups or live 2026 NSA Codebreaker answers/solutions, instead highlighting verified score reports, badges, and defensive engineering workflows.

---

## Featured Systems & Research

- **`Honeypot-Omaha` Enterprise Threat Intelligence & MSSP Platform:** Multi-tenant detection and response pipeline ingesting AWS EC2 DShield and Cowrie SSH/Telnet telemetry into PostgreSQL / SQLite WAL, featuring a four-display PyQt6 command dashboard, FastAPI portal, Scikit-Learn Isolation Forest UEBA anomaly detection, PCAP reconstruction, and SOAR / STIX 2.1 / SIEM CEF exports.
- **[`honeypot-omaha-batch` (`batch.py`)](https://github.com/Frank-Igbokwe/honeypot-omaha-batch):** Source-available (BSL-1.1) automated log parsing and multi-source OSINT enrichment pipeline (`ip-api.com`, `cve.org`, VirusTotal, Shodan).
- **RIPLE Incident Lifecycle Taxonomy:** Structured post-compromise methodology (*Reconnaissance, Initial exploitation, Persistence-Privilege escalation, Lateral movement, Exfiltration of data*) bridging SOC triage and CISO risk reporting.
- **[SANS ISC Guest Diary #33306](https://isc.sans.edu/diary/33306):** Co-authored with Dr. Johannes Ullrich on empirical honeypot attack patterns and automated telemetry triage.
- **National Cyber League (Fall 2026):** Team *SANS.edu Ctrl+Alt+Defeat* — 223rd / 3,034 teams (93rd percentile overall, 86% accuracy); Individual — 819th / 5,961 players (87th percentile, 1,930 pts); 99th percentile Password Cracking, 98th percentile Log Analysis & Network Traffic Analysis ([Cyber Skyline Report Portal](https://cyberskyline.com/report), Report ID: `VWKN7BLDBFMP`).
- **NSA Codebreaker Challenge (2026):** Earned the **Task 1 Badge** for Linux host/syslog and memory forensics investigation.

---

## Verified Credentials

- **7x GIAC Certified:** `GCPN` &bull; `GCIA` &bull; `GCIH` &bull; `GPYC` &bull; `GSEC` &bull; `GISF` &bull; `GFACT`
- **Education:** B.S. in Applied Cybersecurity (Candidate), SANS Technology Institute &bull; A.S. in Information Technology
- **Service & Healthcare:** U.S. Army & U.S. Air Force Veteran (Operation Noble Eagle) &bull; Licensed Practical Nurse (LPN, 18+ years clinical operations)

---

## Local Preview

No build step or external Node dependencies are required—`index.html` is a self-contained single-page application.

```bash
git clone [https://github.com/Frank-Igbokwe/cybersecurity-portfolio.git](https://github.com/Frank-Igbokwe/cybersecurity-portfolio.git)
cd cybersecurity-portfolio
python3 -m http.server 8080
