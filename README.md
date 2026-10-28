# 📉 Customer Churn Prediction | Logistic Regression + SMOTE

Predicts which telecom customers are likely to cancel their service. The notebook cleans a messy customer dataset with missing and anomalous values, encodes and scales features, trains a Logistic Regression classifier, balances classes with SMOTE and generates a Kaggle-style submission file.

## Stack
`Python` `pandas` `NumPy` `scikit-learn` `imbalanced-learn` `Jupyter`

## What it does
- Handles missing values (median for numeric, mode for categorical), fixes negative values and cleans blank strings in the training data
- One-hot encodes categorical features and scales numeric ones with `StandardScaler`
- Trains a Logistic Regression model and evaluates it with accuracy, confusion matrix and ROC AUC (5-fold cross-validation mean ROC AUC: 0.9055)
- Rebalances the classes with SMOTE and re-evaluates (ROC AUC after SMOTE: 0.9137)
- Applies the same preprocessing to the test set and writes the predictions to a submission CSV

## How to run
```bash
git clone https://github.com/lucas-wall/Churn-Prediction-Model.git
cd Churn-Prediction-Model
pip install pandas numpy scikit-learn imbalanced-learn jupyter
jupyter notebook churn_prediction.ipynb
```

Data files: `train_churn_.csv` (training data), `test_churn_.csv` (test data), `sample_submission_.csv` (submission template) and `submission.csv` (predictions).
