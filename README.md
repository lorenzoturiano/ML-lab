Exploratory and modeling notebooks experimenting with machine learning on oncology datasets, focusing on CCLE (Cancer Cell Line Encyclopedia) and TCGA (The Cancer Genome Atlas). The repo includes data exploration and both binary and multi-class classification workflows.
What’s inside the notebooks
Exploration notebooks (*_exploration.ipynb)
Data integrity checks, missingness, distributions
Class balance, label leakage checks
Feature correlations and simple dimensionality reductions (PCA/UMAP)
Classification notebooks (*_bin_class.ipynb, *_multi_class.ipynb)
Train/validation splits with stratification
Baselines (logistic regression / linear models)
Tree-based models (RandomForest, XGBoost)
Model evaluation: ROC-AUC, PR-AUC, accuracy, F1, confusion matrices
Cross-validation and simple hyperparameter sweeps
Feature importance / coefficients and basic interpretability plots
