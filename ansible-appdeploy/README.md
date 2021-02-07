# Ansible Configuration
ansible.cfg

#Inventory
Dynamic Inventory with AWS
```
aws_ec2.yml
```

#Deployment command

```
ansible-playbook -i aws_ec2.yml --private-key=/path/to/feyfile main.yml
```
