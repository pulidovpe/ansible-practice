## Ansible Practices
> Testing repository for Ansible Playbooks


#### How to connect to an EC2 instance on AWS for:
- Install software with APT or uninstall it.
```Shell
ansible-playbook -i ./01/inventory.yaml ./01/playbook.yaml
```

#### How to connect to an EC2 instance on AWS for:
- Install software with APT, NPM, PIP.
- Use environment variables on inventary.
```Shell
ansible-playbook -i ./02/inventory.yaml ./02/playbook.yaml
```

#### How to connect to an EC2 instance on AWS for:
- Set an SSH key for clone a private repository.
```Shell
ansible-playbook -i ./03/inventory.yaml ./03/playbook.yaml
```