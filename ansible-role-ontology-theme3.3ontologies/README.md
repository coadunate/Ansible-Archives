theme3.3ontologies
=========

Downloads a selection of recommended ontologies for theme 3.3 of P2IRC group.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

coadunate.the_gene_ontology
coadunate.pato
coadunate.planteomeontologies
coadunate.protein_ontology
coadunate.plant_phenology_ontology
coadunate.genotype_ontology
coadunate.chebi_ontology
coadunate.floral_phenotype_ontology
coadunate.units_of_measurement_ontology
coadunate.clinical_measurement_ontology
coadunate.anatomical_entity_ontology
coadunate.biological_spatial_ontology
coadunate.agronomy_ontology
coadunate.genetic_interval_ontology

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: coadunate.theme3.3ontologies }

License
-------

CC-BY

