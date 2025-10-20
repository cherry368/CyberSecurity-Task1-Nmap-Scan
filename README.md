# 🛡️ Cyber Security Internship – Task 1

**Topic:** Network Reconnaissance using Nmap

---

## 🎯 Objective:
Discover open ports and active devices on the local network to understand potential security exposures.

---

## 🛠 Tools Used:
- **Nmap**
- **Wireshark** (optional)

---

## 📋 Steps Followed:

1. Installed Nmap from the official website.
2. Found local IP range using `ipconfig`.
3. Ran `nmap -sS 192.168.1.0/24` for TCP SYN scan.
4. Saved results in `scan_results.txt`.
5. Analyzed open ports and identified common services.
6. Noted possible security risks.

---

## ⚠️ Common Risks Identified:

- Open ports like **22, 80, and 445** can expose services to attackers.
- Unnecessary open ports should be **closed or firewalled**.

---

## 📚 Learning Outcome:

✅ Understood the purpose of port scanning.  
✅ Learned how open ports expose network services.  
✅ Gained practical experience in reconnaissance using Nmap.

---

## 📁 Repository Structure:

```
CyberSecurity-Task1-Nmap-Scan/
├── README.md
├── scan_results.txt
└── screenshots/
    └── nmap-scan-placeholder.png
```

---

## 🔍 Interview Questions Covered:

1. What is an open port?
2. How does Nmap perform a TCP SYN scan?
3. What risks are associated with open ports?
4. Explain the difference between TCP and UDP scanning.
5. How can open ports be secured?
6. What is a firewall's role regarding ports?
7. What is a port scan and why do attackers perform it?
8. How does Wireshark complement port scanning?

---

## 📌 Key Concepts:

- Port scanning
- TCP SYN scan
- IP ranges
- Network reconnaissance
- Open ports
- Network security basics

---

**Created as part of Cyber Security Internship - Task 1**
