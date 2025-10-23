# Network Security Automation Lab (GitOps)
This project demonstrates how to build an enterprise-grade **Network Security Automation Lab** using GitOps principles — integrating **Ansible**, **GitHub Actions**, and multi-vendor firewalls (**Cisco**, **Palo Alto**, and **Fortinet**).

## 🚀 Overview
The lab automates network configuration, firewall policy deployment, and version control through Git.  
Each configuration change triggers a CI/CD workflow that runs **lint checks**, **Ansible dry-runs**, and **audits before deployment**.

## 🧱 Tech Stack
- **Ansible** for automation  
- **GitHub Actions** for CI/CD  
- **Cisco IOSv**, **Palo Alto PA-VM**, **FortiGate VM** for network devices  
- **Python (Netmiko, Paramiko)** for scripting  
- **EVE-NG / GNS3** for lab simulation  

## ⚙️ Features
- Automated firewall rule deployment  
- Git-based rollback and change tracking  
- Config backups and diff reports  
- Secure CI/CD for network configuration  
- Multi-vendor integration (Cisco, Palo Alto, Fortinet)

## 📸 Diagram
![Network Automation GitOps Diagram](diagrams/gitops-lab-diagram.png)

## 🧩 Folder Structure
## 🧠 Learning Goals
- Understand GitOps for Network Automation  
- Implement CI/CD pipelines for infrastructure  
- Apply automation to network security operations

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
