GlusterFS Ansible Role
======================

Setup a 2 node base [GlusterFS](https://docs.gluster.org/en/latest/) [TSP](https://docs.gluster.org/en/latest/Administrator%20Guide/Storage%20Pools/) cluster, with no volumes.

Requirements
------------

- RHEL 6+

Role Variables
--------------

- N/A

Dependencies
------------

- N/A

Example Playbook
----------------

```yaml
- hosts: gluster_nodes
  roles:
     - { role: rmachuca89.ansible-gluster }
```

License
-------

MIT

Author Information
------------------

Rodrigo Machuca