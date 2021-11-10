redhat-ha
=========

Ansible role to deploy a redhat cluster HA

Requirements
------------

The following collections must be installed:

```
$ ansible-galaxy collection install ansible.posix -p collections
$ ansible-galaxy collection install community.general -p collections
```

Role Variables
--------------

ToDo

Dependencies
------------

ToDo

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }


$ ansible-playbook -i inventory/cluster2  redhat-ha.yml --tags create-lvm-fs -e @varstest
$ ansible-playbook -i inventory/cluster2  redhat-ha.yml --tags create-resources -e @varstest

License
-------

BSD

Author Information
------------------

silvinux
