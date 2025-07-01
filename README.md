# actimize-ansible

# test connection to managed host using ssh key. command need to executed using root (in accordance to ssh key file owner)
ansible actone -i inventory -m ping

# run playbook
ansible-playbook -i inventory playbook/tomcat-playbook.yaml