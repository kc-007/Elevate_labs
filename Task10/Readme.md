## 📌 Overview

This document explains how I completed **Task 10** of the Cyber Security Internship by configuring firewall rules, testing network connectivity, and analyzing firewall behavior.

---

## 🛠️ Tools & Resources Used

- UFW (Linux Firewall) / Windows Defender Firewall  
- Local system and network  
- System logs  

Only built-in and free firewall tools were used.

---

## 🔧 Steps I Followed

### 1️⃣ Understanding Firewall Concepts
- Studied how firewalls filter network traffic
- Learned the difference between inbound and outbound rules
- Understood stateful vs stateless firewalls

---

### 2️⃣ Enabling the Firewall
- Enabled UFW on Linux or Windows Defender Firewall on Windows
- Verified firewall status before applying rules

---

### 3️⃣ Configuring Firewall Rules
- Allowed required services such as SSH or HTTP
- Denied unnecessary or unused ports
- Applied least privilege principle for network access

---

### 4️⃣ Allowing and Blocking Ports
- Tested connectivity to allowed ports
- Verified blocked ports were inaccessible
- Observed changes in network behavior after rule updates

---

### 5️⃣ Testing Connectivity
- Used network tools to test access before and after firewall rules
- Confirmed that firewall rules were working as expected

---

### 6️⃣ Observing Firewall Logs
- Reviewed firewall logs to see allowed and denied traffic
- Identified blocked connection attempts

---

### 7️⃣ Blocking a Malicious IP
- Added a rule to block a suspicious or test IP address
- Verified that traffic from the blocked IP was denied

---

### 8️⃣ Documenting Rules and Impact
Documented:
- Configured firewall rules
- Allowed and blocked ports
- Observed impact on connectivity and security

---

## 📋 Observations

- Firewalls effectively block unauthorized access
- Misconfigured rules can disrupt services
- Logs provide valuable security insights
- Firewalls reduce attack surface but are not a complete defense

---

## 🎯 What I Learned

- Practical firewall configuration
- Importance of rule management
- How to test firewall effectiveness
- Role of firewalls in layered security


