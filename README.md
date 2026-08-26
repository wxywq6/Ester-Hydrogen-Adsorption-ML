# Ester-Hydrogen-Adsorption-ML
Data and code for interpretable machine learning prediction of hydrogen adsorption in ester oils.

This repository contains the data and source code associated with the manuscript: “An Explainable Machine Learning Framework for Hydrogen Adsorption Prediction Using Stability-Based Molecular Descriptor Selection”

## Overview

This study develops an interpretable quantitative structure–property relationship (QSPR) framework for predicting the hydrogen adsorption capacity of ester molecules. The workflow integrates molecular descriptor calculation, unsupervised descriptor preprocessing, bootstrap-assisted LASSO stability selection, machine learning modeling, and post hoc interpretability analysis.

## Repository Structure
text
data/
Molecular structures, experimental hydrogen adsorption data,
molecular descriptors, and train/test assignments.

code/
Python scripts for descriptor preprocessing, stability selection,
machine learning modeling, model evaluation, and interpretation.

results/
Descriptor-selection scores and model performance.

## Software Requirements
The analyses were conducted using VS Code.
Exact package versions are listed in: requirements.txt
