## 📌 Overview

This document explains how I completed **Task 8** of the Cyber Security Internship by studying SQL Injection vulnerabilities and understanding their impact using controlled and legal testing environments.

---

## 🛠️ Tools & Resources Used

- SQLMap  
- Vulnerable test application (legal lab environment)  
- Web browser  
- Cybersecurity documentation  

Only authorized and intentionally vulnerable applications were used.

---

## 🔧 Steps I Followed

### 1️⃣ Understanding SQL Injection
- Reviewed how SQL Injection vulnerabilities occur
- Studied different types of SQL Injection
- Understood why improper input handling leads to database compromise

---

### 2️⃣ Identifying Injectable Parameters
- Analyzed application input points such as URL parameters and form fields
- Identified parameters that interacted directly with the database

---

### 3️⃣ Using SQLMap for Testing
- Used SQLMap to test identified parameters
- Confirmed whether the parameters were vulnerable
- Observed how automated tools detect SQL Injection

---

### 4️⃣ Database Enumeration (Conceptual Understanding)
- Learned how database names, tables, and columns can be extracted
- Understood the sensitivity of exposed database structures

---

### 5️⃣ Extracting User Data (Learning Perspective)
- Studied how attackers could retrieve sensitive user information
- Focused on understanding impact rather than exploiting real data

---

### 6️⃣ Analyzing Impact
- Identified how SQL Injection can affect confidentiality and integrity
- Understood business and security risks of database compromise

---

### 7️⃣ Documenting the Attack Flow
Documented the overall process:
- Vulnerable input identification
- SQL Injection confirmation
- Database exposure
- Data risk assessment

---

### 8️⃣ Suggesting Fixes
Suggested remediation techniques:
- Parameterized queries
- Input validation
- Secure database permissions
- Regular security testing

---

## 📋 Observations

- SQL Injection can fully compromise databases
- Automated tools simplify detection
- Poor input validation is the root cause
- Prevention is more effective than detection

---

## 🎯 What I Learned

- Practical understanding of SQL Injection risks
- How automated tools assist security testing
- Importance of secure coding practices
- Role of defensive controls in database security
