# 🛡️ Digital Trapdoor

> **🔐 A Multi-Layer Cyber Deception Framework using Encryption, Steganography, and Decoy-Based Defense.**

---

# 📖 Project Overview

Digital Trapdoor is a cybersecurity project that demonstrates how cyber deception, encryption, and steganography can be combined to build a multi-layer defense against unauthorized access.

Instead of protecting sensitive credentials using a single security mechanism, the project encrypts data using **AES-256**, partitions the encrypted data into multiple fragments, hides each fragment inside different file formats using **steganography**, and distributes them across genuine and decoy log files.

An attacker must successfully discover, extract, decode, and reconstruct every fragment before reaching the protected target, significantly increasing the effort required to compromise the system.

This project demonstrates the practical implementation of **Defense-in-Depth**, **Cyber Deception**, and **Secure Data Protection** techniques.

---

# 🎯 Objectives

- 🔐 Protect Sensitive Credentials
- 🛡️ Demonstrate Multi-Layer Security
- 🎭 Implement Cyber Deception
- 💥 Simulate Real-World Attack Scenarios
- ⏳ Delay and Mislead Attackers

---

# 🏗️ System Architecture

```text
                    Sensitive Password
                            │
                            ▼
                  AES-256 Encryption
                            │
                            ▼
                  Partition into 5 Parts
                            │
                            ▼
               Hide Using Steganography
        ┌────────┬────────┬────────┬────────┬────────┐
        │        │        │        │        │
      Image    Audio    Video     Text    Python
        │        │        │        │        │
        └────────┴────────┴────────┴────────┴────────┘
                            │
                            ▼
                  Generate Log Files
                            │
            ┌───────────────┴───────────────┐
            │                               │
        5 Genuine Logs               20 Fake Logs
            │                               │
            └───────────────┬───────────────┘
                            ▼
                  WeTransfer Simulation
                            │
                            ▼
                Attacker Investigation
                            │
                            ▼
                  CyberChef Decoding
                            │
                            ▼
                 Hydra Brute Force Attack
                            │
                            ▼
                      SSH Authentication
                            │
                            ▼
                 Decoy Users & Fake Paths
                            │
                            ▼
                     Target Main User
                            │
                            ▼
                  UFW Firewall Blocking
```

---

# 🔄 Project Workflow

```text
Create Sensitive Password
          │
          ▼
Encrypt using AES-256
          │
          ▼
Split Encrypted Data
          │
          ▼
Hide Fragments using Steganography
(Image / Audio / Video / Text / Python)
          │
          ▼
Generate Genuine & Fake Log Files
          │
          ▼
Upload using WeTransfer Simulation
          │
          ▼
Attacker Downloads Files
          │
          ▼
CyberChef Analysis
          │
          ▼
Hydra Brute Force Attack
          │
          ▼
SSH Login
          │
          ▼
Explore Decoy Users
          │
          ▼
Reach Target User
          │
          ▼
Firewall Blocks Attacker
```

---

# ✨ Key Features

- 🔐 AES-256 Encryption
- 🧩 Password Fragmentation
- 🖼️ Multi-Format Steganography (Image, Audio, Video, Text & Python)
- 📂 Genuine & Fake Log File Generation
- 👤 Decoy User Accounts
- 🌐 WeTransfer Simulation
- 🔎 CyberChef Analysis
- 💥 Hydra Brute Force Simulation
- 🔑 SSH Authentication
- 🛡️ UFW Firewall Protection
- 🎭 Cyber Deception Strategy
- 🔒 Multi-Layer Defense Architecture

---

# 🛠️ Technology Stack

| 💻 Category | 🚀 Technology |
|:------------|:--------------|
| 🖥️ Operating System | Ubuntu Server 20.04 LTS |
| 💻 Programming Language | Python 3 |
| 🔐 Encryption | OpenSSL (AES-256-CBC + PBKDF2) |
| 🖼️ Steganography | OpenPuff |
| 📦 File Partitioning | `split`, `dd` |
| 🔍 Data Analysis | CyberChef |
| 💥 Password Attack | Hydra |
| 🌐 Remote Access | OpenSSH |
| 📂 Secure File Transfer | WinSCP (SFTP) |
| 🛡️ Firewall | UFW (Uncomplicated Firewall) |
| ☁️ File Sharing | WeTransfer (Simulation) |
| 📄 Log Files | auth.log, syslog, audit.log, ufw.log |
| 🐧 Platform | Linux / Ubuntu Server |
| 🔑 Authentication | SSH Login |
| 📁 File Formats | Image, Audio, Video, Text, Python |
| 📦 Virtualization | VirtualBox |
| 🖥️ Shell | Bash |

---

# 🎓 Skills Demonstrated

- Linux Administration
- Ubuntu Server Management
- OpenSSL Encryption
- AES-256 Cryptography
- Steganography
- Password Fragmentation
- Cyber Deception
- SSH Configuration
- Hydra Brute Force Testing
- CyberChef Data Analysis
- WinSCP Secure File Transfer
- UFW Firewall Configuration
- Log Analysis
- Digital Forensics
- Incident Response Concepts
- Secure File Transfer
- Threat Simulation

---

# 🚀 Future Scope

- 🤖 AI-Based Threat Detection
- ☁️ Cloud Deployment (AWS / Azure)
- 📊 SIEM Integration (Wazuh / ELK Stack)
- 🔔 Real-Time Monitoring & Alerts
- 🛡️ Automated Decoy Generation
- 🔐 Support for Advanced Encryption Algorithms
- 🌍 Enterprise-Scale Deployment

---

# 👨‍💻 Author

**Jay Soni**

🎓 M.Sc. IT (Cyber Security)

🛡️ Network Security | SOC Analyst | Cloud Security Enthusiast

📍 Ahmedabad, Gujarat, India

⭐ If you found this project useful, don't forget to **Star** this repository!

---

# 📜 License

This project is developed for **educational, research, and cybersecurity demonstration purposes only**.

The project showcases concepts including **Encryption**, **Steganography**, **Cyber Deception**, and **Defense-in-Depth**.

Any unauthorized or malicious use of this project is strictly discouraged.
