# Ni3Ansible 
# Learning Ansible

=======================================
      ANSIBLE FOR CENTOS 7
=======================================

$ yum install epel-release
$ yum repolist
$ yum install ansible
$ rpm -qa | grep ansible
$ rpm -ql ansible-2.7.1-1.el7.noarch | more ===== list all files install by ansible

/etc/ansible  -- folder of configuration
/etc/ansible/ansible.cfg -- configuration file
/etc/ansible/hosts  -- hosts files for ansible
/etc/ansible/roles 
/usr/bin/ansible -- ansible command and directory for ansible commands

Create user for ansible operations

$ useradd -d /home/ansadm -m ansadm
