# 🛡️ Fraud Detection Data Analysis & Modeling

This repository contains a complete Data Science pipeline developed in Python to identify anomalous behaviors, audit data quality, and build predictive Machine Learning models for financial fraud detection.

The project addresses real-world business challenges related to risk management, pattern identification, and imbalanced data classification in credit card transactions.

---

## 🎯 Key Features & Workflow

The analysis and modeling workflow is split into two main Jupyter Notebooks:

1. **Exploratory Data Analysis & Data Quality (`notebooks/project_fraud_detection_1.ipynb`)**:
   - Automated processing of raw transaction logs, handling missing values, and data type casting.
   - Exploratory Data Analysis (EDA) and statistical checks to uncover underlying patterns in legitimate vs. fraudulent activities.
   - Anomaly detection, threshold logic, and rule-based filtering to flag high-risk transactions.
   - Data resampling techniques (such as **SMOTE**) to address severe class imbalance.

2. **Machine Learning & Evaluation (`notebooks/project_fraud_detection_2.ipynb`)**:
   - Model training using various classification algorithms (e.g., Logistic Regression, Random Forest, XGBoost, LightGBM).
   - Evaluation focused on metrics suitable for imbalanced datasets: **Precision**, **Recall**, **F1-Score**, **ROC-AUC**, and **PR-AUC**.
   - Hyperparameter tuning to maximize fraud capture while minimizing false positives.

---

## 🛠️ Tech Stack

- **Language:** Python 3.10+
- **Data Wrangling:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning & Resampling:** `scikit-learn`, `imbalanced-learn`, `xgboost`, `lightgbm`
- **Environment & Tools:** VS Code, Jupyter Notebooks, Git & GitHub

---

## 📁 Repository Structure

```text
.
├── notebooks/
│   ├── project_fraud_detection_1.ipynb  # Exploratory Data Analysis & Preprocessing
│   └── project_fraud_detection_2.ipynb  # Modeling & Performance Evaluation
├── .gitignore                           # Git exclusions for environment & local data
├── README.md                            # Project documentation
└── requirements.txt                     # Project dependencies & versions
