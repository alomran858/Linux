# Linux Project

This is a set up for Linux server with security settings, a running web server, and deployment on Item Catalog project 


## IP address 
IP: 35.180.99.83
Port: 2200 

## URL
http://35.180.99.83.xip.io

## Summary
* Started a new Ubuntu Linux server instance on Amazon Lightsail. 
* Updated all currently installed packages.
* Changed the SSH port from 22 to 2200 and made sure to configure the Lightsail firewall to allow it.
* Configured the Firewall to only allow incoming connections for SSH (port 2200), HTTP (port 80), and port 123
* Created a new user account named grader and gave him admin access and SSH key pair 
* Configured the local timezone to UTC.
* Deployed the Catalog App



## Referrals 
. [Setting Permissions for LightSail Pem file](http://unix.stackexchange.com/questions/115838/what-is-the-right-file-permission-for-a-pem-file-to-ssh-and-scp) 

. [Digital Ocean setting VPS on ubuntu](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps) 
 
. [Understanding public network ports and firewall settings in Amazon Lightsail](https://lightsail.aws.amazon.com/ls/docs/en/articles/understanding-firewall-and-port-mappings-in-amazon-lightsail)

. [Flask Config](http://flask.pocoo.org/docs/0.12/config/) 

