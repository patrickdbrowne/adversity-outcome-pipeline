# adversity-outcome-pipeline
The notebook contains an adversity outcome prediction training pipeline in scikit-learn to compare the results of logistic regression models applied to the authentic and synthetic MIMIC-III data. AUC-ROC and AUPR evaluation metrics were used across a cohort of five experiments using the FIDDLE preprocessing package.

## Before running the pipeline...
1. Acquire credentialed access to the MIMIC-III database;
2. Change the directory paths listed in the cells as needed; and 
3. Adjust variables that have been removed, indicated by a comment.

## Replication
Outputs for a cohort of experiments reported in Tang et al. 2021 were replicated using the Artemis HPC clusters. These experiments focused on adverse outcomes in ICU stays, including mortality at T=48h, ARF at T=4h, ARF at T=12h, Shock at T=4h, Shock at T=12h.

Feel free to contact me if you would like to discuss the project!
