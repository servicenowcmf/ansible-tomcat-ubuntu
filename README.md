## Standalone Tomcat Deployment to Ubuntu 14 - Trusty

- Requires Ansible 3.0 or newer
- Expects Ubuntu 14 LTS Hosts
- Installs Openjdk 1.8
- Installs Tomcat 7 (with a future update it will provide the capability to install Tomcat 8.0)

These playbooks deploy a very basic implementation of the Tomcat Application Server, version 7.0. 
The original playbook was forked from @Inforedaster. 
The redesigned playbook is designed to run with Ansible Tower with Ubuntu host in the AWS cloud. 
The playbook can not run the Tomcat server on Port 80.

Please use the following Extra Variables: 

version: 7 /n
http_port: 8080 \n
https_port: 8043
admin_username: username
admin_password: password
