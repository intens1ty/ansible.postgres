# Ansible for install Postgresql

## Supported OS
* Centos 7

## Functional
* Install Postgresql

## How to install

### 1. Clone this repo
```
git clone https://github.com/intens1ty/ansible.postgresql
cd ansible.postgresql
```

### 2. Change, or add the desired variables:
* roles/postgresql/vars/main.yml

Default values:
* postgresql version - 12

### 3. Add your hosts in inventory file
* inventory/hosts.ini

### 4. Start ansible 
```
ansible-playbook -i inventory/hosts.ini -l my_host playbook.yml
```


