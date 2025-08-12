# webapp-security-task1
Web Application Security Assessment – Future Interns Task 1. Includes DVWA lab setup, OWASP ZAP and Burp Suite scans, identified vulnerabilities (SQLi, XSS, header misconfigurations), screenshots, and remediation recommendations.
# Web Application Security Assessment – Task 1

## 📌 Overview
This repository contains the deliverables for Future Interns Cyber Security Task 1. It includes a DVWA lab environment, vulnerability scanning with OWASP ZAP and Burp Suite, manual testing for SQL Injection and XSS, and remediation recommendations.

## 🛠 Tools Used
- OWASP ZAP
- Burp Suite Community Edition
- DVWA (Damn Vulnerable Web Application)
- Docker
- Nikto

## 🔍 Vulnerabilities Found
1. Missing Security Headers (CSP, X-Content-Type-Options)
2. SQL Injection (SQLi)
3. Reflected Cross-Site Scripting (XSS)

## 📂 Repository Structure
```
webapp-security-task1/
├─ README.txt
├─ report/
│   └─ WebApp_Security_Assessment_Task1.pdf
└─ screenshots/
    ├─ zap_scan.png
    ├─ xss_reflected.png
    ├─ sqli_burp.png
    └─ sqli_dvwa.png
```

## 📑 Report
The report (`report/WebApp_Security_Assessment_Task1.pdf`) contains:
- Lab setup & methodology
- Detailed findings with impact and fixes
- Embedded evidence

## ⚠️ Disclaimer
All testing was performed in a controlled lab environment. No unauthorized systems were targeted.

## 👤 Author
Naman Patil – Cybersecurity Intern
