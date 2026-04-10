# nmap-network-scan-projectnmap-network-scan-project
Network scanning project using Nmap to discover hosts, open ports, and services in a controlled environment.
🔍 Network Scanning Project using Nmap

📌 Overview

This project demonstrates how to perform network scanning using Nmap (Network Mapper), a powerful tool used in cybersecurity for discovering hosts and services on a network.

🎯 Objectives

- Identify active devices on a network
- Discover open ports
- Detect running services
- Understand basic network security risks

🛠️ Tools Used

- Nmap
- Kali Linux / Windows Command Line

🚀 Steps Performed

## 🔍 Nmap Scan Analysis

### 📌 Scan 1: Localhost (127.0.0.1)

- Command used: `nmap -T4 -A -v 127.0.0.1`
- Open ports discovered:
  - 135 (RPC)
  - 445 (SMB)
  - 8000, 8089, 8194 (Web/Custom services)

**Insight:**
These ports indicate active local services. Port 445 (SMB) is particularly important as it is often targeted in lateral movement attacks.

![Localhost Scan](local-host-scan.png)

---

### 📌 Scan 2: Router (192.168.1.1)

- Command used: `nmap -T4 -A -v 192.168.1.1`
- Result: Host appears down

**Insight:**
The router likely blocks ICMP (ping) requests. This is common in secured networks.

![Router Scan](scan-router.png)
3. Service Detection

Detected services running on open ports:

nmap -sV 192.168.1.1

4. OS Detection

Attempted to detect the operating system:

nmap -O 192.168.1.1

📊 Results

- Identified open ports such as 22 (SSH), 80 (HTTP), and 443 (HTTPS)
- Detected services and versions running on the target system

⚠️ Ethical Consideration

All scans were performed in a controlled lab environment or on authorized systems only.

🧠 What I Learned

- How network scanning works
- Importance of open ports in security
- Basics of reconnaissance in cybersecurity

📎 Conclusion

This project helped me understand how attackers and defenders analyze networks, making it a foundational skill in cybersecurity.

---

⭐ Feel free to connect with me on LinkedIn and check out my other projects!
