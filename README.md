# Ester-Hydrogen-Adsorption-ML
Data and code for interpretable machine learning prediction of hydrogen adsorption in ester oils.

This repository contains the data and source code associated with the manuscript: “An Explainable Machine Learning Framework for Hydrogen Adsorption Prediction Using Stability-Based Molecular Descriptor Selection”

## Overview

This study develops an interpretable quantitative structure–property relationship (QSPR) framework for predicting the hydrogen adsorption capacity of ester molecules. The workflow integrates molecular descriptor calculation, unsupervised descriptor preprocessing, bootstrap-assisted LASSO stability selection, machine learning modeling, and post hoc interpretability analysis.

## Repository Structure
code/
    01_descriptor_preprocessing.py
    02_bootstrap_lasso_selection.py

    03_model_training/
        01_RR.py
        02_KRR.py
        03_SVR.py
        04_GPR.py
        05_RF.py
        06_XGBoost.py

    04_model_evaluation.py
    05_shap_analysis.py
    06_pdp_ice_analysis.py
    07_applicability_domain.py
Ester-Hydrogen-Adsorption-ML/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── 01_ester_dataset_56.csv
│   ├── 02_padel_descriptors_1444.csv
│   ├── 03_preprocessed_descriptors_215.csv
│   ├── 04_selected_descriptors_13.csv
│   └── 05_train_test_split.csv
│
├── code/
│   ├── 01_descriptor_preprocessing.py
│   ├── 02_bootstrap_lasso_selection.py
│   ├── 03_model_training/
│   │   ├── 01_RR.py
│   │   ├── 02_KRR.py
│   │   ├── 03_SVR.py
│   │   ├── 04_GPR.py
│   │   ├── 05_RF.py
│   │   └── 06_XGBoost.py
│   ├── 04_model_evaluation.py
│   └── 05_shap+pdp_analysis.py
│    
│
│
└── results/
    ├── descriptor_selection_frequency.csv
    └── model_results_metrics.csv


## Software Requirements

The analyses were conducted using VS Code.
Exact package versions are listed in: requirements.txt
