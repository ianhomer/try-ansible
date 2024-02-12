# Try Ansible

Install Ansible

    brew install ansible molecule

List inventory

    ansible-inventory -i inventory.ini --list

Run playbook

    ansible-playbook -i inventory.ini playbook.yaml
