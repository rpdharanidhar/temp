This is a README.md file for the ping module that is used to check whether the remote server is in response

*Clone this repository*
https://OCIWolfPack@dev.azure.com/OCIWolfPack/Ansible/_git/Ansible
cd lamp-stack

Make sure to replace the IP of your remote server in the .ini file

*And run the following command*
ansible-playbook -i inventory.ini lamp-depl.yaml and 
add the block of cmd to see the log for the last run "|tee logfile.log"