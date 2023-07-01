# Master's Thesis: Using AI to Predict Loan Defaults

The data used in this thesis is LendingClub's public data from 2007 to 2020.

- 00_data_prep_and_eda.ipynb contains data preprocessing and EDA.
- 01_data_prep_for_modeling.ipynb splits the preprocessed data in a training, validation and test set.
- 02_modeling.ipynb contains all of the models used and the training process.
- 03_feature_importance.ipynb has feature importance analysis using SHAP values.
- 04_credit_drift_analysis.ipynb contains functions used to create transition matrices.
- 05_hyperparameter_tuning.ipynb tunes XGBoost and Neural Network model using balanced undersampled data.

Data and figures folder not included in this repository.

----

## Future Work

#### Survival analysis
Given a set of features, try to predict when down the line the loan will default or if it will default at all.
This analysis can be used to assign some sort of score (A, B, etc.) in conjunction with a predicted probability of default from the models in the previous section.

Create python script with a Class which streamlines modeling process in order to test models on many different feature sets. Include a way to store results from the models using these different data sets.
