# Ansible Playbooks

My Ansible playbooks.

## How to run

Copy `inventory.sample` to `inventory` and update the values inside it.

```bash
ansible-galaxy install -r roles/requirements.yml
ansible-galaxy collection install -r roles/requirements.yml
ansible-playbook playbook.yml -i inventory -f 10 --ask-become-pass -u ${userToConnectAs}
```
