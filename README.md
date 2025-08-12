# QSARBoost
<img width="2436" height="1143" alt="qsarboost drawio" src="https://github.com/user-attachments/assets/8d8749b4-b9e9-457f-9867-7ec13d32bfb8" />

QSARBoost is a Python framework for developing gradient boosting–powered QSAR models for molecular bioactivity prediction and virtual screening. This repository applies QSARBoost to the repurposing of DrugBank compounds as SIRT2 inhibitors, but it can be adapted for any regression-based QSAR task.

## Libraries used
**Python 3.x**
**RDKit** – Molecular descriptor/fingerprint generation  
**Scikit-learn** – Machine learning utilities  
**CatBoost / LightGBM / XGBoost** – Gradient boosting algorithms  
**Optuna** – Hyperparameter optimization  
**Pandas** – Data manipulation  
**Matplotlib** – Visualization  

## Features
**Data Curation** – Import, clean, and preprocess chemical datasets from ChEMBL or other sources.   
**Molecular Featurization** – Generate ECFP4 fingerprints or other descriptors using RDKit.  
**Gradient Boosting Models** – Support for multiple boosting algorithms: CatBoost, LightGBM, XGBoost, GradientBoostingRegressor.  
**Model Selection & Optimization** – Hyperparameter tuning via Optuna.  
**Applicability Domain (AD)** – Williams plot & Mahalanobis distance methods for prediction confidence.  
**Virtual Screening** – Apply trained models to large chemical libraries (e.g., DrugBank).  

## Getting Started
### Prerequisites
Install required packages:
```
pip install rdkit-pypi scikit-learn pandas matplotlib catboost lightgbm xgboost optuna
```

## Cloning the Repository
```
git clone https://github.com/yboulaamane/QSARBoost.git
```

## License
This project is released under the MIT License.

## How to cite
Repurposing DrugBank Compounds as SIRT2 Inhibitors via QSAR Modeling with Gradient Boosting Algorithms and All-Atom Molecular Simulations (manuscript in preparation).

## Contact
For questions or feedback, please contact: boulaamane.yassir@etu.uae.ac.ma 
