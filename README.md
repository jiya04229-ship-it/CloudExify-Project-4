# 🔐 CloudExify Cybersecurity Internship — Project 04

## Vulnerability Assessment & Remediation

### 📌 Project Overview

This project was completed as part of the **CloudExify Cybersecurity Internship – Month 2, Project 04**. The project focuses on conducting an **authorized vulnerability assessment** using **Tenable Nessus Essentials** in a Kali Linux assessment environment.

A **Basic Network Scan** was performed against the authorized target to identify security weaknesses, detect exposed services and software, analyze vulnerability severity, and document appropriate remediation recommendations.

The assessment followed a structured cybersecurity workflow:

**Target Configuration → Vulnerability Scanning → Service Detection → Vulnerability Analysis → Risk Assessment → Evidence Collection → Remediation Planning**

---

## 🎯 Project Objectives

* Identify security vulnerabilities on the authorized target.
* Detect exposed services and software components.
* Analyze vulnerabilities based on severity and CVSS.
* Examine the potential security impact of identified findings.
* Collect technical evidence from Nessus.
* Document vulnerability findings professionally.
* Provide practical remediation recommendations.
* Develop a security remediation roadmap.

---

## 🛠️ Tools & Technologies

| Tool                          | Purpose                               |
| ----------------------------- | ------------------------------------- |
| **Tenable Nessus Essentials** | Vulnerability scanning and assessment |
| **Kali Linux**                | Cybersecurity assessment environment  |
| **Basic Network Scan**        | Nessus scanning policy                |

---

## 🔎 Assessment Highlights

The Nessus assessment identified security findings associated with multiple services and software components, including:

* SSH
* Apache HTTP Server
* HTTP
* TLS
* MariaDB
* PostgreSQL
* Other detected system components

The scan successfully completed against the authorized target and provided detailed vulnerability and host information.

---

## 🚨 Key Vulnerability

### SSL Certificate Cannot Be Trusted

The primary actionable finding identified during the assessment was:

| Attribute         | Details                           |
| ----------------- | --------------------------------- |
| **Vulnerability** | SSL Certificate Cannot Be Trusted |
| **Severity**      | Medium                            |
| **CVSS Score**    | 6.5                               |
| **Affected Port** | TCP/8834                          |
| **Plugin ID**     | 51192                             |
| **Status**        | Requires Remediation              |

The finding indicates that the SSL/TLS certificate presented by the affected service could not be fully trusted by Nessus. Possible causes include an unrecognized Certificate Authority, an invalid certificate, an incomplete certificate chain, or certificate validation issues.

---

## 🛡️ Remediation

The recommended remediation includes:

1. Obtain or generate a trusted SSL/TLS certificate.
2. Verify certificate validity and expiration.
3. Confirm hostname and certificate matching.
4. Install the complete certificate chain.
5. Configure the affected service with the corrected certificate.
6. Perform a follow-up vulnerability scan.
7. Verify that the vulnerability has been successfully resolved.

---


## 📊 Project Outcome

This project provided practical hands-on experience in:

**Vulnerability Scanning**
→ **Service Enumeration**
→ **Vulnerability Analysis**
→ **CVSS & Risk Assessment**
→ **Evidence Collection**
→ **Security Documentation**
→ **Remediation Planning**

The assessment successfully demonstrated the use of **Tenable Nessus Essentials** for identifying and analyzing security weaknesses within an authorized assessment environment.

---

## 👩‍💻 Author

**Javeria Khan**

**CloudExify Cybersecurity Internship**
**Project 04 — Vulnerability Assessment & Remediation**

**Registration No:** CX-INT-2026-CYB-0525

---

## 🏢 Internship

**CloudExify Cybersecurity Internship Program**

**Project:** 04 — Vulnerability Assessment & Remediation
**Assessment Type:** Authorized Vulnerability Assessment
**Assessment Tool:** Tenable Nessus Essentials
**Environment:** Kali Linux

---

⭐ **Project completed as part of the CloudExify Cybersecurity Internship Program.**
