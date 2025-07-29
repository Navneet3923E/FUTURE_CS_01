# FUTURE_CS_01

# ✅ Internship Task - 1 Completed

> Vulnerability Assessment of DVWA using OWASP ZAP

---

# 🔍 DVWA Vulnerability Scan using OWASP ZAP

This repository contains the results of a **web application vulnerability assessment** performed on [DVWA (Damn Vulnerable Web Application)](http://www.dvwa.co.uk/) using the **OWASP ZAP** automated security scanner.

## 📁 Project Structure

```
/DVWA-ZAP-Scan/
│
├── zap-report.html        # Full ZAP HTML scan report
├── screenshots/           # Screenshots of the findings
├── README.md              # This file
└── summary-report.md      # Human-readable summary of key vulnerabilities and remediation
```

---

## 💠 Tools Used

| Tool         | Purpose                                      |
|--------------|----------------------------------------------|
| OWASP ZAP    | Automated vulnerability scanning             |
| DVWA         | Intentionally vulnerable PHP web application |
| Kali Linux   | Hosting DVWA and ZAP for testing             |

---

## 🚀 Getting Started

To replicate this test:

1. Set up **DVWA** on a local or virtual environment (XAMPP/Kali Linux).
2. Launch **OWASP ZAP**.
3. Configure browser or proxy to route traffic through ZAP.
4. Perform **Active Scan** on `http://localhost/DVWA`.
5. Export the report in HTML format.

---

## 📋 Scan Summary

- ✅ Automated Active Scan completed using OWASP ZAP.
- 🧠 Targeted known vulnerabilities: SQL Injection, XSS, CSRF, etc.
- ⚠️ Detected multiple issues mapped to OWASP Top 10 threats.
- 📄 Report generated in both **HTML** and **Markdown Summary** format.

---

## 🔐 Vulnerabilities Detected (Examples)

| ID   | Vulnerability Type | Risk Level | Affected URL               |
|------|--------------------|------------|----------------------------|
| 10020| SQL Injection      | High       | `/vulnerabilities/sqli/`   |
| 10021| XSS (Reflected)    | Medium     | `/vulnerabilities/xss_r/`  |
| 10015| CSRF               | Medium     | `/vulnerabilities/csrf/`   |

> 📌 Detailed evidence and remediation tips are provided in the full report.

---

## 📌 Reports

- 📄 [View ZAP HTML Report](./zap-report.html)
- 📘 [View Summary Report](./summary-report.md)
- 🖼️ [Screenshots of Findings](./screenshots/)

---

## 📌 OWASP Top 10 Mapping

| Category                     | Detected |
|-----------------------------|----------|
| A01: Broken Access Control  | ❌       |
| A02: Cryptographic Failures | ❌       |
| A03: Injection              | ✅       |
| A05: Security Misconfig     | ✅       |
| A07: Identification & Auth  | ✅       |
| A08: Software/Data Integrity| ❌       |
| A09: Logging & Monitoring   | ❌       |
| A10: SSRF                   | ❌       |

---

## ✅ Learning Outcomes

- ✔️ Performed authenticated and unauthenticated scanning.
- ✔️ Understood ZAP interface, spidering, and active scanning.
- ✔️ Mapped findings to OWASP Top 10 risks.
- ✔️ Documented results in professional format.

---

## 🧠 Note

> This assessment was conducted in a controlled lab environment on a purposely vulnerable application. **Do not scan live production apps without written permission.**

---

## 📬 Contact

For questions or collaborations, reach out via [LinkedIn](www.linkedin.com/in/navneet3923e) or raise an issue in this repo.
