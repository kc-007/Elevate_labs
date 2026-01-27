# Task 7 – Web Application Vulnerability Testing (Execution)

---

## 📌 Overview

This document explains how I completed **Task 7** of the Cyber Security Internship by performing basic web application vulnerability testing using a vulnerable application and security testing tools.

---

## 🛠️ Tools & Resources Used

- Burp Suite Community Edition  
- Vulnerable Web Application (DVWA / OWASP Juice Shop)  
- Web browser  

Only free and legal testing environments were used.

---

## 🔧 Steps I Followed

### 1️⃣ Understanding OWASP Top 10
- Reviewed OWASP Top 10 vulnerabilities
- Focused mainly on SQL Injection and XSS
- Understood how these vulnerabilities affect web applications

---

### 2️⃣ Setting Up a Vulnerable Application
- Used a deliberately vulnerable application (DVWA / Juice Shop)
- Ensured testing was performed in a controlled environment

---

### 3️⃣ Configuring Burp Suite
- Set up Burp Suite as a proxy
- Configured the browser to route traffic through Burp
- Intercepted HTTP requests and responses

---

### 4️⃣ Testing for SQL Injection
- Identified input fields accepting user data
- Injected basic SQL payloads
- Observed application behavior and error messages
- Confirmed vulnerability based on response changes

---

### 5️⃣ Testing for XSS
- Injected simple XSS payloads into input fields
- Observed whether the payload executed in the browser
- Identified reflected or stored XSS behavior

---

### 6️⃣ Observing Application Responses
- Analyzed HTTP status codes
- Reviewed server responses for errors and unusual behavior
- Correlated responses with injected payloads

---

### 7️⃣ Documenting Vulnerabilities
For each identified vulnerability, I documented:
- Vulnerability type
- Affected input parameter
- Observed behavior
- Potential impact

---

### 8️⃣ Suggesting Mitigations
Suggested fixes included:
- Input validation
- Use of prepared SQL statements
- Output encoding
- Security testing during development

---

## 📋 Observations

- Improper input handling leads to serious vulnerabilities
- SQL Injection can expose backend databases
- XSS can compromise user sessions
- Burp Suite is effective for intercepting and analyzing requests

---

## 🎯 What I Learned

- Practical use of Burp Suite
- How common web vulnerabilities occur
- How attackers exploit insecure inputs
- Importance of secure coding practices

---

## 🏁 Conclusion

This task helped me gain hands-on experience in web application security testing. It improved my understanding of OWASP Top 10 vulnerabilities and strengthened my ability to analyze and report security issues in web applications.

---

⭐ Task 7 Completed – Web Application Vulnerability Testing
