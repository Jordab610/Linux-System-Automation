# Linux-System-Automation
A collection of Unix-based automation scripts and system monitoring tools developed while transitioning into Site Reliability Engineering (SRE).

# macOS System Health Check Script
A lightweight Zsh automation tool designed to monitor system vitals on Apple Silicon (M1) hardware.

## 🚀 Purpose
I built this script to streamline my daily workstation "Sanity Checks." As an aspiring SRE, I wanted to automate the process of checking for disk saturation, memory-hogging processes, and system log errors.

## 🛠️ Features
- **Disk Monitoring:** Uses `df -h` to ensure storage isn't reaching critical levels.
- **Process Analysis:** Identifies the top 3 memory-consuming applications.
- **Automated Logging:** Parses `/var/log/system.log` using `grep` and uses conditional logic to report system health status.

## 📖 What I Learned
- Implementing **conditional if-else logic** in Zsh.
- Managing Unix **file permissions** (`chmod +x`).
- Using **Pipes (|)** to filter CLI output for specific data.
