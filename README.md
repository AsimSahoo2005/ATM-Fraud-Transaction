# ATM Fraud Transaction Detection

A machine learning project for identifying fraudulent ATM transactions using transaction data and exploratory analysis.

## Project Structure

- `atm_fraud_detection.ipynb` — Main Jupyter notebook containing data loading, preprocessing, model training, evaluation, and visualization.
- `data/` — Dataset directory with CSV files used for training and testing.

## Data Files

- `data/train.csv` — Training dataset used to build and validate models.
- `data/test_private.csv` — Private holdout dataset for final evaluation.
- `data/test_share.csv` — Shared test dataset for model comparison.
- `data/Geo_scores.csv` — Geographic location scores or features.
- `data/instance_scores.csv` — Instance-level scoring or derived features.
- `data/Lambda_wts.csv` — Lambda weights used for feature engineering or model combination.
- `data/Qset_tats.csv` — Quality set or transaction attribute scores.

## How to Use

1. Open `atm_fraud_detection.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the notebook cells sequentially to load the data, preprocess features, and train fraud detection models.
3. Review the evaluation section to understand model performance and fraud detection metrics.

## Notes

- Ensure the `data/` folder is present and contains the required CSV files before running the notebook.
- The notebook is the central analysis and model development artifact for this project.
