# DrugScreen_CFTR

# Chem 277 Final Project: Virtual Screen for CFTR
###  Fall 2023
### Qi Tifany Chu


## Project Summary
In this project, I will use an Artificial Neural Network and Random Forest Regressor to predict the binding affinities of ligands to the Cystic Fibrosis Transmembrane Receptor (CFTR).

I will use the binding affinity data (EC50 and IC50) and SMILES strings from two sources: ChemBl and BindingDB. I will turn the smiles strings into Morgan Fingerprints and use that as the input for the Machine Learning Models.

With my learned model, I then plan to recreate a Virtual Screen from a paper published by Sonawane et al. that contains similar ligands (active and inactive) of CFTR. This will allow me to asses the viability of my models and compare them.

## Contents: 
- python notebook (use this to run both models) 
1) Download Data
- Chembl Web
- BindingPD
2) Preprocess data
- Combine Data Sets
- Check for Missing Data & Duplicate Data
- Turn SMILES into Fingerprints
- Convert IC50/EC50 to pIC50/pEC50
3) Artificial Neural Network (ANN) model
- Introduce Functions used for ANN (training and evaluation)
- Parameter Optimization
- Running the models (Loss Curves)
- Model Evaluation (RMSE/MSE/R^2/Accuracy/Baseline)
4) Random Forest (RF) Regression Model
- Optimize Parameters (GridSearchCV)
- Running the model (No Loss Curves in RF)
- Model Evaluation (RMSE/MSE/R^2/Accuracy/Baseline)
- Finding the important chemical motif contributors
5) Test Screen (Sonawane et al.)
- Preprocess Test Screen Data
- ANN Virtual Screen (VS)
- RF Virtual Screen
- Compare with common motifs from RF
6) Discusssion

7) References
