# LeakLynx  

> **Sniffing out secrets before attackers do.**  

LeakLynx is a lightweight, blazing-fast secret scanning tool for Git repositories and file systems.  
It hunts down exposed API keys, tokens, passwords, and other sensitive credentials before they turn into security incidents.  

---

## ✨ Features
- Detects API keys, tokens, and secrets in codebases.  
- Scans both Git history and current files.  
- Lightweight and fast – no bulky dependencies.  
- Customizable regex patterns for your environment.  
- Clear and developer-friendly output.  

---

## 📦 Installation

Clone the repository and install dependencies:  
```bash
git clone https://github.com/vulntrixsecurity/LeakLynx.git
cd LeakLynx
pip install -r requirements.txt
