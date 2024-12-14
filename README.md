# Vulnerability Assessment and Penetration Testing (VAPT) of an E-Commerce Platform

## Overview
This project demonstrates the process of identifying, exploiting, and reporting vulnerabilities in a real-life-like e-commerce platform. The objective is to analyze the platform thoroughly, uncover security loopholes, and provide actionable recommendations to secure the application against potential threats.

The assessment was conducted using ethical hacking techniques, and a detailed developer-level report has been created to document findings, proof of concepts (PoCs), and solutions.

---

## Problem Statement
The e-commerce platform was intentionally configured with a range of vulnerabilities to simulate a real-world testing environment. The goal was to:
1. Explore the platform and identify all possible vulnerabilities and loopholes.
2. Prepare a **Detailed Developer-Level Report** for each identified vulnerability, including:
   - Vulnerability Title
   - Short Description
   - Exact Vulnerable URL
   - Affected Parameters (GET, POST, Cookie, Header, etc.)
   - Payloads Used
   - Step-by-step PoCs
   - Business Impact Analysis
   - Recommendations for Mitigation
   - References for Further Reading

---

## Vulnerabilities Identified
The platform included 28 intentionally placed vulnerabilities, categorized as follows:
- **SQL Injection**
- **Reflected and Stored Cross-Site Scripting (XSS)**
- **Insecure Direct Object Reference (IDOR)**
- **Rate Limiting Issues**
- **Insecure File Uploads**
- **Client-Side Filter Bypass**
- **Server Misconfigurations**
- **Components with Known Vulnerabilities**
- **Weak Passwords**
- **Default Files and Pages**
- **File Inclusion Vulnerabilities**
- **Personally Identifiable Information (PII) Leakage**
- **Open Redirection**
- **Bruteforce Exploitation**
- **Command Execution Vulnerabilities**
- **Forced Browsing Flaws**
- **Cross-Site Request Forgery (CSRF)**

Additionally, other general vulnerabilities beyond the intentionally placed ones were identified and reported.

---

## Methodology
### Steps Followed:
1. Access the project web application through the ethical hacking training platform.
2. Explore the platform’s features to understand its functionality.
3. Perform vulnerability assessment and penetration testing by:
   - Fuzzing input fields.
   - Manipulating HTTP requests.
   - Analyzing server responses.
   - Testing hidden pages and components.
4. Document each vulnerability with detailed observations, PoCs, and mitigation strategies.

### Tools Used:
- **Burp Suite**: For intercepting and modifying requests.
- **OWASP ZAP**: For automated scanning and manual testing.
- **SQLMap**: For exploiting SQL injection vulnerabilities.
- **Nmap**: For network scanning and discovering open ports.
- **DirBuster**: For enumerating hidden directories and files.
- **Custom Scripts**: For brute-forcing and payload crafting.

---

## Report Structure
For each vulnerability, the following details are documented:
1. **Title of Vulnerability**
2. **Short Description**
3. **Exact URL**
4. **Vulnerable Parameters** (GET, POST, Cookie, Header, etc.)
5. **Payloads Used**
6. **Step-by-Step PoCs with Screenshots**
7. **Business Impact**: Detailed explanation of potential exploitation.
8. **Recommendations**: Practical steps to fix the vulnerability.
9. **References**: Links to reputed resources for additional learning.

---

## Steps to Access the Project
1. Log in to [Internshala Training Platform](https://trainings.internshala.com).
2. Navigate to the **Ethical Hacking Training** section.
3. Open the **Progress Tracker**.
4. Click on the **GO TO PROJECT WEB APPLICATION** button to access the test platform.

---

## Business Impact
This project highlights the critical risks that vulnerabilities pose to e-commerce platforms, including:
- Unauthorized access to sensitive user data (e.g., PII leakage).
- Financial fraud through exploitation of payment mechanisms.
- Brand reputation damage due to data breaches.
- Potential legal and compliance issues.

---

## Recommendations
The project concludes with detailed recommendations to mitigate each identified vulnerability. These include:
1. Implementing secure coding practices.
2. Regularly updating software and dependencies.
3. Enforcing strong authentication mechanisms.
4. Applying input validation and output encoding.
5. Conducting periodic vulnerability assessments and penetration tests.

---

## Disclaimer
This project was conducted in a controlled environment for educational purposes as part of ethical hacking training. The information in this report must not be used for malicious purposes. Unauthorized access to systems or applications without explicit permission is illegal and punishable under cybersecurity laws.

---

## Acknowledgments
This project was completed as part of the **Ethical Hacking Training** provided by Internshala. Special thanks to the training team for creating a realistic web application for practical learning.

---
