Ansible Playbooks
=================

My Ansible playbooks.

How to run
----------

Install `passlib` to encrypt passwords.
On Ubuntu:

```
sudo apt install python-passlib
```

On Arch:

```
sudo pacman -S python2-passlib
```

```
ansible-galaxy install -r requirements.yml
ansible-playbook playbook.yml -f 10
```
