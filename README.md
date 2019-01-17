NFS
=========

CENTOS

Role Variables
--------------


Example Playbook
----------------

```
# invteroy hosts 文件配置
[nfs_server]

[nfs_clent]

```

    - hosts: servers
      roles:
         - { role: nfs }

License
-------

BSD
