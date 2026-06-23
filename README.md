# vuln-checker 🛡️

A simple CLI tool for **ethical vulnerability assessment** (learning purposes only).

> ⚠️ **THIS TOOL IS FOR EDUCATIONAL USE ONLY**  
> **DO NOT** scan systems you don't own or have explicit permission to test.  
> Unauthorized scanning is illegal and unethical.

## 🔍 What it does
- Checks for common security headers (X-Frame-Options, Content-Security-Policy)
- Scans for common paths (e.g., `/admin`, `/api`)
- **Does NOT** perform brute-forcing, password guessing, or full penetration testing

## 🛠️ How to use
1. Install Python 3.7+
2. Clone this repo:
   ```bash
   git clone https://github.com/sibust13/vuln-checker.git
   cd vuln-checker
pip install -r requirements.txt

python3 vuln-checker.py --url https://your-own-site.com
