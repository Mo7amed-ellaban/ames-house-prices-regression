# 🏠 Ames House Prices Prediction
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![CatBoost](https://img.shields.io/badge/CatBoost-Regressor-yellow)
![Kaggle](https://img.shields.io/badge/Kaggle-House_Prices-20BEFF)

End-to-end Machine Learning project for predicting house prices using the Ames Housing Dataset.

## 📌 Project Overview

This project focuses on building a high-performance regression model to predict house sale prices.

The workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Encoding
- Baseline Modeling
- Model Comparison
- Hyperparameter Optimization using Optuna
- Final Kaggle Submission

---

## 📊 Dataset

- Competition: House Prices - Advanced Regression Techniques
- Platform: Kaggle

Dataset:
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- CatBoost
- XGBoost
- LightGBM
- Optuna
- Seaborn
- Matplotlib
- YData Profiling

---

## ⚙ Workflow

1. Data Cleaning
2. Missing Value Handling
3. Feature Engineering
4. Feature Encoding
5. Baseline Random Forest Model
6. Feature Importance Analysis
7. Model Comparison
8. Hyperparameter Tuning (Optuna)
9. Final CatBoost Model
10. Kaggle Submission

---

## 📈 Models

| Model | CV RMSE |
|--------|---------|
| Random Forest (Baseline) | 0.14088 |
| XGBoost | 0.12703 |
| LightGBM | 0.13855 |
| CatBoost | 0.12564 |
| CatBoost + Optuna | **0.12294** |

---
## 📊 Feature Importance

<p align="center">
  <img src="images/feature_importance.png" width="800">
</p>

## 🏆 Kaggle Result

| Metric | Score |
|--------|------:|
| Cross Validation RMSE | **0.12294** |
| Kaggle Public Score | **0.12738** |

Leaderboard Position:

**1602**

---

## 📂 Repository Structure

```
├── Ames_House_Prices.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Future Improvements

- Ensemble Models
- Stacking
- Feature Selection
- Advanced Feature Engineering

---

## 👨‍💻 Author

**Mohamed Ehab Ellaban**

Faculty of Engineering – Mansoura University

Artificial Intelligence Department

🔗 LinkedIn:
[https://www.linkedin.com/in/adel-sobhy-4b97a12aa/](https://www.linkedin.com/in/mohamed-ellaban-a5726a344/)
