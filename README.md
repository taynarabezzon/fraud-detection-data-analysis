# Transaction Fraud Detection & Data Quality Pipeline

![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-data__wrangling-150458.svg)
![Domain](https://img.shields.io/badge/focus-data__quality__%26__analytics-orange.svg)

## 📌 Project Overview
This repository contains an exploratory data analysis (EDA) and data quality auditing pipeline developed in Python to identify anomalous behavior and potential fraud in financial transaction datasets. 

By leveraging data wrangling techniques, statistical aggregation, and rule-based validation, this project addresses real-world business challenges related to **risk management, data integrity, and pattern identification**.

---

## 🎯 Key Technical Features
* **Data Cleaning & Wrangling:** Automated processing of raw transaction logs, handling missing values, data type casting, and duplicate removal using `Pandas`.
* **Anomaly Detection & Rule-Based Filtering:** Implementation of threshold logic and pattern matching to flag high-risk transactions.
* **Exploratory Data Analysis (EDA):** Statistical summarization and distribution checks to uncover underlying trends in fraudulent versus legitimate activities.
* **Data Quality & Traceability:** Structuring validation checks to ensure clean, audit-ready data inputs for downstream analytics or reporting layers.

---

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization (Optional):** `Matplotlib`, `Seaborn`
* **Environment:** VS Code, Jupyter Notebooks / Python Scripts, Git/GitHub

---

## 📁 Repository Structure
```text
├── data/
│   └── raw_transactions_sample.csv   # Anonymized sample data (if applicable)
├── notebooks/
│   └── fraud_detection_eda.ipynb     # Exploratory analysis and visual insights
├── src/
│   └── data_cleaning.py              # Production-ready data preparation script
├── .gitignore                        # System and environment exclusions
└── README.md                         # Technical documentation
