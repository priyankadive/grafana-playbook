This is simple playbook to install grafana on Ubuntu 14.04.
Edit hosts.txt and provide target address.
Run with:
ansible-playbook -i hosts.txt main.yml -u username -s -k
