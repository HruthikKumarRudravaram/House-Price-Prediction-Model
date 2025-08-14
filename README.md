# 🏠 House Price Prediction: The Hero Edition 🦸‍♂️

## Project Overview
Ever wondered if predicting house prices could be as epic as saving the multiverse? Well, now it can! Using the Kaggle "House Prices: Advanced Regression Techniques" dataset, this project unleashes **data science superpowers** to predict how much your dream Stark Tower (or just a regular house) costs.  

**Tech Stack:** Python 3.8+, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Joblib  

---

## Dataset
- **Source:** [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)  
- **Files used:** `train.csv` (heroes in training), `test.csv` (the final battle)

---

## Infinity Stone Plan (Project Steps) 💎

1. **Setup – Wakanda Style**
   - Install packages:  
     ```bash
     pip install pandas numpy matplotlib seaborn scikit-learn joblib
     ```
   - Download Kaggle dataset via API or manually. Assemble your dataset like the Avengers.

2. **Exploratory Data Analysis (EDA) – Vision Mode**
   - Peek into the data (`head()`, `info()`, `describe()`).
   - Visualize missing values, correlations, and distributions. Spot the Thanos of missing data!

3. **Data Cleaning & Feature Engineering – Iron Man Upgrades**
   - Handle missing values like a pro:
     - Numeric → median (Jarvis-approved)
     - Categorical → mode (because superheroes love order)
   - Log-transform `SalePrice` to tame the Hulk-level skewness.
   - Build new powers… err, features like `TotalSF` (total square footage = your Iron Man suit of features).
   - One-hot encode categorical variables (because we can’t have Loki confusing the model).
   - Align train & test sets – no hero left behind!

4. **Modeling – Avengers Assemble**
   - Baseline: predict the mean (basic Hulk smash).
   - Linear Regression: classic Captain America shield.
   - Random Forest Regressor: Thor’s hammer (Mjolnir) of predictive power.
   - k-fold cross-validation: test your heroes in multiple battles.
   - Hyperparameter tuning (GridSearchCV) = Wakanda tech upgrade.

5. **Model Evaluation – The Battle Report**
   - Baseline RMSE: 0.0093 (no gauntlet yet)
   - Linear Regression RMSE: 0.0037 (Shield on)
   - Random Forest RMSE: 0.0031, R²: 0.8619 (Mjolnir mode activated!)
   - Feature engineering = ~60–70% gain. Infinity Stones collected.

6. **Saving & Inference – Endgame**
   - Save final model with Joblib (lock it in the vault like Captain America’s shield).
   - Load model and predict new house prices. Be the hero the neighborhood deserves.

---

## How to Run (Hero Edition)
1. Clone the repo:
```bash
git clone https://github.com/HruthikKumarRudravaram/House-Price-Prediction-Model.git
