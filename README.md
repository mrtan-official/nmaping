# Nmap-scaning 
This code write by Mr Tan.

An interactive and custom-built Nmap automation tool, completely designed and coded by me in Python to streamline network scanning and security assessments.

A powerful, interactive, and automated network scanning toolkit built with Python and Nmap. This tool simplifies complex network security auditing, vulnerability scanning, and port mapping, offering advanced speed control features for ethical hackers and penetration testers.

---

## 🛠️ Key Features

- **Comprehensive Scanning Modes**: Supports 16 different scan types including SYN, Version Detection, Vulnerability Assessment (`--script vuln`), OS Detection, Aggressive Scans, Firewall/IDS Detection, and more.
- **Advanced Timing Controls**: Integrated with Nmap Timing Templates (`-T0` to `-T5`) allowing you to balance speed and stealth (Bypassing firewalls or performing rapid audits).
- **Interactive Multi-Color CLI**: Beautiful, clean, and color-coded user interface designed for readability and professional output.
- **Live Version Checker**: Automatically synchronizes and checks for updates with the GitHub source file.
- **Cross-Platform Compatibility**: Fully optimized for Linux (Kali, Ubuntu) and Windows environments.

---

## 🚀 Timing Templates Guide

This toolkit allows you to choose your scan intensity before every scan, giving you full control over performance and stealth:

| Mode | Template | Description |
| :--- | :---: | :--- |
| **Paranoid** | `-T0` | Very slow, minimal noise, best for bypassing strict IDS/Firewalls. |
| **Sneaky** | `-T1` | Slow, used to avoid detection during active monitoring. |
| **Polite** | `-T2` | Moderate speed, consumes very low bandwidth. |
| **Normal** | `-T3` | **Default Speed** - Balanced performance for standard networks. |
| **Aggressive**| `-T4` | Fast and highly recommended for faster security auditing. |
| **Insane** | `-T5` | Extremely fast, best for local lab testing (might drop packets). |

---

## 📋 Prerequisites

Make sure you have **Nmap** installed on your system before running this toolkit.

### For Linux (Kali/Ubuntu):
```bash
sudo apt update && sudo apt install nmap -y
