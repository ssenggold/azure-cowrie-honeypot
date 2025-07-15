# azure-cowrie-honeypot
# 🛡️ Azure Cowrie Honeypot Project

This project demonstrates how to deploy a **Cowrie SSH honeypot** on an **Ubuntu virtual machine in Microsoft Azure**. The honeypot mimics an SSH server to detect and log unauthorized login attempts, giving you insight into basic attacker behavior and cybersecurity monitoring.

---

## 🧰 Tech Stack

- **Azure** – Ubuntu 22.04 LTS virtual machine  
- **Cowrie** – SSH/Telnet honeypot  
- **Python 3 + Virtual Environment**  
- **Port 2222** – Custom port for honeypot access  
- **SSH Logs** – Stored locally in `cowrie.log`

---

## 🚀 Setup Steps

1. **Created** an Ubuntu 22.04 VM in Azure
2. **Opened port 2222** in the Network Security Group
3. **Installed dependencies** for Cowrie (Python, pip, etc.)
4. **Cloned** the Cowrie GitHub repo
5. **Created** and activated a Python virtual environment
6. **Installed** Cowrie’s Python requirements
7. **Copied** the config file and started Cowrie
8. **Simulated an attack** via SSH on port 2222
9. **Captured and reviewed logs** of the attack in `cowrie.log`

---

## 📸 Screenshots

### ✅ VM Created in Azure  
![](screenshots/1-vm-deployment.png)

### ⚙️ System Update  
![](screenshots/2-system-update.png)

### 📦 Dependencies Installed  
![](screenshots/3-install-deps.png)

### 🧬 Cloned Cowrie Repo  
![](screenshots/4-cowrie-clone.png)

### 🐍 Virtual Environment Activated  
![](screenshots/5-venv-setup.png)

### 🔧 Installed Python Requirements  
![](screenshots/6-pip-install.png)

### 🟢 Cowrie Running  
![](screenshots/7-cowrie-start.png)

### ❌ SSH Fail (Before Opening Port)  
![](screenshots/8-port-fail.png)

### ✅ SSH Fake Login Captured  
![](screenshots/9-port-open-success.png)

### 📄 Logs Confirming the Attempt  
![](screenshots/10-logs-captured.png)

---

## 🧠 What I Learned

- How to deploy and secure an Azure VM
- Honeypot usage and SSH attack simulation
- Reading logs to detect unauthorized access
- Basic cybersecurity deception tactics

---

## 📈 Next Steps

- Forward logs to ELK, Graylog, or Splunk for analysis
- Add fake files and users to make the honeypot more realistic
- Deploy multiple honeypots to monitor attacker patterns

---

## 👤 Author

**Steven Senga**  
GitHub: [@ssengold](https://github.com/ssengold)

---

