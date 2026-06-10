# 🚀 Nmaping - Python Nmap Automation Tool

A powerful and interactive **Nmap automation toolkit** built with Python for network scanning, port analysis, and security auditing.

Developed by **Mr Tan**, this tool simplifies complex Nmap commands into an easy-to-use CLI interface for ethical hackers, penetration testers, and cybersecurity learners.

---

## ⚡ Features

- 🧠 16+ Advanced Scan Modes (SYN, OS Detection, Version Detection, Vuln Scan, etc.)
- ⚡ Nmap Timing Control (`-T0` to `-T5`) for stealth and speed tuning
- 🎨 Interactive Colorful CLI Interface
- 🔄 Auto Update Checker (GitHub Sync Support)
- 🌐 Cross-platform support (Linux & Windows)
- 🛡️ Ethical hacking & security auditing toolkit

---

## 🧪 Scan Timing Levels

| Mode | Flag | Description |
|------|------|-------------|
| Paranoid | `-T0` | Very slow, maximum stealth |
| Sneaky | `-T1` | Low detection risk |
| Polite | `-T2` | Light network usage |
| Normal | `-T3` | Default balanced scan |
| Aggressive | `-T4` | Fast scanning |
| Insane | `-T5` | Extremely fast (lab only) |

---

## ⚙️ Requirements

- Python 3.x
- Nmap installed

### 📌 Install Nmap

**Linux (Kali/Ubuntu):**
```bash
pipx install nmaping
