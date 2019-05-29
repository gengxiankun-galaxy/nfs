NFS
=========

Build nfs service.

Role Variables
--------------

parameter | description
------------ | -------------
NFS_MOUNT_PATH | NFS挂载路径
NFS_CIDR | NFS网段
NFS_PERMISSIOM | NFS权限
NFS_SERVER_IP | NFS服务端IP
NFS_PROVISIONER_NAME | NFS PROVISIONER NAME

Example Invteroy Hosts
-------------

```
[nfs_server]

[nfs_client]

```

Example Playbook
----------------

    - hosts: servers
      roles:
         - gengxiankun.nfs

License
-------

BSD

Author Information
------------------

This role was created in 2019 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).
