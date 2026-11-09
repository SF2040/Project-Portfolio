# 🛡️ Cybersecurity Portfolio

> **Hands-on security engineering, cloud infrastructure, detection & IOT projects — built, broken and documented end-to-end.**

Welcome. This repository is the index for my practical cybersecurity work. Rather than coursework screenshots, each project here is something I designed, deployed, tested and documented myself — covering **cloud security, security monitoring & detection, OSINT investigation, digital preservation standards, and embedded/IoT hardware**.

Every project folder contains its objective, architecture, the tools used, what I found, what broke, and what I'd do differently.

## 🤖 USE OF AI
Im happy to say that AI was NOT used for my project ideas or writing.

The only exceptions for use of AI was for
- Part of this README
- Skills summarisation for each project
- PythonGUI code for https://github.com/SF2040/minecraft-server-archive

All writing & research is done by yours truly, I could've easily use AI to cleanup my projects, reformat them and fix spelling etc, but then it would not be my work anymore, and not feel authentic.

<!-- Optional: add badges here, e.g. certifications in progress, TryHackMe/HTB rank, LinkedIn -->

---

## 👤 About Me

**Competent**: ICT50220-AE60 Diploma of Information Technology - 2026

**Competent**: 22603VIC Certificate IV in Cyber Security - 2025

**Working towards:** CompTIA Security+

---

## 📑 Table of Contents
Ranked in order of my favourite & complexity

