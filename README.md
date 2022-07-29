# ansible

#### Commands

##### Run playbook
ansible-playbook azure-docker.yml

##### Check inventory (no need to use hosts file)
ansible-inventory -i inventory.azure_rm.yml --list

##### Run playbook with inventory
ansible-playbook -i inventory.azure_rm.yml azure-docker.yml

#### Run playbook/inventory from Jenkins pipeline
Refer: to https://gitlab.com/nanuchi/java-maven-app/-/tree/feature/ansible

#### Note:
Values should change before testing
