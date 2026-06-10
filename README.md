# 🚀 Nmaping - Python Nmap Automation Tool

A powerful and automated **Nmap scanning toolkit** built with Python for network reconnaissance, port scanning, and security auditing.

Developed by **Mr Tan**, this tool converts complex Nmap commands into a simple interactive CLI interface for ethical hackers, penetration testers, and cybersecurity learners.

---

## ⚡ Key Features

- 🧠 16+ Automated Nmap Scan Modes
- ⚡ Timing Control (`-T0` to `-T5`) for stealth & speed
- 🎨 Interactive Colorful CLI Interface
- 🔄 Auto Update Checker (GitHub Sync)
- 🌐 Cross-platform (Linux & Windows)
- 🛡️ Security & penetration testing tool

---

## 🔍 Supported Scan Types

- SYN Scan
- TCP Connect Scan
- Version Detection
- OS Detection
- Aggressive Scan
- Vulnerability Scan (`--script vuln`)
- Firewall / IDS Evasion
- Fast Scan Modes

---

## ⏱️ Timing Levels

| Mode | Flag | Description |
|------|------|-------------|
| Paranoid | `-T0` | Maximum stealth |
| Sneaky | `-T1` | Low detection risk |
| Polite | `-T2` | Light usage |
| Normal | `-T3` | Default mode |
| Aggressive | `-T4` | Fast scanning |
| Insane | `-T5` | Very fast (lab only) |

---

## ⚙️ Requirements

- Python 3.x
- Nmaping installed
```bash
pipx install nmaping
```

---

# 🚀 2. PyPI DESCRIPTION (paste this in setup / PyPI long description)

txt id="pypi_desc"
Nmaping is a powerful Python-based Nmap automation toolkit designed for network scanning, port analysis, and security auditing.

It simplifies complex Nmap commands into an interactive CLI interface, making it easier for ethical hackers, penetration testers, and cybersecurity learners to perform advanced scans.

Features:
- 20+ automated scan modes
- Nmap timing control (-T0 to -T5)
- Vulnerability scanning support
- OS and service detection
- Fast and aggressive scan options
- Cross-platform support (Linux & Windows)

This project is intended for educational and ethical use only.
