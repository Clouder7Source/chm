# chm - Console Host Manager


A toolkit to console host manager of CentOS 6.


## Install
rpm -ivh 

## Features
- Automatic install and configuration a CentOS 6 minimal installation with apache, mysql and other common tools, using the best practices of performance, secure and compatibility.
- Secure configuration with iptables, failtoban
- Tool to create virtualhost of Apache

## Usage
chm [command] [options]

Command:

init: Install and configure apache, mysql, phpmyadmin
host: Create a user and configure virtualhost, home directory, logs
