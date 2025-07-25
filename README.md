# 🚨 Authentication Bypass Exploit Project

This project demonstrates how an attacker can exploit SQL injection vulnerabilities to bypass login mechanisms and gain unauthorized admin access to web applications like **Altoro Mutual** and **Acunetix test apps**.

---

## 📁 Contents

- `/report` – Final PDF report with screenshots and step-by-step walkthrough
- `/logs` – SQLMap tool output during injection testing
- `/payloads` – Payloads for SQL injection-based bypass
- `/screenshots` – Capture of browser + terminal session results
- `/tools` – Shell command history used during exploitation

---

## 🧠 Techniques Used

- Boolean-based blind SQL injection
- Error-based SQL injection
- Time-based blind SQLi using `SLEEP()`
- UNION-based injection to dump data
- Password hash retrieval and dictionary cracking

---

## 🔧 Tools

- Kali Linux (Debian)
- SQLMap
- Firefox Developer Tools
- Altoro Mutual Test Environment
- PHP 5.6 / MySQL 5.6 / Nginx

---

## ⚠️ Legal Note

This project is for **educational and ethical hacking** purposes only. Do **not** attempt these techniques on live or unauthorized systems. Always use legally sanctioned environments like Altoro Mutual or testphp.vulnweb.com.

---

## 📄 License

MIT License
