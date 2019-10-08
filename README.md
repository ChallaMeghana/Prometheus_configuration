# Prometheus_configuration
A simple playbook for installation of Prometheus using ansible roles
Once you clone the repository, place it in /etc/ansible/roles.
## Then run below command.
`ansible-playbook -i invetory prometheus.yml`

**Note**: In inventory file, define your host servers ip and add the ssh key to establish connection between ansible controller and node.


## you can access prometheus server using `localhost:9090`





Originally created and maintained by [Challa Meghana](https://github.com/ChallaMeghana)
