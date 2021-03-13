# CYP2C9 activity and abundance score analysis

This repository houses the analysis pipeline for the manuscript "Massively parallel characterization of CYP2C9 variant enzyme activity and abundance". The "CYP2C9_activity_abundance_analysis.Rmd" R Markdown file is intended to be run with R Studio. This markdown file will analyze the data for the CYP2C9 manuscript, using input files in the "data" folder. The two main input files are the CYP2C9 variant and positional activity and abundance data score tables, "CYP2C9_activity_abundance_scores.csv" and "CYP2C9_activity_abundance_positional_scores.csv", respectively. To run this script, place the "data" folder and all containing files in the same directory as this R Markdown file and allow the analysis to proceed. 

Files in the data folder: 
1. "CYP2C9_activity_abundance_scores.csv" CYP2C9 variant activity and abundance scores
2. "CYP2C9_activity_abundance_positional_scores.csv" CYP2C9 median activity and abundance scores by position
3. "CYP2C9_validation_data.csv" Data from individual variant validation of both activity and abundance scores
4. "click_probe_optimization_data.csv" Data from optimization of Click-seq activity-based probes
5. "CYP2C9_human_variant_data.csv" gnomAD and CPIC CYP2C9 human variant data
6. "CYP2C9_computational_predictor_data.csv" Predicted score of CYP2C9 variants from CADD, PolyPhen2, and SIFT. 
7. "CYP2C9_rsa_data.csv" Relative solvent accessibility for CYP2C9 posiitons
8. "sstruct_1r9o_helix.csv" Secondary structure coordinates (helices) for CYP2C9 structure (PDB: 1R9O)
9. "sstruct_1r9o_sheet.csv" Secondary structure coordinates (sheets) for CYP2C9 structure (PDB: 1R9O)

Additionally, create a directory titled "output" in the same directory as this R Markdown file to create the graphics files used to generate the figures. This R Markdown file will also create a series of ".pml" files that can be loaded into PyMOL to generate the CYP2C9 structure images for this manuscript. 
