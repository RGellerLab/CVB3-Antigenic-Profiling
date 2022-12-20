This folder contains:

1. CVB3_nancy_table_escape_muts_sites: contains evolutionary, structural, and physicochemical information on surface exposed residues of the CVB3 nancy capsid used for the machine learning analyses. 

Escape_site="yes" is indicated for sites with mean positive differential selection values above mean+2SD in the antigenic profiling experiments. Escape_mut="yes" is indicated for mutations within escape sites with positive differential selection values per mutation >2. Misclassified_mut="yes" is indicated for mutations predicted to be wrongly classified by the machine learning classifier, having a probability larger that 70% to belong to the escape_mut="yes" class. 

2. heatmap_escape_sites_ss_region: indicates main sites of escape obtained in the antigenic profiling experiments (positive differential selection value > mean +2SD), mean positive differential selection values per sample and structural location (secondary structure element and region of the capsid).