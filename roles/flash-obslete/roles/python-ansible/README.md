Python Ansible Role
=========

Ansible role for downloading Python source archives to control server, then extracting them to the target host.

Role Variables
--------------
Set the ```python_version``` parameter to install other versions of Python

        python_version: 3.5.2
        
Available versions:

    2.7.12
    3.3.6
    3.4.5
    3.5.2
    3.6.0b1
    3.6.0a4
        

Change Log
-------

- Made the role download the source file onto the remote instead of the local machine, hence eliminating the need for sudo password.


License
-------

CC-BY

Author
-------
Coadunate

