# Load_balancer-On-the-top-of-AWS-using-Ansible
Uses Ansible playbook to Configure Reverse Proxy i.e. Haproxy and update it's configuration file automatically on each time new Managed node (Configured With Apache 
Webserver over AWS using instance) join the inventory.<br/>
Download the aws private key and put into the RedHat Linux.<br/><br/>
Run the command
<br/>#chmod 400 private_key_name<br/><br/>
You need to have ansible install into your system and have some prior knowledge about ansible.
