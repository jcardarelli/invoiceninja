# invoiceninja
Ansible playbook to install Invoice Ninja on a new Digital Ocean VM

## Setup

### vars/main.yml
1. Change local_user variable
2. Ensure that the base_dir variable is correct

### token.txt
Create a file containing the Digital Ocean API token


## Usage
```
ansible-playbook invoice_ninja.yml --ask-become-pass --extra-vars='{name: fqdn.site.com, size: 1gb}'
```
