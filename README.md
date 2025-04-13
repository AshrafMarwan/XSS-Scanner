# 🛡️ XSS Vulnerability Scanner

This is a simple Python-based **XSS Vulnerability Scanner** designed to detect **Cross-Site Scripting (XSS)** vulnerabilities in web forms.  
It was developed as part of my practical training in the field of **IT Security** and **Ethical Hacking**.

---

## ⚙️ Features

- ✅ Detects and analyzes all HTML forms on the target URL
- ✅ Tests forms with multiple common XSS payloads
- ✅ Supports crawling and scanning multiple internal links
- ✅ Optionally respects `robots.txt` rules
- ✅ Can export results to an output file

---

## 📦 Requirements

- Python 3.x  
- Required libraries:
  - `requests`
  - `beautifulsoup4`
  - `colorama`
  - `argparse`

Install dependencies:

```bash
pip install -r requirements.txt

Usage:
python xss_scanner.py <URL> [options]
Example:
python xss_scanner.py https://example.com -c -m 10 --obey-robots -o result.txt
Sample Output:
[+] Detected 2 forms on https://example.com
[+] XSS Vulnerability Detected on https://example.com
[*] Payload: <script>alert('XSS')</script>
🎯 Project Goal
This project demonstrates practical knowledge in:

Web application testing

Form input analysis

Manual injection testing for XSS

Ethical hacking and web security awareness

Python scripting for offensive security
🔐 Future Improvements
Detect DOM-based XSS

Generate HTML reports

Add multi-threading support for faster scans
👨‍💻 Author
Name: Ashraf Marwan
Email: ashrafmarwan954@gmail.com
Field of Interest: IT Security & Penetration Testing
