
# 🌐 Linux Service Management: Apache2 Web Server

## 1. Project Overview
The goal of this project was to practice Linux service management commands and understand how a web server operates from a SOC Analyst perspective. Inspired by industry insights from Faisal Zaman.

## 2. Environment
* **OS:** Ubuntu 22.04 LTS (VirtualBox)
* **Service:** Apache2 (HTTP Server)

## 3. Hands-on Tasks
I executed the following commands to manage the web infrastructure:
1. **Installation:** `sudo apt install apache2`
2. **Verification:** Used `systemctl status apache2` to ensure the service was active.
3. **Connectivity:** Verified the local server by accessing `http://localhost`.

## 4. SOC Perspective: Log Analysis
As an aspiring SOC Analyst, I monitored the real-time access logs to understand how the server records incoming traffic:
* **Command used:** `tail -f /var/log/apache2/access.log`
* **Observation:** I witnessed how every page refresh generates a new log entry, which is the foundation of security monitoring and incident response.

## 5. Evidence
<img width="1908" height="1003" alt="Capture d&#39;écran 2026-02-12 103006" src="https://github.com/user-attachments/assets/de4a93ce-379b-4371-87c3-1a77360a2faf" />
<img width="1919" height="984" alt="Capture d&#39;écran 2026-02-12 102940" src="https://github.com/user-attachments/assets/184dd420-98b0-4f9b-9e3c-b0223e1ffe1f" />
