# tcga_thyroid

Goal of project: To classify variants into deleterious and passenger.

Path of scripts:
  1. import_maf_files
  2. create_test_feature_vector
  3. create_training_feature_vector
  4. classify_mutations
  
Scripts that create (necessary) components but only have to be run once:
  -The output of these scripts should already be present on github
  create_gene_interaction_network: uses human net to create gene interaction network
  find_gene_neighborhoods: starting script for future task of finding clusters of mutations
  find_densities_of_nodes: given a graph, this script finds the density scores
  cluster_patients: contains initial code to cluster patients, to be continued once gene neighborhoods are found
  create_cosmic_id_converter: creates a data frame with cosmic mutation id, entrez gene id, chromosome and location; used for convering between tcga and cosmic data
  create_protein_residue_converter: creates a data frame with 
