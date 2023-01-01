Role Name
=========

This downloads and install krustlet and let it join an k8s cluster

Requirements
------------

This role runs on the instance to join. Kubectl must be installed and the Kubconfig file current-context must set to a valid login to join the cluster.

Role Variables
--------------
see: defaults

Dependencies
------------
no

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  ---
- hosts: krustlet
  roles:
    - role: krustlet

License
-------

BSD

Author Information
------------------

Ludger Pottmeier (hurzelpurzel)
