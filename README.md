# Ansible Apache2 Folder Creation Project

The "Ansible Apache2 Folder Creation" project aims to automate the process of creating folders on an Apache2 web server using Ansible. The main objective is to simplify the setup of new directories on the server, ensuring consistent and efficient folder management.

By utilizing this Ansible playbook, you can automate the creation of folders on an Apache2 web server, streamlining the process and reducing manual effort. This project provides a convenient way to ensure consistency and efficiency in folder management. 

Before running the playbook, make sure you have the following prerequisites installed:
- Ansible: Version 2.10 or later.
- Apache2: Installed and properly configured on the target server.
- SSH access: Ensure you have SSH access to the target server with the appropriate credentials.


## to run the ansible script you need to execute the command below:
```sh
 ansible-playbook -i hosts apache.yml --ask-become-pass 
```
# But above all you need to install ansible:
```sh
sudo apt update
sudo apt install ansible
```
To conclude the script that i gave will help you to install apache automatically if you don't have on pc and help you to create host website

