## 📌 Overview

This document explains how I completed **Task 3** of the Cyber Security Internship by practically exploring networking concepts and analyzing network traffic using packet capture tools.

---

## 🛠️ Tools Used

- Wireshark  
- Web Browser  
- Operating System Network Interface  

Only free and open-source tools were used.

---

## 🔧 Steps I Followed

### 1️⃣ Learning Networking Basics
I first studied basic networking concepts such as:
- IP addresses
- MAC addresses
- TCP and UDP
- DNS
- HTTP vs HTTPS

This helped me understand what to look for during packet analysis.

---

### 2️⃣ Installing and Using Wireshark
- Installed Wireshark on my system
- Selected the active network interface
- Started capturing live network traffic

---

### 3️⃣ Capturing Live Network Traffic
- Observed real-time packets generated during normal internet usage
- Noted different protocols present in the capture

---

### 4️⃣ Applying Packet Filters
I used protocol filters in Wireshark to analyze specific traffic:
- `tcp`
- `udp`
- `dns`
- `http`

This made it easier to focus on relevant packets.

---

### 5️⃣ Observing TCP Three-Way Handshake
- Identified SYN, SYN-ACK, and ACK packets
- Understood how TCP establishes reliable connections

---

### 6️⃣ Analyzing DNS Queries
- Captured DNS request and response packets
- Observed domain name resolution to IP addresses

---

### 7️⃣ Plain-text vs Encrypted Traffic
- Observed HTTP traffic where data was visible
- Compared it with HTTPS traffic, which was encrypted and unreadable

---

### 8️⃣ Saving Packet Captures
- Saved the captured packets as `.pcap` files
- These files can be used later for offline analysis

---

## 📋 Observations

- Network traffic contains a mix of protocols
- DNS queries reveal browsing behavior
- TCP ensures reliable communication
- Encrypted traffic protects sensitive data

---

## 🎯 What I Learned

- Basics of networking relevant to cybersecurity
- How packet sniffing works
- How attackers can analyze unencrypted traffic
- Importance of encryption and secure protocols


