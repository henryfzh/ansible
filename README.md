# Ansible Script for Ubuntu

## Run
    - To verify the playbook without making changes, use the --check option
    ```
    ansible-playbook -i inventory.yml main.yml --ask-become-pass --check
    ```

    - Run
    ```
    ansible-playbook -i inventory.yml main.yml --ask-become-pass
    ```