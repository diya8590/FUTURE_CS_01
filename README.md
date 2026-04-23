# FUTURE_CS_01
Cyber Security Task 01 - Basic Web Security Assessment using Nmap and OWASP ZAP. Includes vulnerability report, screenshots, and remediation steps.
 # FUTURE_CS_01 - Basic Web Security Assessment

## 📌 Task Overview

This repository contains the deliverables for Cyber Security Task 01.

The objective of this task was to perform a basic web vulnerability assessment to identify potential security risks and provide remediation steps.

---

## 🌐 Target Website

Website Tested:

http://demo.testfire.net

This is a deliberately vulnerable website used for educational testing.

---

## 🎯 Scope

- Network scanning
- Vulnerability scanning
- Risk classification
- Reporting findings

Testing Type:

Black-box testing

---

## 🛠️ Tools Used

### Nmap

Used for:

- Port scanning
- Service detection

Command:

nmap -p 80,443 -sV demo.testfire.net

---

### OWASP ZAP

Used for:

- Web vulnerability scanning
- Detecting XSS
- Detecting SQL Injection

---

## 🚨 Vulnerabilities Identified

### High Risk

- Cross Site Scripting (XSS)
- SQL Injection

### Medium Risk

- Missing Security Headers

### Low Risk

- Cookie Without SameSite Attribute

---

## 📸 Evidence

Screenshots available inside:

Evidence/

---

## 📄 Report

Full report available inside:

Report/Web_Vulnerability_Assessment_Report.pdf

---

## ⚠️ Disclaimer

Testing was performed only on a vulnerable educational website.

---

## 👤 Author

Diya
Cyber Security Student
