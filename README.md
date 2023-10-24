# homelab-playbook
Ansible playbook for my home lab

## Examples

List all the hosts in the inventory:

```
ansible-inventory --list
```

Check that all the hosts in the inventory are accessible:

```bash
ansible -m ping all
```

Run playbook:

```bash
ansible-playbook playbook.yml
```