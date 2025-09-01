# ftp_brute 🔐

A simple FTP brute-force tool for penetration testing and research.  
This project demonstrates how brute-forcing works against FTP services using Python.

---

## 📂 Project Structure
- **ftp_brute.py** → Main brute-force script  
- **usernames.txt** → List of usernames for testing  
- **small_wordlist.txt** → Password wordlist  
- **ftp_bruteforce.log** → Execution logs  
- **reports/** → Generated FTP brute-force reports  
- **Mail_securty_code.txt** → Extra note / reference file  

---

## ⚙️ Features
- Attempts brute-force login on FTP servers  
- Supports username & password wordlists  
- Generates detailed logs and reports  
- Simple and lightweight, written in Python  

---

## 🚀 Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/sanketjaybhaye/ftp_Brute.git
   cd ftp_Brute

    Run the brute force script:

python3 ftp_brute.py <target-ip> <port>

Example:

    python3 ftp_brute.py 192.168.1.10 21

    Check results:

        Logs → ftp_bruteforce.log

        Reports → reports/

📑 Example Output

[+] Trying user: admin / password123
[!] Success: Logged in as admin
Report saved: reports/ftp_report_<timestamp>.txt

--- 

## ⚠️ Disclaimer

This tool is created for educational purposes only.
Do NOT use it on systems without proper authorization.
The author is not responsible for misuse or illegal activities.
