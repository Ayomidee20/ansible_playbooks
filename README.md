# 📦 Ansible Playbooks Collection

This repository is a collection of Ansible playbooks I've worked on and used in real-world DevOps, infrastructure automation, and server management scenarios.

Each playbook is written to be **reusable**, **modular**, and easy to adapt for different environments.

---

## 📁 Structure

├── wazuh/
│   ├── install_wazuh_ubuntu.yml
│   └── install_wazuh_rpm.yml

---

## ✅ How to Use

1. **Clone the repo:**

```bash
git clone https://github.com/yourusername/ansible-playbooks.git
cd ansible-playbooks

```
2.	Edit the inventory file or use the -i option:

You can define hosts in an inventory file or pass them inline using -i:

---

## ✅ How to Use

1. **Clone the repo:**

```bash
git clone https://github.com/yourusername/ansible-playbooks.git
cd ansible-playbooks

```
3.	Set required variables:

Some playbooks use variables like wazuh_manager_ip or docker_user. You can:
	•	Set them in a vars.yml file
	•	Or pass them inline like this:

 ansible-playbook playbook.yml -e "wazuh_manager_ip=10.0.0.10"

 🔐 Security Disclaimer

Some playbooks originally used internal IPs, credentials, or organization-specific configs. All sensitive data has been scrubbed or replaced with placeholders.

Please replace placeholder values like "YOUR_WAZUH_MANAGER_IP" before running.


👨🏽‍💻 Author

Ayomide Giwa
DevOps Engineer | IT Infrastructure Engineer | Cloud Enthusiast
📍 Nigeria

🤝 Contributions

Feel free to fork this repo, improve any playbooks, or suggest new ones by opening a pull request. Let’s automate more, together 🚀
