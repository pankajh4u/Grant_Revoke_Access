Grant_Access by running the below command:

ansible-playbook -i inventory/ -e "action=grant" playbooks/ssh.yml

Revoke_Access by running the below command:
ansible-playbook -i inventory/ -e "action=revoke" playbooks/ssh.yml --skip-tags=remove