# Customer Credit Risk Analysis Project

## 📌 Project Overview

This project focuses on performing complete Data Analysis and Data Preprocessing on a synthetic Customer Credit Risk dataset.

The project demonstrates:
- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Missing Value Handling
- Outlier Detection & Treatment
- Feature Engineering
- Encoding Techniques
- Feature Scaling
- Feature Transformation
- SQL Database Handling
- Final Dataset Preparation for Machine Learning

---

# 📂 Project Structure

```text
Customer_Project/
│
├── customer_credit_risk_project.ipynb
├── customer_credit_risk_dataset.csv
├── customer_metadata.json
├── customer_credit_risk.db
├── final_cleaned_credit_dataset.csv
└── README.md
```

---

# 📊 Dataset Information

## Dataset Shape

```python
(1000, 15)
```

## Features

| Column Name | Description |
|---|---|
| customer_id | Unique customer ID |
| age | Customer age |
| gender | Gender |
| region | Customer region |
| education_level | Education qualification |
| employment_type | Employment category |
| annual_income | Annual income |
| loan_amount | Loan amount |
| loan_purpose | Purpose of loan |
| credit_score | Credit score |
| repayment_history | Previous repayment count |
| transaction_count | Number of transactions |
| spending_ratio | Spending ratio |
| join_date | Customer join date |
| default_flag | Loan default target variable |

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- SQLite
- JSON

---

# 📈 Tasks Performed

## 1. Data Acquisition
- Loading CSV files
- Reading JSON files
- Reading SQLite database

## 2. Exploratory Data Analysis (EDA)
- Dataset understanding
- Statistical analysis
- Missing value analysis
- Data visualization

## 3. Missing Value Handling
- Simple Imputer
- Most Frequent Imputation
- Random Sample Imputation
- Missing Indicator
- KNN Imputer
- MICE Imputer

## 4. Outlier Detection & Treatment
- Boxplots
- Z-score method
- IQR method
- Winsorization

## 5. Feature Engineering
- Debt-to-income ratio
- Date feature extraction
- Monthly transaction calculation

## 6. Encoding Techniques
- Label Encoding
- Ordinal Encoding
- One-Hot Encoding

## 7. Numerical Feature Processing
- Binning
- Quantile Binning
- Binarization

## 8. Feature Scaling
- StandardScaler
- MinMaxScaler
- RobustScaler
- MaxAbsScaler

## 9. Feature Transformation
- Log Transformation
- Square Root Transformation
- Box-Cox Transformation
- Yeo-Johnson Transformation

## 10. Column Transformer Pipeline
- Numerical preprocessing pipeline
- Categorical preprocessing pipeline

---

# 🧠 Machine Learning Problem

## Problem Type
Binary Classification

## Target Variable

```python
default_flag
```

- 0 → No Default
- 1 → Default

---

# ▶️ How to Run the Project

## Step 1
Clone or download the project.

## Step 2
Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn missingno
```

## Step 3
Open Jupyter Notebook:

```bash
jupyter notebook
```

## Step 4
Run:

```text
customer_credit_risk_project.ipynb
```

---

# 📌 Key Learnings

- Real-world data preprocessing
- Handling missing data
- Detecting and treating outliers
- Feature engineering techniques
- Encoding categorical data
- Feature scaling methods
- Data transformation techniques
- Building preprocessing pipelines

---

# 📷 Visualizations Included

- Heatmaps
- Boxplots
- Missing Value Matrix
- Distribution Plots
- Statistical Summaries

---

# 📁 Output Files

| File | Purpose |
|---|---|
| customer_credit_risk_dataset.csv | Raw dataset |
| customer_metadata.json | Dataset metadata |
| customer_credit_risk.db | SQLite database |
| final_cleaned_credit_dataset.csv | Final processed dataset |

---

# 👨‍💻 Author
Keval Rampariya
