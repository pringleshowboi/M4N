# 🛡️ M4N: Honeypot OS + SIEM Fusion

**M4N** is a lightweight, purpose-built honeypot operating system designed to attract, log, and analyze malicious activity — acting as both a trap and a Security Information and Event Management (SIEM) system.

---

## 🔍 What It Does

- 🎯 **Attracts attackers** with emulated services and vulnerable-looking endpoints
- 📦 **Captures logs** from network traffic, system calls, and unauthorized access attempts
- 🧠 **Analyzes behavior** to identify patterns, indicators of compromise (IOCs), and attack vectors
- 📊 **Feeds data** into SIEM pipelines for deeper threat intelligence and response

---

## 🧰 Tech Stack

- **Languages**: C, Assembly, Python
- **Core Components**:
  - `src/`: Honeypot logic and system emulation
  - `scripts/`: Automation and deployment tools
  - `build_scripts/`: Build automation and packaging
  - `tools/fat/`: FAT filesystem tools and utilities
- **Build System**: SCons
- **Dependencies**: See `requirements.txt`

---
### Project Structure

M4N/
├── build_scripts/    # Scripts for building the OS image
├── image/            # Disk image and related files
├── scripts/          # Deployment and utility scripts
├── src/              # Source code for honeypot services
├── tools/fat/        # FAT filesystem tools
├── SConstruct        # Build configuration file
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation


## 🚀 Getting Started

> ⚠️ **Warning**: This project is intended for research and educational purposes only. Deploy in isolated environments.

### 1. Clone the Repository

```bash
git clone https://github.com/pringleshowboi/M4N.git
cd M4N
```


