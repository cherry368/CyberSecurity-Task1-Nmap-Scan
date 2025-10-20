# 🛡️ Cyber Security Internship – Task 1

**Topic:** Network Reconnaissance using Nmap

---

## 🎯 Objective:
Discover open ports and active devices on the local network to understand potential security exposures.

---

## 🛠 Tools Used:
- **Nmap**

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

## 📌 Key Concepts:

- Port scanning
- TCP SYN scan
- IP ranges
- Network reconnaissance
- Open ports
- Network security basics

---

**Created as part of Cyber Security Internship - Task 1**
