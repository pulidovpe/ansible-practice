## Ansible Practices
> Testing repository for Ansible Playbooks


#### How to connect to an EC2 instance on AWS for:
- Install software with APT or uninstall it.
```Shell
ansible-playbook -i ./01/inventory.yaml ./01/playbook.yaml
```
