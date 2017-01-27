# Ansible Roles

My collection of Ansible Roles for CentOS 7

## Roles

### common

#### Description
Base configuration for CentOS7 servers including security relevant settings:
* OpenSSH Server with base configuration
* NTP Client
* Postfix with root-mail forwarding
* git
* tmux
* dotfiles from [https://github.com/olivermichel/dotfiles](this repository)

#### Variables
* admin_user -- the name for the admin user
* admin_mail_forward -- email address where user's mail should be forwarded to
* ntp_server -- NTP server address, default: pool.ntp.org

### docker

### firewall

### munin-master

### munin-node
