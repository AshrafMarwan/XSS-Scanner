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
