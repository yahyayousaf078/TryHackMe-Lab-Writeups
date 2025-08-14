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
3. Conducted a service and version detection scan:
   ```bash
    nmap -sV 10.10.124.5
4. Executed vulnerability scripts:
   ```bash
   nmap --script vuln 10.10.124.5

 ---

## 🔍 Key Findings

- Open Ports: 22 (SSH), 80 (HTTP), 443 (HTTPS)

- Outdated Apache web server detected.

- Potential for HTTP directory listing enumeration.

 ---

##🎯 Learning Outcomes

- Understood how to use Nmap for comprehensive scanning.

- Learned the importance of precise targeting to minimize scan noise.
