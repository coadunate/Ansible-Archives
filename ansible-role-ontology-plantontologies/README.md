ansible-role-ontology-plantontologies
=========

Will download a number of plant related ontologies for use with genotype-phenotype analysis and the goals of P2IRC

Requirements
------------

None

Role Variables
--------------

url_list is the list of ontologies that will be downloaded. Only recommended ontologies will be downloaded. To downloaded all ontologies, simply delete 'main.yml' in the vars folder. 

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: coadunate.ontology-plantontologies }

License
-------

CC-BY
