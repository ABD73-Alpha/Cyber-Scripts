
# 🧨 SQL Injection Payload Tester

A Python-based tool that tests a list of advanced SQL injection (SQLi) payloads against a target login form and identifies possible SQLi vulnerabilities.

Perfect for CTF challenges, lab environments like TryHackMe or HackTheBox, and educational purposes in web penetration testing.

---

## 🔍 Features

- Automated testing of **error-based**, **boolean-based**, and **time-based** SQLi payloads
- Scans response content for common SQL error messages
- Detects login bypass and suspicious behavior in response
- Custom headers support (e.g., User-Agent spoofing)
- Written for beginner/intermediate cybersecurity learners

---

## ⚙️ How It Works

1. Sends POST requests with different SQLi payloads to a login endpoint
2. Checks for error-based signs (like MySQL/MSSQL/Oracle error messages)
3. Looks for success indicators (e.g., `welcome`, `dashboard`, redirect)
4. Detects delay in response time (for time-based payloads)

---

## 💻 Usage

Update the script with your target URL:

target_url = "http://10.10.95.166/login.php" // Change This

## Then run it : 

python3 sqli_tester.py

⚠️ Disclaimer
This script is intended for educational purposes only.
Do not use this tool against any system without explicit permission.

👨‍💻 Author

- Atharva Dendge { ABD }
  
Cybersecurity Student | Web Pentester

