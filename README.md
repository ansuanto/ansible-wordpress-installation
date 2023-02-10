# Ansible-wordpress-installation
Ansible project - Wordpress installation using ansible.

This document is for fresh installation of Wordpress into ansible clients (ec2-instances) using Ansible playbook.
We can add the client details in inventory file of ansible(/etc/ansible/hosts). Its not manidatory to place the client details in default location.
Here by using ansible playbook we install Apache webserver,Mariadb server and Wordpress.

Before running playbook we can check syntax via following:

> ansible-playbook -i hosts main.yml --syntax check

We can run the playbook via following command:

> ansible-playbook -i hosts main.yml

Now the wordpress is installed in all the client instances of Ansible.
