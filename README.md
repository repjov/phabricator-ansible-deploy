## Phabricator installer:
This script allow to deploy Phabricator on Vagrant machine or other server. 
PHP5.1, MySQL, Nginx

In order to install this application you must have installed following tools:

- Ansible >=v2.0
- Vagrant >= 1.8.4.
- GIT
- Vagrant plugin `vagrant-hostsupdater`. In order to install it just run following command: `$ vagrant plugin install vagrant-hostsupdater`
- `pexpect` pyton module. How to install look [here](https://github.com/pexpect/pexpect) 

`vagrant up` - setup and run Ubuntu 14.014 and configure Phabricator.

