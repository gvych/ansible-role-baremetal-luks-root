Role Name
=========

Provision Linux OS on baremetal with encrypted root partition

Role Variables
--------------

NVMe drives expected by default. For each server with SDD and HDD you must set two variables:

``` 
disks_partions_suffix="" 
luks_disks='["/dev/sdc","/dev/sdb"]'
```

Example Playbook
----------------

Example repository for provision using Hetzner Rescue mode (or similar) https://github.com/gvych/ansible-provision-luks-root

License
-------

BSD
