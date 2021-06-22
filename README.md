# biomarker-paper-2021
Public reference code for the paper _Machine Learning Prediction of Blood and Urine Biomarkers from Genotype and of Disease Risk from Biomarkers in the UK Biobank_.

## Disclaimer
The code is not entirely self-contained and is not runnable as is since none of the research data is included. The original data is protected under agreements with UK Biobank (UKB). To obtain access to the data, please be referred to UKB's application process (https://www.ukbiobank.ac.uk). 

The code in this repo is thus published as a supporting reference for the paper and not as a piece of functioning software. The notebook relies on early versions of MSU-Hsu-Lab packages which, at the time of publishing the paper, were not yet public. Those packages may or may not have been published since then and the reader is recommended to check out the other lab repositories if functionalities imported from other modules are of interest. Since this code is published _as is_ and without extensive documentation, any questions about it or the methodology are welcome by the corresponding authors.

## Overview of content
- Jupyter notebook biomarker_paper.ipynb
  - Phenotype inspections
    - phenotype distribution plots, age dependence etc.
  - Analyses of PGS results
  - Construction and analyses of BMRS and gBMRS
  - ASCVD Risk Estimator comparison

- Predictor files are located in https://www.dropbox.com/sh/2lekipbt9bs1jv5/AABERpXEm3JKa2wMCO1ZkpCHa?dl=0
  - Files with summary SNP data and effect sizes for PGS, PRS and BMRS predictors
