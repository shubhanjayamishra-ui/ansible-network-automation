# 🌐 Ansible Network Automation

A production-ready network automation project built with Ansible,
targeting Cisco IOS devices. Designed to automate repetitive 
network tasks and reduce manual effort in enterprise environments.

---

## 📌 Project Overview

This project automates common network operations using Ansible playbooks,
including device fact collection, BGP neighbor verification, 
interface status checks, and configuration backups.

---

## 🛠️ Tech Stack

- Ansible Core 2.21
- Cisco IOS Collection (cisco.ios)
- Python 3.14
- YAML
- Git & GitHub

---

## 📂 Project Structure

ansible-network-automation/
├── ansible.cfg
├── inventory/
│   └── hosts.ini
├── playbooks/
│   ├── get_facts.yml
│   ├── bgp_check.yml
│   ├── interface_status.yml
│   └── config_backup.yml
├── backups/
└── README.md

---

## 📋 Playbooks

| Playbook | Description |
|---|---|
| get_facts.yml | Collects device facts from Cisco routers |
| bgp_check.yml | Verifies BGP neighbor status |
| interface_status.yml | Checks interface up/down status |
| config_backup.yml | Takes running config backup |

---

## 🚀 How to Run

### 1. Clone the repo
git clone https://github.com/shubhanjayamishra-ui/ansible-network-automation.git
cd ansible-network-automation

### 2. Update inventory
Edit inventory/hosts.ini with your device IPs and credentials

### 3. Run a playbook
ansible-playbook playbooks/get_facts.yml
ansible-playbook playbooks/bgp_check.yml
ansible-playbook playbooks/interface_status.yml
ansible-playbook playbooks/config_backup.yml

---

## 👨‍💻 Author

Subhanjaya Mishra
Senior Network Engineer | CCNP CERTIFIED
NTTDATA NORTHAMERICA, Pune

