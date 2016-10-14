Multistage environments with Ansible
====================================

ansible-playbook -i local group-vars.yml
ansible-playbook -i production group-vars.yml
ansible -i local/inventory -u vagrant ms1 -a date
ansible-playbook -i local -u vagrant group-vars.yml
