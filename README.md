# chm - Console Host Manager


CHM is a toolkit to simplify hosting management in CentOS.

> Do you have a VPS o Dedicated server and need a light solution to management your host? CHM is for you


## Install
rpm -ivh 

## Features
- Automatic install and configuration a CentOS 6 minimal installation with apache, mysql and other common tools, using the best practices of performance, secure and compatibility.
- Configure local time
- Configure monitor logwatch
- Secure configuration with iptables, failtoban
- Tool to create virtualhost of Apache

## Usage
chm [command] [options]

Command:

+ init: Install and configure apache, mysql, phpmyadmin
  - Options:
  - a: Add some app
+ host: Create a user and configure virtualhost, home directory, logs
