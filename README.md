# Diels_Alder_CO2
Scripts to reproduce figures in CO2 Diels Alder paper: \
Paper information: Computational Investigation of a CO2 Conversion Strategy via Diels–Alder Reaction in a Carbon Capture Solvent, ACS Omega 2025, 10, 22, 23663–23672 (https://pubs.acs.org/doi/10.1021/acsomega.5c02620 )

Dataset_and_PCA: to create the dataset, and perform PCA analysis as needed in the older version. \
Generate_new_diene: build new diene structures for computational screening. \
Previous_version_ML_prediction: an older version to train ML models and perform screening for new dienes. Keep for reproduction. \
Code_for_paper: Train ML models and perform screening in the paper. \
Additional details are provided in the scripts' comments.

feature_final, model_final, and scaler_final are the finalized parameters that can be directly used.

A data repository can be found at: https://doi.org/10.6084/m9.figshare.24313807.v3 (or https://figshare.com/articles/dataset/Datasets_for_CO2_DA_paper/24313807) 
This contains the dataset of HOMO/LUMO energies used in this work, their energies, and XYZ coordinates.
