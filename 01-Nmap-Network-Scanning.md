# Nmap Network Scanning

**Lab Name:** Nmap Basics  
**Platform:** TryHackMe  
**Date Completed:** 2024-08-15  
**Objective:** Learn how to perform network reconnaissance using Nmap.

---

## 🛠 Tools Used
- `nmap`
- `ping`
- Linux terminal

---

## 📝 Methodology
1. Performed a basic ping sweep to identify active hosts.
2. Ran a full TCP port scan to detect open ports:
   ```bash
   nmap -p- 10.10.124.5
