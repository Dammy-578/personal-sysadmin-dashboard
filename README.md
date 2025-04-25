# 💻 Personal SysAdmin Dashboard (Windows 11 | Glances)

This project showcases a live **system health monitoring dashboard** for my Lenovo Windows 11 laptop using **Glances**, a lightweight cross-platform monitoring tool. The dashboard displays real-time CPU, memory, disk, network activity, and running processes via a browser-accessible interface.

---

## 🎯 Project Goal

To build a local monitoring system that simulates real-world IT administrator tools used for infrastructure health checks and resource tracking — without the need for coding.

---

## 🧰 Tools & Technologies Used

| Tool            | Purpose                             |
|-----------------|-------------------------------------|
| **Python 3.13** | Base environment                    |
| **Glances**     | System monitoring dashboard         |
| **FastAPI**     | Web framework required by Glances   |
| **Uvicorn**     | Web server for Glances dashboard    |
| **Jinja2**      | Template rendering in Glances       |
| **Windows 11**  | Host operating system               |

---

## 🛠️ Setup Steps (Windows 11)

### 1. Installed Python  
Installed [Python 3.13](https://www.python.org/downloads/) and ensured it was added to the system PATH.

### 2. Installed Required Tools
```bash
pip install glances
pip install fastapi uvicorn jinja2
```

### 3. Started the Dashboard Server
```bash
glances -w
```

### 4. Accessed the Dashboard in Browser
```
http://localhost:61208
```

✅ The dashboard runs only **on my local machine** for privacy and security.

---

## ⚠️ Troubles Faced & How I Fixed Them

| Issue                          | Fix                                               |
|--------------------------------|----------------------------------------------------|
| `FastAPI` import error         | Installed FastAPI and Uvicorn via `pip`           |
| `jinja2 must be installed`     | Installed using `pip install jinja2`              |
| No login page on dashboard     | Skipped password for now (future enhancement)     |

✅ After resolving the missing dependencies, the dashboard successfully launched in the browser.

---

## 📸 Screenshot

Here’s a screenshot of the live Glances dashboard:

🔗 [Click here to view](https://github.com/Dammy-578/personal-sysadmin-dashboard/blob/main/Screenshot%202025-04-25%20154914.png)

> 📌 **Note:** The screenshot is safe and does not reveal any personal or identifying system data.

---

## 🔐 Security Disclaimer

- The Glances dashboard was run **locally on `localhost` only**
- No public IP, hostname, or real-time system data is exposed
- Password protection and remote access will be implemented in future upgrades
- This repo does **not** include any security-sensitive information

---

## 🧠 Skills Demonstrated

- Local system monitoring setup
- Real-time resource usage tracking
- Python package installation & troubleshooting
- Lightweight web service deployment on Windows

---

## 🚀 Future Enhancements

- Add username/password authentication
- Configure DuckDNS + HTTPS for remote secure access
- Auto-launch dashboard with a startup script

---

📍 **Created by:** Dammy Ogundipe  
📅 **Completed:** April 2025  
🔒 _Live dashboard was not shared publicly for security reasons._
```