| # | Project | Domain | Key Skills | Link |
|---|---------|--------|------------|------|
| 1 | Auto Server Archive (4 parts) 17/10/26 |👷🏻 End-To-End Pipeline  | 1. Implementing ISO14721 into a real, automated project     2. Designed an end-to-end automated archiving pipeline for public use | [View](https://github.com/SF2040/Project-Portfolio/blob/main/Minecraft-Server-Archiver-PT1.md) |
| 2 | Minecraft x Splunk (2 parts) 6/11/25 | 💥 Incident Analysis | 1. ATT&CK & NIST Framwork structured report 2. Incident analysis using Splunk | [View](https://github.com/SF2040/Project-Portfolio/blob/main/mcsplunkSETUP.md) |
| 3 | 97% off flagship AI models (2 parts) 29/06/26 | 💻 Infrastructure As Code | 1. System Architecture 2. Cost & Tools optimisation| [View](https://github.com/SF2040/Project-Portfolio/blob/main/AI-Infastructure-PT1.md) |
| 4 | IOT Crypto NerdMiner 15/09/25 | 📱 Internet Of Things Configuration | 1. Configured & deployed IOT device 2. Troubleshooting | [View](https://github.com/SF2040/Project-Portfolio/blob/main/nerdminer.md) |
| 5 | IOT M5StackC 15/09/25 | 🟥 Red Team | 1. Red Team testing with IOT device | [View](https://github.com/SF2040/Project-Portfolio/blob/main/m5stack.md) |
| 6 | AWS Homelab 22/06/25 | ☁️ Cloud Infrastructure | 1. Built & Configured cloud lab environment | [View](https://github.com/SF2040/Project-Portfolio/blob/main/AWS-Homelab.md) |
| 7 | AWS Secure S3 11/10/25 | ☁️ Cloud Infrastructure | 1. Secured storage in cloud environment | [View](https://github.com/SF2040/Project-Portfolio/blob/main/AWS-secure-bucket.md) |
| 8 | Open Source Intelligence 19/06/25 | 📓 Report | 1. Demonstrated gathering open source information | [View](https://github.com/SF2040/Project-Portfolio/blob/main/OSINT.md) |

<!-- Tip: keep "Domain" to one of: Cloud Security · Detection & Monitoring · OSINT · GRC / Standards · Hardware & IoT -->

---

## ⭐ Featured Skills

The core competencies demonstrated across the projects in this portfolio:

| Domain | Demonstrated Capability |
|--------|------------------------|
| **☁️ Cloud Security & Administration** | AWS administration via Console and CLI, IAM users/roles and access-key lifecycle management, RBAC and least-privilege design, S3 hardening (versioning, server-side encryption, bucket policies, access logging), secure multi-tenant access control |
| **📡 Security Monitoring & Detection** | SIEM deployment and configuration (Splunk), log ingestion pipelines, log parsing and correlation, event detection and filtering, alert creation, dashboarding and data visualisation, attacker simulation to validate detections |
| **🚨 Incident Response & Reporting** | Event triage and analysis, evidence cross-verification against source logs, framework-aligned incident reporting, written findings and remediation recommendations |
| **🕵️ OSINT & SOCMINT** | Username and identity investigation, social media account enumeration and data analysis, reverse image search, geolocation and metadata analysis, digital footprint mapping, OSINT tooling selection and operational use |
| **🏗️ Infrastructure & Cloud Architecture** | Multi-tier cloud architecture design, containerised deployment (Docker, Railway), API integration and authentication, VPS and self-hosted model evaluation, migration planning with data integrity and service continuity, cost/performance optimisation |
| **🐍 Scripting & Automation** | Python automation using the standard library only (`argparse`, `zipfile`, `hashlib`, `json`, `csv`, `subprocess`), regex-based log parsing, automated QA checks, Bash/CLI workflows, JSON configuration |
| **🔐 Data Integrity & Forensic Verification** | SHA-256 fixity checksums, tamper detection through deliberate corruption testing, duplicate detection, remote-state verification against expected commit hashes |
| **📋 GRC, Standards & Governance** | Applying ISO 14721 (OAIS) to a live pipeline, conformance mapping, data privacy / residency / third-party exposure assessment, access-rights documentation, log redaction and ethical handling of personal data |
| **🔌 Hardware, Embedded & IoT Security** | ESP32 development and firmware flashing, soldering and hardware assembly, pinout/schematic interpretation, GPIO and SPI/SD-card integration, Wi-Fi/Bluetooth/RF fundamentals, hardware and firmware troubleshooting |
| **📝 Technical Documentation** | Architecture and configuration documentation, beginner and end-user guides, flowcharts, conformance tables, troubleshooting logs and formal written reports |

---

## 🧰 Tools & Technologies

**Cloud & Infrastructure**
`AWS` · `AWS CLI` · `IAM` · `S3` · `CloudTrail/Logging` · `Docker` · `Railway` · `VPS Hosting` · `REST APIs`

**Monitoring & Detection**
`Splunk` · `SPL` · `Log Correlation` · `Dashboards & Alerting` · `Attacker Simulation`

**OSINT**
`Kali Linux` · `Reverse Image Search` · `Username Enumeration` · `EXIF / Metadata Analysis` · `Geolocation Analysis`

**Development & Scripting**
`Python (stdlib)` · `Bash` · `Regex` · `JSON` · `CSV` · `Git` · `GitHub`

**Hardware & Embedded**
`ESP32` · `M5Stack` · `Firmware Flashing` · `Soldering` · `SPI / GPIO` · `3D Printing` · `RF & Wireless`

**Standards & Frameworks**
`ISO 14721 (OAIS)` · `Data Governance & Privacy` · `RBAC / Least Privilege` · `Incident Reporting`

---

## 🔍 Skills in Detail

<details>
<summary><b>☁️ Cloud Security, Architecture & Administration</b></summary>

<br>

- **AWS administration** through both the Management Console and the AWS CLI.
- **IAM & access control** — creating and managing users, tenants and access keys; rotating and revoking credentials; exploring role-based access control and least-privilege models.
- **S3 hardening** — built a secure bucket from scratch with versioning, server-side encryption, restrictive bucket policies and access logging enabled, then documented *why* each control matters.
- **Multi-tier architecture design** — designed and deployed cloud architectures integrating frontend, backend and external third-party services.
- **Containerised deployment** of applications using Docker and Railway.
- **API integration** — configuring endpoints, authentication schemes and third-party AI providers.
- **Cloud migration planning** — mapping out infrastructure moves while preserving data integrity and service continuity.
- **Cost optimisation** — comparing hosting providers, API providers and model performance against operational cost.
- **Infrastructure evaluation** — assessing VPS hosting and self-hosted model options against managed alternatives.
- **Technical troubleshooting** — diagnosing API compatibility, authentication and integration failures.

</details>

<details>
<summary><b>📡 Security Monitoring, Detection & Incident Analysis</b></summary>

<br>

- **SIEM build-out** — stood up and configured a Splunk instance, including data inputs and index configuration.
- **Log pipeline engineering** — installed and configured application plugins and config files to generate and forward real log data, and built an understanding of exactly *how* those logs travel into the SIEM and correlate once there.
- **Organic data generation** — collected genuine, non-synthetic activity data to support an in-depth analytical report rather than relying on sample datasets.
- **Cloud security monitoring** — detection and filtering of security-relevant events in AWS, with alerting configured on top.
- **Threat detection & attacker simulation** — simulated attacker behaviour to test whether monitoring and alerting actually fired.
- **Log analysis & correlation** — parsing application logs, compressed `.gz` archives and tooling logs with regular expressions, then correlating across sources.
- **Evidence cross-checking** — in one investigation, a tool reported a "Download timeout" that contradicted the application's own log; I based the outcome on the primary log evidence rather than the tool's summary.
- **Visualisation, framework implementation and incident reporting** — turning findings into dashboards and a structured written report.

</details>

<details>
<summary><b>📋 Standards, Governance, Integrity & Compliance</b></summary>

<br>

- **Applied ISO 14721 (OAIS)** — mapped a digital preservation standard's functional entities and information model onto a real, working pipeline, with a conformance table to evidence it.
- **NIST & MITRE ATT&CK** - Frameworks used for defensive reports
- **Data integrity & verification** — SHA-256 checksums for every file, tamper detection, and upload confirmation that validates the remote commit against the one pushed.
- **Quality assurance design** — automated checks returning clear, unambiguous outcomes (*complete, incomplete, unverified, rejected*) plus duplicate detection.
- **Metadata & structured data design** — JSON and CSV schemas covering provenance, context, fixity, access rights, packaging and a searchable catalogue.
- **Data governance** — evaluating data privacy, data residency and third-party data exposure risk.
- **Privacy & ethics** — redacting usernames from logs, keeping sensitive repositories private, and explicitly documenting access rights and potential personal data.
- **Testing & validation** — running against sample data, repeat runs for idempotency, and deliberate file tampering to prove the integrity checks genuinely work.
- **Workflow design** — building a repeatable end-to-end process that extends an existing pipeline **without modifying it**.
- **Version control & cloud storage workflows** — Git and GitHub (clone, commit, push, private repos, remote state verification).


</details>

<details>
<summary><b>🕵️ OSINT & SOCMINT Investigation</b></summary>

<br>

- End-to-end OSINT and SOCMINT investigation methodology.
- Social media **account enumeration** and cross-platform correlation.
- **Username and identity investigation** across services.
- **Reverse image searching** and image-based pivoting.
- **Social media data analysis** for behavioural and relational insight.
- **Geolocation investigation**, **metadata/EXIF analysis** and **digital footprint mapping**.
- **Tool selection** — choosing the right tool for the question being asked, and knowing each tool's limits.
- **Kali Linux and Python environment management** for investigative tooling.


</details>

<details>
<summary><b>🔌 Hardware, Embedded Systems & IoT</b></summary>

<br>

**Physical**
- Soldering and hardware assembly, with demonstrated improvement in soldering proficiency.
- Reading and working from **pinout diagrams and schematics**.
- Connecting external modules and wiring **GPIO and peripheral** interfaces.
- Hardware fault diagnosis and troubleshooting.
- 3D printing and enclosure assembly.

**Digital**
- **ESP32 development**, firmware flashing, configuration and deployment.
- Embedded systems fundamentals and constrained-device considerations.
- **Wi-Fi, Bluetooth and RF** concepts in practice.
- **SD card / SPI** integration.
- Firmware troubleshooting and recovery.
- **IoT device configuration** and open-source project research/evaluation.
- Bitcoin and blockchain fundamentals (proof-of-work, hashing, mining pools).

</details>

<details>
<summary><b>📝 Documentation & Communication</b></summary>

<br>

- Architecture, configuration and deployment documentation.
- **Dual-audience user guides** — one written for complete beginners, one for external/technical users.
- Flowcharts and process diagrams.
- Conformance tables mapping controls to standards.
- Troubleshooting write-ups that record what failed and why.
- Formal written reports with findings and recommendations.

</details>

---

## 📬 Contact

<!-- REPLACE with your details -->
- **LinkedIn:** https://www.linkedin.com/in/santo-f-38837b3b9/
- **TryHackMe:** https://tryhackme.com/p/SF5

---

<sub>All projects were built in isolated lab environments or against systems I own. No testing was performed against third-party systems without authorisation.</sub>
