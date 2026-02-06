📌 Prerequisites

Ubuntu 20.04+ (or any Debian-based Linux)

sudo access

Internet connection

Check:

sudo -v

📥 Step 1 — Update system
sudo apt update && sudo apt upgrade -y

📦 Step 2 — Install Ansible
sudo apt install ansible -y

✅ Step 3 — Verify installation
ansible --version


You should see version output.

📁 Step 4 — Basic inventory setup

Create inventory file:

sudo nano /etc/ansible/hosts


Example:

[servers]
192.168.1.10
192.168.1.11


Save & exit.

🔐 Step 5 — Test connection
ansible servers -m ping


If you get pong → it’s working.

⚡ Common useful commands

Run command on all servers:

ansible servers -a "uptime"


Install package:

ansible servers -b -m apt -a "name=nginx state=present"

📂 Create your first playbook
nano install-nginx.yml

- hosts: servers
  become: yes
  tasks:
    - name: Install nginx
      apt:
        name: nginx
        state: present


Run it:

ansible-playbook install-nginx.yml
