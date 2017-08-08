## role: common

Oliver Michel < oliver dot michel at editum dot de >

Base configuration for CentOS7 servers including:
* OpenSSH Server with base configuration
* SELinux
* NTP Client
* Postfix with root-mail forwarding
* git
* tmux
* dotfiles from [https://github.com/olivermichel/dotfiles](this repository)

#### Variables
* `admin_user`: the name for the admin user
* `admin_mail_forward`: email address where user's mail should be forwarded to
* `ntp_server`: NTP server address, default: pool.ntp.org

python
# python-devel
libselinux-python

 policycoreutils-python
