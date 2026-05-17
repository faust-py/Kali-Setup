# Kali Setup

> Automated Kali Linux Full Pentest Environment Setup Script

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Kali%20Linux-purple.svg)
![Shell](https://img.shields.io/badge/shell-bash-green.svg)

---

## Overview

**Kali Setup** is a fully automated Bash script designed to quickly prepare a complete penetration testing environment on Kali Linux.

It installs and configures:

- Recon & OSINT tools
- Web application testing tools
- Network analysis & sniffing utilities
- Exploitation frameworks
- Wireless auditing tools
- Post-exploitation utilities
- Go-based security tools
- Useful UI/terminal enhancements

The script also configures system settings, repositories, PATH persistence, aliases, and performs post-install tweaks automatically.

---

# Features

- Fully automated setup
- Organized installation categories
- Safe package installation with failure handling
- Automatic Go installation
- Persistent Go PATH configuration
- Cloudflare + Google DNS setup
- IPv4 forwarding enablement
- Wireless driver installation
- Colorized logging system
- Summary report with failed packages/tools
- Post-install terminal enhancements

---

# Installed Tool Categories

## Recon & OSINT

- `seclists`
- `maltego`
- `spiderfoot`
- `sublist3r`
- `subfinder`
- `assetfinder`
- `amass`
- `recon-ng`

---

## Web Application Testing

- `gobuster`
- `ffuf`
- `dirsearch`
- `feroxbuster`
- `nikto`
- `zaproxy`
- `nuclei`
- `sqlmap`
- `wpscan`
- `httprobe`
- `beef-xss`

---

## Network & Sniffing

- `nmap`
- `naabu`
- `bettercap`
- `ettercap`
- `responder`
- `wireshark`
- `netdiscover`

---

## Exploitation Frameworks

- `armitage`
- `villain`
- `crackmapexec`
- `impacket`

---

## Wireless Auditing

- `airgeddon`
- `wifiphisher`
- `hcxdumptool`
- `hcxtools`
- `reaver`
- `pixiewps`
- `hostapd`

---

## Utilities & UI

- `terminator`
- `sublime-text`
- `tmux`
- `htop`
- `tree`
- `lsd`
- `zenmap`

---

## Go Tools Installed

### Recon & Discovery

- `katana`
- `httpx`
- `dnsx`
- `naabu`

### URL & Web

- `gau`
- `waybackurls`
- `hakrawler`

### Utilities

- `anew`
- `gf`
- `httprobe`
- `assetfinder`

---

# Requirements

- Kali Linux
- Root privileges
- Internet connection

---

# Installation

## Clone the repository

```bash
git clone https://github.com/yourusername/Kali Setup.git
cd Kali Setup
