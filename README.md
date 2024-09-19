# nextcloud-ansible
This is a playbook meant to install and configure Nextcloud and its dependencies on Ubuntu and Rocky hosts. This playbook has been tested and verified on single-server configurations in which Nextcloud and the backend database exist on localhost.

#Instructions
Edit /group_vars/all.yml with the desired specifications for your instance. If you're not sure whether to change the preset settings, you can leave them alone.
Edit the hosts file with the IP addresses of the hosts that this playbook will be run against. IF you're only installing Nextcloud on the current host, you can leave this alone as it is set to "localhost" by default.
Run the playbook using "ansible-playbook -i hosts setup_nextcloud.yml".
