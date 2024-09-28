This playbook copies a hardened sshd_config file to a remote server. Simple yet powerful! Be sure to replace the Port and AllowUsers values with your correct values. Let me know what you think of it! Requires ansible to be installed.
<br></br>
You can clone the entire AnsiblePlaybooks repository via `git clone https://github.com/Phoenix-Ignited-Tech/AnsiblePlaybooks` or you can copy the individual files for this Ubuntu Server Setup / SSH-Hardening playbook to your local machine.
Before running this playbook be sure to update the host info in the inventory.ini file and the ssh Port and AllowUsers values in the Hardened-SSHD-CONFIG file to your desired values.
To run this playbook run: `ansible-playbook -i inventory.ini ansibleplay.yaml -K`
