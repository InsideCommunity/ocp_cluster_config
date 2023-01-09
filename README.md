ocp_cluster_config
=========

Ansible role to manage configuration in Openshift cluster.

Role Variables
--------------

Explained in [defaults](defaults/main.yml)

Dependencies
------------

Required authentification to Openshift. For example with ocp_auth role.

Example Playbook
----------------

```yaml
    - hosts: localhost
      connection: local
      roles:
         - role: ocp_cluster_config
```
