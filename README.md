
# **WiFuX v2.0** 
### *WPS Security Auditing Tool for Android / Termux*

**Created by Hayat** | [@rifat_hayat](https://instagram.com/rifat_hayat)

---

</div>

## 🎯 Overview

WiFuX is a WPS (Wi-Fi Protected Setup) security auditing tool built for Android devices running Termux. It automates Pixie Dust and Bruteforce attacks against WPS-enabled routers, allowing security researchers and network administrators to evaluate the strength of their own wireless infrastructure.

WiFuX v2.0 is a complete rewrite of the original v1 engine, introducing:
- 🔄 Global command system
- 📊 Session management & reporting
- 🛡️ Enhanced stability
- 📚 Built-in interactive help guide
- ⚡ Fully optimized for Android / Termux

> ⚠️ **Legal Notice:** This tool is intended for authorized security testing only. Only use it on networks you own or have explicit permission to test.

---

## 📋 Requirements

- Android device with root access (Magisk or KernelSU)
- [Termux](https://f-droid.org/en/packages/com.termux/) installed (from F-Droid, NOT PlayStore)
- Root-capable WiFi adapter (internal wlan0 or external)

---

## 🚀 Installation

```bash
pkg update && pkg upgrade -y
pkg install root-repo git tsu python 
pkg install wpa-supplicant pixiewps iw -y
git clone https://github.com/mdrifathosain74-hash/WifuK
cd WifuK
chmod +x installer.sh
bash installer.sh
