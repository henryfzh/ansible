# Ansible Script for Ubuntu

## How to Run

### Verify the Playbook Without Making Changes
To simulate the playbook execution without applying changes, use the `--check` option:

```bash
ansible-playbook -i inventory.yml main.yml --ask-become-pass --check
```

### Run the Playbook
To execute the playbook and apply the changes, run:

```bash
ansible-playbook -i inventory.yml main.yml --ask-become-pass
```

---

Test