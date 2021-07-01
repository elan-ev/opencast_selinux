Ansible: Opencast SELinux Role
==============================

Enable and configure SElinux for Opencast cluster.
This role only makes sense in combination with the other Opencast roles.
It allows Nginx to act as a reverse proxy and to access NFS shares.


Example Playbook
----------------

Example of how to configure and use the role:

```yaml
- hosts: servers
  become: true
  roles:
    - role: lkiesow.opencast_selinux
```
