# Diabetes-Readmission-Predictive-Analysis

## Overview

This project focuses on the exploratory and predictive analysis of diabetes patient readmission data using Python.

The notebook demonstrates essential data science workflows including data loading, preprocessing, missing value treatment, categorical and numerical variable analysis, outlier handling, statistical testing, and multivariate exploratory data analysis (EDA).

The main objective of the project is to identify the variables that may influence the probability of hospital readmission within 30 days for diabetic patients.

---

## Dataset

The project uses a dataset containing information about hospital admissions of diabetic patients.

The dataset includes:
- Demographic information
- Hospital admission data
- Medical diagnoses
- Medications and treatments
- Laboratory procedures
- Readmission indicators

Main variables analyzed include:

- `readmit_30_days`: target variable indicating 30-day readmission
- `time_in_hospital`
- `num_lab_procedures`
- `num_medications`
- `number_diagnoses`
- `medical_specialty`
- `insulin`
- `diabetesMed`

---

## Main Tasks Performed

- Loading and inspecting datasets
- Missing value identification and treatment
- Categorical variable preprocessing
- Rare category grouping
- Boolean variable conversion
- Numerical variable analysis
- Outlier detection and treatment
- Correlation analysis
- Contingency table analysis
- Statistical hypothesis testing
- Bivariate exploratory data analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## Statistical Techniques Applied

- Tukey Outlier Detection
- Kruskal-Wallis Test
- Mann-Whitney U Test
- Chi-Square Test
- Correlation Analysis

---

## Project Structure

```text
Diabetes_Readmission_Predictive_Analysis/
│
├── data/
│   └── diabetes.csv
│
├── notebooks/
│   ├── Diabetes_Readmission_Predictive_Analysis_English.ipynb
│   └── Analisis_Predictivo_Recaida_Diabetes_Español.ipynb
│
├── README.md
└── requirements.txt
