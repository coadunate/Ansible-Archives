ansible-role-ontology-planteomeontologies
=========

Downloads the ontologies found on planteome

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

coadunate.ontology-theplantontology
coadunate.ontology-plant_environment_ontology
coadunate.ontology-plant_trait_ontology

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: coadunate.ontology-planteomeontologies }

License
-------

CC-BY