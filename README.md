# 🧠 A Comprehensive Study of Income Classification Through EDA & Machine Learning

![Python](https://img.shields.io/badge/Python-3.13.2-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data--Analysis-150458?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green)
![Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Sklearn](https://img.shields.io/badge/Sklearn-1.7.0-blue?logo=scikit-learn)
![Numpy](https://img.shields.io/badge/Numpy-2.2.0-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.9.2-blue?logo=matplotlib)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12.2-blue?logo=seaborn) 
![Plotly](https://img.shields.io/badge/Plotly-5.24.1-blue?logo=plotly)
![Scipy](https://img.shields.io/badge/Scipy-1.14.1-blue?logo=scipy)
![Warnings](https://img.shields.io/badge/Warnings-blue?logo=warnings)
![math](https://img.shields.io/badge/Math-blue?logo=math)

---

## 📊 Project Overview

This project focuses on classifying whether an individual earns more than $50K per year based on a variety of demographic and employment-related attributes. It involves a complete data science pipeline including data cleaning, feature engineering, exploratory data analysis (EDA), and machine learning preprocessing. The dataset contains nearly 49,000 records with rich information about individuals’ age, education, occupation, marital status, and more — making it a strong candidate for income prediction tasks.

---

## 📁 Dataset Details

- **Source:** UCI Machine Learning Repository - Adult Income Dataset
- **Records:** 48,842 rows
- **Features:** 15 columns (age, education, occupation, hours-per-week, etc.)
- **Target Variable:** `income` (`<=50K` or `>50K`)

---

## 🔧 Tools & Libraries

- `pandas`, `numpy`, `math`
- `matplotlib`, `seaborn`, `plotly`
- `sklearn` (LabelEncoder, MinMaxScaler, train_test_split)
- `warnings`, `scipy`

---

## 🔍 Exploratory Data Analysis (EDA)

- Distribution of **age**, **education**, **hours worked**
- Analysis of **income vs gender**, **marital status**, **education**
- **Correlation heatmap** for numerical features
- Interactive **Plotly** visuals and styled tables

---

## 🧹 Preprocessing Steps

✔️ Removed unnecessary characters and spaces  
✔️ Label encoded categorical features  
✔️ Created a binary column `income_group` (0 for `<=50K`, 1 for `>50K`)  
✔️ Scaled numerical features using `MinMaxScaler`  
✔️ Split data into training, validation, and test sets

---

## 🧠 Planned Modeling Steps

> *(Model training not yet included in notebook)*

- Train models: `Logistic Regression`, `Random Forest`, `XGBoost`
- Evaluate with accuracy, precision, recall, F1-score
- Use ROC Curve and Confusion Matrix

---

## 📌 Key Insights

- Age, education level, and workclass strongly influence income
- Marital status and gender also correlate with earning levels
- Higher education often leads to higher income brackets

---

## 📂 Project Structure

```bash
📁 income-classification-eda
├── preprocessing.ipynb      # Main notebook with all EDA & preprocessing
├── adult.csv                # Dataset file
├── README.md                # Project documentation
