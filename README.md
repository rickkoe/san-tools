# SAN Tools

A collection of Python scripts and Ansible playbooks for automating tasks in Storage Area Networks (SAN), focusing on IBM Storage, Brocade SAN, and Cisco SAN environments. This repository is designed for storage consultants and administrators looking to streamline their workflows.

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your_username/san-tools.git
   cd san-tools
   ```

2. **Set up dependencies**:
	•	Install Python requirements (if applicable):
   ```bash
    pip install -r requirements.txt
    ```

	•	Install Ansible if not already installed:
    ```bash
    dnf install ansible
    ```
3.	Configure your environment:
	•	Update inventory files in ansible/inventory/.
	•	Modify playbook variables in group_vars/.


## 🛠️ Tools Overview

### Ansible

Automate complex tasks like provisioning storage, configuring SAN switches, and managing storage networks.
	•	Example: Provision IBM FlashSystem volumes

ansible-playbook ansible/playbooks/provision_storage.yml



### Python

Scripts for interacting with SAN environments via REST APIs and CLI tools.
	•	Example: Create a new IBM FlashSystem volume

python python_tools/ibm_storage/create_volume.py


## 📚 Documentation

Detailed guides can be found in the docs/ directory:
	•	Getting Started
	•	Ansible Guide
	•	Python Tools Guide

## 🤝 Contributing

We welcome contributions! Please read the CONTRIBUTING.md guide before making changes.

⚖️ License

This project is licensed under the MIT License. See the LICENSE file for details.

## 🌟 Acknowledgments

Special thanks to the storage and SAN community for their continuous support and contributions.

This README is structured to:
- Provide an overview of the repository.
- Explain its structure and purpose.
- Guide users on getting started and contributing.

Feel free to adjust the placeholders like `your_username` and tweak sections to fit your style!