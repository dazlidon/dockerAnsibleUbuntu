# dockerAnsibleUbuntu
Ansible Role to install docker and create ubuntu container
Hello, 
This is a simple script in Ansible that will allow you to:
- install docker if not found
- create a desired user to be used to run the docker container and image
- download a desired image from Docker Repository ( in this example the ubuntu image)
- create the container and run the image
# Usage:
- Fill in the two variables in runAnsible.yml
- Make sure you have the host value defined in the /etc/ansible/hosts
- Command: ansible-playbook runAnsible.yml
