# Bootstrap Docker-CE and docker-compose

This is an ansible playbook that installs docker-ce and docker-compose on a remote host

## Usage

Edit hosts, site.yml, and host_vars/remote to include the user you'd like to do this as on your remote host. I have this set up with ssh keys so that passwords are note necessary. Also edit hosts to include the hosts you'd like to bootstrap. Then, run:

`ansible-playbook site.yml -i hosts`
