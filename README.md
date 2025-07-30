# 🤖 UNICH Project Automation

### 🚀 UNICH Project Automation

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-Educational-green.svg)](LICENSE)
[![Telegram- Pheonix](https://img.shields.io/badge/Telegram-@PhoenixCrypto__PC-blue.svg)](https://t.me/PhoenixCrypto_PC)
[![Telegram](https://img.shields.io/badge/Telegram-@AirdropScriptFA-blue.svg)](https://t.me/AirdropScriptFA)
---

## 📋 Overview

An advanced automation system for the UNICH project featuring full control over account management, mining, performance monitoring, backups, and logging.

---

## ✨ Key Features

### 🔧 Core Functionalities

- ✉️ Gmail Dot Trick Generator: Create unique Gmail variants  
- 🔌 Direct API Registration: Supports 2Captcha, Anticaptcha, Capsolver  
- ⛏️ Auto Mining: Start mining for all accounts  
- 📊 Stats Dashboard: View performance and mining statistics  
- 🔍 System Health Check: Monitor CPU, memory, and disk  
- 📦 Backup Management: Auto-backup and restore options  

### 🛡️ Security & Reliability

- 🔄 Enhanced Retry Logic: Exponential backoff with random delays  
- 📝 Advanced Logging: Multi-level, structured logging  
- ⏱️ Session Handling: Request limiting & session tracking  
- 💾 Auto Backups: Every 6 hours  
- 🔐 Environment Variables: Protect sensitive information  

---

## 🚀 Installation & Setup

### Requirements

```bash
Python 3.8+
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📁 Project Structure

```
UNICH-ULTIMATE/
├── main.py                 # Main launcher
├── config.py               # Configuration
├── requirements.txt        # Required libraries
├── README.md               # This file
├── .gitignore              # Git ignore rules
├── modules/
│   ├── api_interaction.py      # Handles API requests
│   ├── mining_api.py           # Mining logic
│   ├── gmail_dot_generator.py  # Email generator
│   ├── utils.py                # General utilities
│   ├── system_utils.py         # Health checks
│   ├── stats.py                # Stats tracking
│   ├── session_manager.py      # Session control
│   ├── performance_monitor.py  # CPU/Memory/Disk monitoring
│   ├── backup_manager.py       # Backup and restore logic
│   └── setup_config.py         # Interactive configuration script
├── data/
│   ├── accounts.txt            # List of accounts
│   ├── done.txt                # Processed accounts
│   ├── errors.txt              # Error logs
│   └── statistics.json         # Stats data
├── logs/
│   └── app.log                 # Main log file
└── backups/                   # Backup storage
```

---

## 🎯 How to Use

### Launch the Main Script

```bash
python main.py
```

### Main Menu Options

1. ✉️ Generate Gmail Dot Trick Emails  
2. 🔌 API Registration (2Captcha, Anticaptcha, Capsolver)  
3. ⛏️ Start Mining for All Accounts  
4. 📊 View Statistics & Performance  
5. 🔍 System Health Check  
6. 📦 Backup & Restore Management  

---

## 🔧 Advanced Features

### Retry System

- ✅ Exponential Backoff  
- ✅ Random Jitter to prevent collisions  
- ✅ Smart Retry for transient errors  

### Statistics System

- 📈 Registration success rate  
- 🎯 CAPTCHA solving performance  
- 🔁 OTP verification rate  
- ⛏️ Mining success rate  

### Performance Monitoring

- 💻 CPU usage  
- 🧠 RAM consumption  
- 💾 Disk space remaining  
- ⚠️ Real-time alert system  

### Backup Management

- 🔁 Automatic backup every 6 hours  
- 💽 Keeps last 10 backups  
- 🔄 Safe Restore  
- 🗂️ Full backup management  

---

## ⚙️ Configuration Setup

### Method 1: Interactive Setup (Recommended)

```bash
python modules/setup_config.py
```

You can configure:

- Referral Code  
- Gmail Email  
- Gmail App Password  
- 2Captcha API Key  
- Anticaptcha API Key  
- Capsolver API Key  

✅ User-friendly  
✅ Input validation  
✅ Saves securely to `config.py`  

### Method 2: Use Environment Variables

```bash
# Gmail
export GMAIL_EMAIL="your-email@gmail.com"
export GMAIL_PASSWORD="your-app-password"

# CAPTCHA APIs
export API_KEY_2CAPTCHA="your-2captcha-key"
export API_KEY_ANTICAPTCHA="your-anticaptcha-key"
export API_KEY_CAPSOLVER="your-capsolver-key"
```

---

## 📊 Statistics Tracked

- Registration success  
- CAPTCHA solve rate  
- OTP verification success  
- Mining activity results  
- System metrics: CPU, RAM, Disk  
- Requests per hour  
- Detailed error breakdowns  

---

## 🔍 Troubleshooting

### Common Issues

1. Gmail Error: Enable Gmail App Password  
2. CAPTCHA Errors: Check API key validity  
3. Connection Errors: Verify internet access  
4. Disk Errors: Ensure storage space  

### Logs to Check

- `logs/app.log` – Full activity logs  
- `data/errors.txt` – Error-specific logs  
- `data/statistics.json` – Stats database  

---

## 📈 Performance Tips

- ✅ Use `setup_config.py` for safe setup  
- ✅ Validate all API keys before usage  
- ✅ Monitor system health regularly  
- ✅ Enable backup retention  
- ✅ Review logs weekly  

---

## 🤝 Contributing

Want to help improve this project?

1. Fork this repo  
2. Create a new branch  
3. Make your changes  
4. Submit a pull request  

---

## 📄 License

This software is licensed for **educational and research use only**.

---

## 📞 Support

- Telegram: [@PhoenixCrypto_PC](https://t.me/PhoenixCrypto_PC)

---

## 🏆 Developed by PhoenixCrypto_PC

```
██████╗ ██╗  ██╗ ██████╗ ███████╗███╗   ██╗██╗██╗  ██╗
██╔══██╗██║  ██║██╔═══██╗██╔════╝████╗  ██║██║╚██╗██╔╝
██████╔╝███████║██║   ██║█████╗  ██╔██╗ ██║██║ ╚███╔╝ 
██╔═══╝ ██╔══██║██║   ██║██╔══╝  ██║╚██╗██║██║ ██╔██╗ 
██║     ██║  ██║╚██████╔╝███████╗██║ ╚████║██║██╔╝ ██╗
╚═╝     ╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝  ╚═══╝╚═╝╚═╝  ╚═╝
```

Thanks for using **UNICH Project Automation** 🚀
