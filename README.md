# 🩺 Health Insurance Premium Prediction

> A machine learning project to predict medical insurance premiums using demographic and health data, inspired by the Codebasics ML course.

---

## ✅ Project Overview

- **Objective:** Build predictive models to estimate insurance premiums based on features such as age, BMI, gender, smoking habits, and health conditions.
- **Modeling Approach:** Includes Exploratory Data Analysis, feature engineering, regression modeling (Linear Regression, XGBoost), and hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
- **Evaluation:** Quantify model performance via metrics like R², MAE, RMSE—Codebasics-based implementations often report accuracy around 99% or R² ~0.98+ :contentReference[oaicite:1]{index=1}.

---

## 📂 Repository Structure

codebasics_ml_health_premium/
├── data/ # Raw and processed datasets (e.g. CSV files)
├── notebooks/ # Jupyter notebooks for EDA and model development
├── main.py # Script to load model and make predictions
├── prediction_helper.py # Functions to preprocess input features and predict
├── requirements.txt # Dependencies (scikit‑learn, pandas, matplotlib, etc.)
└── LICENSE # Apache‑2.0 or MIT License


---

## 🧰 Getting Started

To run the project locally:

```bash
git clone https://github.com/vinaybabu2112/codebasics_ml_health_premium.git
cd codebasics_ml_health_premium
pip install -r requirements.txt
# Launch Jupyter to explore analysis and modeling notebooks
jupyter notebook
