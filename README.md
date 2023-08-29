# Ansible
This ansible code is for Installing nginx on the Debian and RedHat servers.
1. secret file
   secret file contains the credentials so you have to enter your username and password in the .secret file.
2. encrypting the secret file
   # ansible-vault encrypt group_vars/.secret
3. For running the ansible
   # ansible-playbook install-nginx.yml --ask-vault-pass -e "@./group_vars/.secret"
   
