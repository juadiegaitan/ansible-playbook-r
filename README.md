# ansible-playbook-r
An Ansible Playbook to deploy RStudio Server

```sh

$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt update
$ sudo apt-get install git ansible
$ git clone https://github.com/yutannihilation/ansible-playbook-r
$ ansible-playbook --ask-su-pass ansible-playbook-r/deploy-rstudio-server.yml
```
