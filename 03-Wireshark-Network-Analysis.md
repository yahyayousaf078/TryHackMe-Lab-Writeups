# Wireshark Network Analysis

**Lab Name:** Packet Analysis  
**Platform:** TryHackMe  
**Date Completed:** 2024-08-22  
**Objective:** Capture and analyze network packets to identify potential security issues.

---

## 🛠 Tools Used
- Wireshark
- tcpdump

---

## 📝 Methodology
1. Captured live network traffic using `tcpdump` and saved it as a `.pcap` file.
2. Imported the capture file into **Wireshark** for detailed inspection.
3. Applied display filters to focus on HTTP, DNS, and suspicious traffic patterns.
4. Examined TCP streams to identify credentials or sensitive information transmitted in plain text.
5. Flagged anomalies and possible malicious activity for further investigation.

---

## 🔍 Key Findings
- Multiple **DNS requests** to suspicious, non-standard domains.
- Unencrypted **HTTP traffic** containing sensitive login details.
- Several repeated **failed login attempts** from the same IP address.

---

## 🎯 Learning Outcomes
- Learned how to capture and filter network traffic in Wireshark.
- Understood how to detect suspicious or malicious patterns in packet captures.
- Recognized the importance of encryption and secure authentication mechanisms.
