Ansible integration with Jenkins

Follow this on YouTube

Prerequisites:

Ansible server Get Help Here
Jenkins Server Get Help Here

Part-01 Integration Setps

Install "publish Over SSH"

Manage Jenkins > Manage Plugins > Available > Publish over SSH

Enable connection between Ansible and Jenkins

Manage Jenkins > Configure System > Publish Over SSH > SSH Servers

SSH Servers:

Hostname:<ServerIP>
  
username: ansadm
password: *******

Test the connection "Test Connection"
