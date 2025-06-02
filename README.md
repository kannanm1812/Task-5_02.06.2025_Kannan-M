# Task-5_02.06.2025_Kannan-M
Task 5 dated 02.06.2025 submitted by Kannan M
# Task 5 – Network Traffic Analysis Using Wireshark

## 📌 Overview
Analyzed a network capture file using Wireshark to identify and understand the behavior of different network protocols.

## 🔧 Tools Used
- Wireshark
- Browser/Terminal (to generate traffic)

## 📡 Protocols Identified
### 1. **DNS**
- Resolves domain names into IP addresses.
- Port: 53 (UDP)
- Example: Query for `google.com`

### 2. **TCP**
- Reliable transmission protocol.
- Used in handshakes and secure communications (e.g., HTTPS).
- Port example: 443

### 3. **HTTP**
- Protocol for web traffic.
- Port: 80
- Example: GET request to a website

## 🧾 Sample Packet Table

| No.    | Protocol | Source IP         | Destination IP   | Length | Info                         	|
|--------|----------|-------------------|------------------|--------|-----------------------------------|
| 1542   | DNS      | 192.168.188.2     | 192.168.188.128  | 53     | Standard query A response    	|
| 1543   | TCP      | 192.168.188.128   | 34.107.221.82    | 74     | SYN                          	|
| 1546   | HTTP     | 192.168.188.128   | 34.107.221.82    | 364    | GET /success.txt?ipv4 HTTP/1.1    |

## 📁 Files in this Repo
- `README.md` – Summary of the task
- `Wireshar_Network Traffic.pcap`
- Screen Shots

## 📸 Screenshots

!screenshots of the wirshark 



## 🔍 Key Learnings
- DNS traffic is unencrypted and easily readable.
- TCP follows the 3-way handshake mechanism.
- HTTP shows full request/response data.

## 🔗 Submission

**GitHub Repo Link**: https://github.com/kannanm1812/Task-5_02.06.2025_Kannan-M
**Submission Form**: https://docs.google.com/forms/u/0/d/e/1FAIpQLSewY4rIS3T506ZoBsj5TPzQdyxe7gg9tFmuOiiO0diPlaVNjw/formResponse

---

## ✅ Task Completed
