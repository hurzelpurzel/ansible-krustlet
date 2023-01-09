Role Name
=========

This downloads and install krustlet and let it join an k8s cluster

Requirements
------------

This role runs on the instance to join. 
The Kubconfig file must be present and set to a valid login to let the node join the cluster.
It might be a good idea to login locally and do scp copy. Usually kubeconfig is located at ~/.kube/config
If you are not able to login via ssh, you can try to install openssh-server package with apt.


Role Variables
--------------
see: defaults

| name | default |
| kubeconfig_path | /tmp/kubeconfig | 

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
