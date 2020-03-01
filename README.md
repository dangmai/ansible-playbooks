Ansible Playbooks
=================

My Ansible playbooks.

How to run
----------

Copy `inventory.sample` to `inventory` and update the values inside it.

```
ansible-galaxy install -r requirements.yml
ansible-playbook playbook.yml -i inventory -f 10
```
