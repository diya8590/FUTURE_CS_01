# 🔐 Web Application Security Analysis

## 📌 Project Overview

This project focuses on performing a **Web Application Security Assessment** on a target website using industry-standard cybersecurity tools. The objective was to identify vulnerabilities, analyze security configurations, and provide remediation recommendations.

The target website used for testing was:

http://demo.testfire.net

This website is intentionally vulnerable and designed for security testing and learning purposes.

---

## 🎯 Objectives

- Perform passive and active security analysis
- Identify vulnerabilities in the web application
- Analyze missing security headers
- Conduct network scanning
- Recommend security improvements
- Document findings in a structured report

---

## 🛠️ Tools Used

The following tools were used during the security assessment:

- **OWASP ZAP** — Vulnerability scanning  
- **SecurityHeaders.com** — Security header analysis  
- **Nmap (Kali Linux)** — Network scanning  
- **Google Chrome Developer Tools** — Header inspection  
- **Oracle VirtualBox** — Virtual environment  
- **Kali Linux** — Security testing platform  

---

## 🌐 Target Information

- **Target Website:** http://demo.testfire.net  
- **IP Address:** 65.61.137.117  
- **Environment:** Kali Linux Virtual Machine  
- **Scan Type:** Passive Scanning  

---

## 🔍 Key Findings

The following vulnerabilities were identified during testing:

- Absence of Anti-CSRF Tokens  
- Content Security Policy (CSP) Header Not Set  
- Missing Anti-Clickjacking Header  
- Cookie Without SameSite Attribute  
- Server Leaks Version Information  
- Missing Security Headers  
- Website Using HTTP Instead of HTTPS  
- Multiple Open Ports Detected (80, 443, 8080)

These vulnerabilities may expose the web application to attacks such as:

- Cross-Site Scripting (XSS)  
- Clickjacking  
- Session Hijacking  
- Information Disclosure  
- Man-in-the-Middle (MITM) Attacks  

---

## 📊 Network Scan Summary

Network scanning was performed using **Nmap**.

### Command Used:

```bash
nmap -sV demo.testfire.net
