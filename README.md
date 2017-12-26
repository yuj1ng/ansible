# ansible
Ansible playbooks and related stuff to make lives easier

## Run ad-hoc tasks
1. Go to standalone folder
2. Run the below command
```
ansible-playbook -i host, [-c local] playbook
```
>The comma "," after **host** is to tell ansible it's a single host rather than a group  
>-c local so you don't need ssh if you are using **localhost**
