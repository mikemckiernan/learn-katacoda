# Install vdo

`yum install -y vdo-6.2.3.114-14.el8 kmod-kvdo-6.2.3.114-74.el8`{{execute}}

VDO provides block level, inline data reduction for Linux in the form of deduplication,
compression, and thin provisioning.  

VDO is currently delivered as two packages: 
* kmod-kvdo (kernel modules),
* vdo (user-space utilities).  

VDO can be used for local or cloud storage.  VDO can benefit Filesystems,
Ceph, hypervisors, and container environments.  

VDO is comprised of:

Two Kernel modules
* kvdo     - manages block storage and compression,
* uds      - manages the deduplication index.  
    
User space utilities
* vdo      - vdo manager used to create, remove or modify volumes,
* vdostats - view volume statistics.

Detailed information on VDO can be found in the man page.

`man vdo`

Use the 'q' key to exit the man page.

Also, each of the statistics for vdostats can be found in the man page.

`man vdostats`

Use the 'q' key to exit the man page.

