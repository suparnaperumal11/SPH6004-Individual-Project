# SPH6004-Individual-Project
In this study MIMIC – IV database is used to develop a predictive model using machine leaning to forecast the chance of patient mortality in ICU.

## Files
icu_mortality_prediction.py — complete pipeline including data preprocessing, 
feature selection, model training, threshold optimisation, and evaluation

## Output Files
model_results.csv  — model performance at default threshold
model_results_tuned.csv - model performance after threshold tuning
feature_selection_stepwise.csv — stepwise audit trail
feature_selection_elasticnet.csv - features selected by elasticnet
feature_selection_genetic.csv - features selected by genetic
confusion_matrices_tuned.png — confusion matrices
roc_curves.png — ROC curves all models
model_comparison.png — performance bar charts
## Dataset 
MIMIC-IV clinical database https://physionet.org/content/mimiciv/
Note: Dataset requires a signed data use agreement and is NOT included in this repository.

## Requirements
pip install pandas numpy scikit-learn matplotlib
