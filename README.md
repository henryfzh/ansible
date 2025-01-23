# Ansible Script for Ubuntu
## Install Ansible

```bash
sudo apt install -y software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install -y ansible
```
## How to Run

### Verify the Playbook Without Making Changes
To simulate the playbook execution without applying changes, use the `--check` option:

```bash
ansible-playbook -i inventory.yml playbook.yml --ask-become-pass --check
```

### Run the Playbook
To execute the playbook and apply the changes, run:

```bash
ansible-playbook -i inventory.yml playbook.yml --ask-become-pass -v
```

### Run the Playbook with specific task
```bash
ansible-playbook -i inventory.yml playbook.yml --tags "grafana,nvim" --ask-become-pass
```
---

Test
