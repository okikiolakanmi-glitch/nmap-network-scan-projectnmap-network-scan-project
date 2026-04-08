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

1. Host Discovery

Used ping scan to identify active devices:

nmap -sn 192.168.1.0/24

2. Port Scanning

Scanned a target IP for open ports:

nmap 192.168.1.1

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
