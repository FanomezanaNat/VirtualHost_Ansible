# Apache2 Configuration Automation

This repository contains an Ansible script to automate the configuration of Apache2 on a local machine.

## Prerequisites

Before running the script, make sure you have the following installed:

- Ansible
- Apache2

## Usage

1. Clone this repository to your local machine.
2. Ensure that you have administrative rights to execute the tasks.
3. Modify the `hostConf` file to specify the IP addresses and hostnames of the sites you want to configure.
4. Run the Ansible script with the following command:

```sh
 ansible-playbook -i hosts apache.yml --ask-become-pass 
```

This will execute the configuration tasks, including Apache2 installation, directory creation, virtual host configuration, and adding entries to the `/etc/hosts` file.

5. Once the script completes successfully, you can access the websites using the configured hostnames.
# Command to install ansible:
```sh
sudo apt update
sudo apt install ansible
```


