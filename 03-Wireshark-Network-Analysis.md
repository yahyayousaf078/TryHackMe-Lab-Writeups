# Wireshark Network Analysis

**Lab Name:** Packet Analysis  
**Platform:** TryHackMe  
**Date Completed:** 2024-08-22  
**Objective:** Capture and analyze network traffic to identify anomalies, potential threats, and insecure data transmissions.

---

## 🛠 Tools Used
- **Wireshark** – for packet capture and protocol analysis  
- **tcpdump** – for command-line packet capture  
- **Linux Terminal** – for data handling and filtering

---

## 📝 Methodology
1. **Packet Capture:**  
   Used `tcpdump` to capture live traffic for a targeted host:  
   ```bash
   sudo tcpdump -i eth0 -w capture.pcap
