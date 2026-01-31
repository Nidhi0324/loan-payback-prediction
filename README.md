# Loan Payback Prediction (Kaggle Playground Series S5E11)

This project predicts whether a borrower will successfully pay back a loan using borrower demographics, financial indicators, and loan-related attributes. The work was developed as part of the Kaggle Playground Series and focuses on robust feature engineering, model optimization, and reliable evaluation for binary classification.

## Dataset
The dataset used in this project is publicly available as part of the Kaggle Playground Series.

- **Dataset link:** https://www.kaggle.com/competitions/playground-series-s5e11/data

## Key Results
- **Final Kaggle submission score:** 0.92280  
- **Best local ROC-AUC performance:**
  - LightGBM (Optuna, GPU): **0.921750**
  - Optimized Logistic Regression: **0.910191**

## Methodology
- Performed exploratory data analysis and data preprocessing to ensure data quality
- Engineered domain-driven features to capture borrower repayment risk
- Applied feature selection using correlation analysis and model-based importance
- Trained and optimized machine learning models including Logistic Regression and LightGBM
- Evaluated models using ROC-AUC and cross-validation to assess generalization performance

## Repository Structure
- `notebooks/loan_payback_prediction.ipynb`  
  Complete end-to-end workflow covering data preprocessing, feature engineering, model training, and evaluation
- `reports/poster.pdf`  
  Project poster summarizing the methodology, experiments, and results

## Reproducibility
1. Install required dependencies:
   ```bash
   pip install -r requirements.txt
2. Run the notebook:
      ```bash
   notebooks/loan_payback_prediction.ipynb
