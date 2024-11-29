# Born2beRoot 🚀

## Summary
This project is a system administration exercise that introduces virtualization and server setup using tools like VirtualBox or UTM. It requires creating a virtual machine, configuring essential server settings, and ensuring security through strict rules. 🖥️🔒

## Project Details
**Skills Gained**: Virtualization, server configuration, password policy setup, service management, and scripting. 🛠️

## Description
Born2beRoot is an in-depth exercise that teaches virtualization by guiding you to build a server environment from scratch. You’ll work with either Debian or Rocky Linux to:

- Set up partitions with LVM. 🔧
- Configure the system without a graphical interface. 🖤
- Establish a secure SSH server (port 4242). 🔐
- Implement a robust firewall (UFW/firewalld). 🚧
- Set strong password policies and sudo rules. 🛡️
- Write a `monitoring.sh` script to report server status at intervals. ⏱️

### Key Features
- **OS Installation**: Deploy the latest stable version of Debian or Rocky Linux. 💻
- **LVM Partitions**: Create and manage encrypted partitions. 🔒
- **Security Configuration**: Enforce password policies, use sudo with security measures, and ensure the firewall is configured correctly. 🛡️
- **Monitoring Script**: Display server health information (e.g., CPU load, available RAM, disk usage). 📊

## Prerequisites
- VirtualBox or UTM for virtual machine setup. 🖥️
- Basic knowledge of Linux commands and shell scripting. 📚

## Installation & Usage
1. Set up a new virtual machine in VirtualBox/UTM. 🛠️
2. Follow the guidelines to install the OS and apply configurations as per the project requirements. 📑
3. Use `monitoring.sh` for regular server status updates. ⏲️

## Challenges
- Ensuring all security measures (e.g., disabling root login, setting up sudo). 🔐
- Implementing a robust script that runs periodically without issues. 📝
- Understanding system administration concepts deeply, including SELinux/AppArmor configurations. 🤔

## Submission Requirements
Submit a `signature.txt` containing the signature of your virtual disk. Detailed submission and peer-evaluation guidelines are available in the project documentation. 📝
