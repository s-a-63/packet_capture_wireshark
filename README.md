# Network Packet Capture & Protocol Analysis using Wireshark

This project documents a basic network packet analysis conducted using **Wireshark**. The goal of the task was to capture live network traffic, analyze the types of protocols in use, and generate insights based on the data collected.

---

## 📌 Task Objective

- Capture live network traffic using Wireshark.
- Analyze the protocols used during the session.
- Summarize the number of packets associated with each protocol.
- Identify the presence or absence of HTTP traffic.
- Generate a protocol hierarchy summary.
- Document all findings in a structured report.

---

## 🛠️ Tools Used

- **Wireshark** – Packet capture and analysis tool   
- **.pcapng** file – Captured packet data saved for analysis

---

## 📂 Files Included
### ▶️  [`Documents/`](./Documents/)

- `NW packet capture.pcapng` – The original packet capture file  
- `Task 5-Capture and Analyze Network Traffic using Wireshark` – Summary of the protocol analysis

---

## 📊 Summary of Analysis

- **Total Packets Captured:** 6693
- **Dominant Protocols:**
  - **TCP:** 6369 packets (95.2%)
  - **UDP:** 228 packets (3.4%)
  - **TLS (HTTPS/Encrypted):** 2411 packets (36.0%)
  - **DNS:** 212 packets (3.2%)
  - **Others:** ARP, ICMP, IGMP, and more

- **Observation:**  
  No unencrypted HTTP traffic was found. Most web traffic was secured using **TLS (HTTPS)**.

---

## 📈 Conclusion

The analysis reflects a typical secure browsing session with DNS queries, TCP transmissions, and encrypted TLS communication. This kind of capture can be useful for:
- Studying traffic patterns
- Monitoring encrypted traffic presence
- Understanding the overall structure of network communications

---

