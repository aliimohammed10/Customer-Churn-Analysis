# 📊 Customer Churn Analysis

> An end-to-end Data Science project to predict customer churn for a telecom company, potentially saving **$185K+ annually**.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🎯 Project Overview

A telecom company was losing **26.5% of its customers annually**, equivalent to ~$1.87M in lost revenue. This project builds an AI-powered early warning system to predict churn before it happens, enabling proactive retention strategies.

**Final Project** for the **Orange Digital Center Scholarship** delivered by **Global Knowledge Egypt**.

---

## 🏆 Key Results

| Metric | Value |
|--------|-------|
| 🎯 Model Accuracy | 84% |
| 🎯 Recall (Catch Rate) | 78.6% |
| 💰 Net Business Value | $185,400 (test sample) |
| 🚀 Scaled Annual Savings | ~$925K |

---

## 🔍 Key Insights

1. **Contract Length is King**: Two-year contract customers churn at 2.83% vs 42.71% for month-to-month — a **15x difference!**
   
2. **Fiber Optic Quality Issue**: 41.89% of Fiber Optic users churn — possible service quality problem requiring investigation.
   
3. **First-Year Critical**: New customers (first year) show 47% churn rate, highlighting the need for an onboarding program.

---

## 📊 Project Structure
Customer-Churn-Analysis/
│
├── notebooks/
│   └── Customer_Churn_Analysis.ipynb
├── data/
│   ├── WA_Fn-UseC_-Telco-Customer-Churn.csv
│   └── telco_cleaned.csv
├── presentation/
│   └── Customer_Churn_Analysis.pdf
├── images/
└── README.md


---

## 🛠️ Tech Stack

- **Language**: Python 3.10
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Environment**: Google Colab

---

## 🔬 Methodology

### 1️⃣ Data Exploration & Cleaning
- Analyzed 7,043 customers across 21 features
- Identified and fixed 11 hidden missing values in `TotalCharges`
- Type conversions and feature engineering

### 2️⃣ Exploratory Data Analysis (EDA)
- Demographic analysis
- Service analysis
- Contract & Payment analysis
- Numerical features distribution

### 3️⃣ Machine Learning Modeling
- One-Hot Encoding (30 features)
- Stratified Train/Test Split
- Feature Scaling (StandardScaler)

#### Model Comparison:

| Metric | Logistic Regression | Random Forest |
|--------|---------------------|---------------|
| Accuracy | 0.7402 | 0.7637 |
| Precision | 0.5069 | 0.5400 |
| **Recall** | **0.7861** ⭐ | 0.7406 |
| F1-Score | 0.6164 | 0.6246 |
| ROC-AUC | 0.8414 | 0.8420 |

**Selected Model**: Logistic Regression (higher Recall + interpretability)

### 4️⃣ Business Value Analysis

| Item | Value |
|------|-------|
| Customers Saved (TP) | +$294,000 |
| Customers Missed (FN) | -$80,000 |
| Retention Offer Cost | -$28,600 |
| **Net Value** | **+$185,400** |

---

## 📈 Visualizations

### Churn Distribution
![Churn Distribution](images/churn_distribution_presentation.png)

### Contract Type Impact
![Contract Type vs Churn](images/contract_churn_presentation.png)

### Top Features Driving Churn
![Feature Importance](images/feature_importance_presentation.png)

### Business Value Breakdown
![Business Value](images/business_value_presentation.png)

---

## 🎯 Business Recommendations

1. **Push Annual Contracts**: Incentive program to convert month-to-month customers to longer contracts
2. **Investigate Fiber Optic**: Quality audit on Fiber Optic service to address the 42% churn rate
3. **Onboarding Program**: Special retention strategy for first-year customers
4. **Deploy AI System**: Production deployment for daily risk scoring

---

## 📊 Dataset

- **Source**: [Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Records**: 7,043 customers
- **Features**: 21 (demographics, services, billing, contracts)

---

## 🙏 Acknowledgments

Special thanks to:

- **Eng. Ali Afifi** — Our instructor throughout the program, whose dedication, patience, and practical approach made this project possible. He didn't just teach us tools, he taught us how to think like Data Scientists.

- **Orange Digital Center** — For the scholarship opportunity that enabled this learning journey.

- **Global Knowledge Egypt** — For delivering an outstanding program with high-quality content.

---

## 📫 Contact

- **LinkedIn**: [https://www.linkedin.com/in/alii-mohamed/]
- **Email**: [aliimoha12345@gmail.com]

---

⭐ If you found this project useful, please give it a star!


