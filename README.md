# SmartPremium: Insurance Premium Predictor

A beginner-friendly Machine Learning project to predict **Insurance Premium Amount** based on customer demographics, lifestyle, and policy details.  
Built using **Python, Scikit-Learn, XGBoost, MLflow, and Streamlit**.

---

## Project Workflow

1. Load Data (`train.csv`, `test.csv`, `sample_submission.csv`)  
2. Perform EDA (explore data, check missing values, visualize distributions)  
3. Preprocess Data (handle missing values, encode categoricals, scale numerics, feature engineering)  
4. Train-Validation Split (80/20)  
5. Model Development  
   - Linear Regression (baseline)  
   - Random Forest  
   - XGBoost (tuned)  
6. Evaluate Models (RMSE, MAE, R², RMSLE)  
7. Select Best Model (XGBoost Tuned Full Data)  
8. Predict on `test.csv` → Generate `insurance_predictions.csv`  
9. Deploy with **Streamlit App**  
10. Document everything in GitHub  

---

## Files in Repository

- `train.csv` → Training dataset  
- `test.csv` → Test dataset  
- `sample_submission.csv` → Format for submission  
- `insurance_predictions.csv` → Final predictions  
- `app.py` → Streamlit web app  
- `model_comparison.csv` → Model evaluation results  
- `artifacts/` → Saved ML pipeline  
- `README.md` → Project documentation  

