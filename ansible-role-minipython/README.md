Python 2 and 3 Ansible Role
=========
An ansible role for installing and creating python 2 and 3 environmetns via miniconda.

Dependencies
------------
coadunate.miniconda

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: coadunate.minipython }
         
Environment Access
------------------
```
$source activate py2
$source deactivate
$source activate py3
$source deactivate
```

License
-------

CC-BY

Author Information
------------------

Coadunate
.
