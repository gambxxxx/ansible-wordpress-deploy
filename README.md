# Ansible-Wordpress-Deploy Documentation

# Requirements:
* Ubuntu 16.04 destination server
* Linux / Unix based local machine
* Ansible 2.7.2

# Installing Ansible
* On Ubuntu 
`sudo apt-get update`
`sudo apt-get install software-properties-common`
`sudo apt-add-repository ppa:ansible/ansible`
`sudo apt-get update`
`sudo apt-get install ansible`

# Usage: 
* Clone this rapository to your local machine and update the hosts file with the destination server address.
* Run the ansible-playbook by entering:
`ansible-playbook playbook.yml`
