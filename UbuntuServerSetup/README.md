The Ubuntu Server Setup Ansible Playbook collection contains numerous individual ansible playbooks for a variety of actions commonly taken to secure an Ubuntu server. 
The playbooks include: 
-AIO (Combines the SSH Hardening, Auto Upgrade, Required Packages, UFW, & Fail2Ban, playbooks into a single all-in-one Ubuntu Server Setup playbook)
-SSH Hardening (This playbook very simply contains a hardened sshd_config file and copies this file over to the remote server via the ansible.builtin.copy module.)
-SSH Hardening Manual (This playbook contains numerous individual actions that together harden an existing sshd_config file on a remote server.)
-Auto Upgrade (This playbook enables automatic upgrades on a remote server)
-Required Packages (This playbooks installs required software packages on a remote server)
-UFW (This playbook isntalls and configures UFW on a remote server)
-Fail2Ban (This playbook installs and configurtes Fail2Ban on a remote server)
