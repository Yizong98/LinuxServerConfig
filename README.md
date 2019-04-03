# LinuxServerConfig
### Full Stack Web Development
_______________________
## About
This project is about configuring a Linux Server. 

## Prerequisites

* IP: 54.71.12.133
* SSH port: 2200
* Url1: http://54.71.12.133.xip.io/
* Url2: http://ec2-54-71-12-133.us-west-2.compute.amazonaws.com/

## Summary of Configurations steps:
* chmod 600 the pem lightsail key
* ssh to ubuntu
* add user grader and grant root access
* update and upgrade packages
* change port to 2200 and set PermitRootLogin to no
* generate ssh-kegen for grader
* configure fire wall block all ports but 2200,80,123
* set up timezone
* download Fail2Ban for security protection
* configure Apache and python virtual environment to run scripts
* download git and set up database
* set up wsgi file
* run application, test
* get Google Oautho2.0 to work


## Software Packages:
* Python
* apache
* sendmaik
* Fail2Ban
* libapache2-mod-wsgi
* postgresql
* git
* httplib2
* requests
* oauth2client
* sqlalchemy
* flask
* libpq-dev
* psycopg2

Reference
-------------
* https://www.digitalocean.com/community/tutorials/how-to-protect-ssh-with-fail2ban-on-ubuntu-14-04
* https://github.com/boisalai/udacity-linux-server-configuration
* https://linuxconfig.org/configuring-gmail-as-sendmail-email-relay


