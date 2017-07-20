theme3.5ontologies
=========

Downloads a selection of recommended ontologies for theme 3.5 of P2IRC group.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

coadunate.biological_spatial_ontology
coadunate.pato
coadunate.agronomy_ontology
coadunate.planteomeontologies
coadunate.genotype_ontology
coadunate.the_gene_ontology
coadunate.plant_phenology_ontology
coadunate.ontology_of_bio_attributes
coadunate.units_of_measurement
coadunate.clinical_measurement_ontology
coadunate.kinetic_sim_alg_ontology
coadunate.mathematical_modeling_ontology
coadunate.systems_biology_ontology
coadunate.software_ontology

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: coadunate.theme3.5ontologies }

License
-------

CC-BY
