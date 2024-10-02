This playbook combines multiples of the other Ubuntu Server Setup playbooks into one playbook. It is meant strictly for debian / Ubuntu like systems and includes the following tasks: 
<br></br><ul><li>Create Users on Target Hosts including Admin Users</li>
<li>Installs Common Packages on Target Systems</li>
<li>Configures UFW & Fail2ban</li>
<li>Copies a Hardened SSHD Config file to the remote server</li>
<li>Reboots the server and checks to ensure the server is back online</li>
</ul>
<br></br>
The playbook contains multiple variables that will need to be modified according to your own use case. All variables are at the beginning of the playbook.
The playbook also contains two files that it copies over to the remote target systems a JailConf file which is copied over the jail.local file on the remote systems and a hardened sshd_config file.
Be sure to modify these files according to your own use case.
