theme3.2ontologies
=========

Downloads a selection of recommended ontologies for theme 3.2 of P2IRC group.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

coadunate.planteomeontologies
coadunate.pato
coadunate.ontology_of_bio_attributes
coadunate.units_of_measurement_ontology
coadunate.anatomical_entity_ontology
coadunate.plant_phenology_ontology
coadunate.biological_imaging_methods_ontology
coadunate.evidence_and_conclusion_ontology

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: coadunate.theme3.2ontologies }

License
-------

CC-BY

