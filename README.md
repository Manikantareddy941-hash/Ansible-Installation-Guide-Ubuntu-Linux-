# Ansible Installation Guide (Ubuntu Linux)

## Overview
This project documents the installation and basic verification of **Ansible** on an Ubuntu Linux system.
Ansible is a configuration management and automation tool used to manage servers, deploy applications,
and automate repetitive IT tasks.

---

## Why Ansible
- Agentless automation (no software needed on managed nodes)
- Simple YAML-based playbooks
- Widely used in DevOps and CI/CD pipelines
- Ideal for configuration management and orchestration

---

## Use Cases
- Server configuration management
- Application deployment
- Automated patching
- Infrastructure provisioning
- Managing multiple servers from a single control node

---

## Environment
- OS: Ubuntu 20.04 / 22.04
- Tool: Ansible
- Access: SSH-based communication

---

## Installation
This section covers installing Ansible on the **control node** using Ubuntu package repositories.

(check Commands file)

---

## Verification
After installation, Ansible is verified using version and inventory checks to ensure it is ready
to manage remote hosts.

---

## Notes
- Ansible is installed only on the control node
- Managed nodes require SSH access
- Python must be available on managed nodes
- Inventory file defines target servers

---

## Conclusion
This repository provides a simple and reliable way to install and validate Ansible on Ubuntu Linux,
serving as a foundation for automation and infrastructure management.
