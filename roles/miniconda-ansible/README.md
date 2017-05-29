## Miniconda Ansible Role

Ansible role for installing the latest version of miniconda.

Dependencies

coadunate.miniconda
Example Playbook

- hosts: servers
  roles:
     - { role: coadunate.miniconda }
License

CC-BY

Author Information

Coadunate


## Credits
This role was adapted from this miniconda role:

- [robinandeer/ansible-miniconda][deployment]
