# docker-swarm-centos

Before set Env:

 `export ANSIBLE_HOST_KEY_CHECKING=False`
 
 If specified user is not in sudo group
 
 `ansible-playbook -i hosts.ini swarm-cluster.yml --extra-vars "ansible_sudo_pass=yourPassword"`
