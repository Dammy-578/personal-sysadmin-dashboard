# personal-sysadmin-dashboard
A Windows 11-based system health monitoring dashboard using Glances, displaying real-time CPU, memory, disk, and network metrics via a local web interface.
# 💻 Personal SysAdmin Dashboard (Windows 11 | Glances)

This project showcases a live **system health monitoring dashboard** for my Lenovo Windows 11 laptop using **Glances**, a lightweight cross-platform monitoring tool. The dashboard displays real-time CPU, memory, disk, network activity, and running processes via a browser-accessible interface.

---

## 🎯 Project Goal

To build a local monitoring system that simulates real-world IT administrator tools used for infrastructure health checks and resource tracking — without the need for coding.

---

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Python 3.13** | Base environment |
| **Glances** | System monitoring dashboard |
| **FastAPI** | Web framework required by Glances |
| **Uvicorn** | Web server for Glances dashboard |
| **Jinja2** | Template rendering in Glances |
| **Windows 11** | Host operating system |

---

## 🛠️ Setup Steps (Windows 11)

### 1. Installed Python
Installed [Python 3.13](https://www.python.org/downloads/) and ensured it was added to the system PATH.

### 2. Installed Required Tools
```bash
pip install glances
pip install fastapi uvicorn jinja2
3. Started the Dashboard Server
bash
Copy
Edit
glances -w
4. Accessed the Dashboard in Browser
Opened:

arduino
Copy
Edit
http://localhost:61208
✅ The dashboard runs only on my local machine for privacy and security.

⚠️ Troubles Faced & How I Fixed Them

Issue	Fix
FastAPI import error	Installed FastAPI and Uvicorn: pip install fastapi uvicorn
jinja2 must be installed error	Resolved with: pip install jinja2
Dashboard not showing login screen	Skipped password for now; noted for future improvement
✅ After resolving the missing dependencies, the dashboard successfully launched in the browser.

📸 Screenshots
You can view the screenshots in the screenshots/ folder in this repository:

🔗 https://github.com/Dammy-578/personal-sysadmin-dashboard/blob/main/Screenshot%202025-04-25%20154914.png


Screenshot	Description
dashboard-view.png	Full system dashboard showing CPU, memory, disk, and network stats
local-url-open.png	The dashboard open in browser via localhost:61208
📌 Note: These screenshots are safe and contain no personal or identifying information.

🔐 Security Disclaimer
The Glances dashboard was run locally on localhost only

No public IP, hostname, or real-time system data is exposed

Password protection and remote access will be implemented in future upgrades

This repo does not include any security-sensitive information

🧠 Skills Demonstrated
Local system monitoring setup

Real-time resource usage tracking

Python package installation & troubleshooting

Lightweight web service deployment on Windows

🚀 Future Enhancements
Add username/password authentication

Configure DuckDNS + HTTPS for remote secure access

Auto-launch dashboard with a startup script

📍 Created by: Dammy Ogundipe
📅 Completed: April 2025
🔒 Live dashboard was not shared publicly for security reasons.
