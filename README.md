# tcga_thyroid

Goal of project: To classify variants into deleterious and passenger.

Path of scripts:
  1. import_maf_files
  2. create_test_feature_vector
  3. create_training_feature_vector
  4. classify_mutations
  
Scripts that create (necessary) components but only have to be run once (already done):
  1. create_gene_interaction_network: uses human net to create gene interaction network
  2. find_gene_neighborhoods: starting script for future task of finding clusters of mutations
  3. find_densities_of_nodes: given a graph, this script finds the density scores
  4. cluster_patients: contains initial code to cluster patients, to be continued once gene neighborhoods are found
  5. create_cosmic_id_converter: creates a data frame with cosmic mutation id, entrez gene id, chromosome and location; used for convering between tcga and cosmic data
  6. create_protein_residue_converter: creates a data frame with 
