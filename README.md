# ansible_playbook_commands
This Ansible playbook allows inventory hosts to execute a list of chosen commands. 
You can use this repository if you need to execute a list of commands on several hosts. To do so, follow these steps:
1. update the inventory.ini file for number of hosts
2. update the file roles/execute_commands/defaults/main.yml for list of commands you wanted to execute
3. you can provide private key file name private-key-to-access.key to access hosts we don't need passwordless connections
4. run command "ansible-playbook -i inventory.ini playbook.yml" 
