# actimize-ansible

# test connection to managed host using ssh key. command need to executed using root (in accordance to ssh key file owner)
ansible actone -i inventory -m ping

# run playbook
ansible-playbook -i inventory playbook/tomcat-playbook.yaml

# install actone
1. Make sure postgre playbook executed
2. Make sure tomcat playbook excecuted
3. Make sure actone playbook executed