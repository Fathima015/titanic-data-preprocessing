# titanic-data-preprocessing

## Overview

This project is part of an AI & ML Internship task focused on **data cleaning and preprocessing** using the Titanic dataset from Kaggle. The goal is to clean raw data and make it suitable for machine learning models.

---

## What to Learn

- How to explore and understand data
- Handling missing values with mean/median/imputation
- Encoding categorical features (label & one-hot encoding)
- Normalizing and standardizing numerical features
- Detecting and removing outliers using boxplots and IQR

---

## Dataset

**Source**: [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
File used: `titanic-dataset.csv`

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Seaborn / Matplotlib
- Scikit-learn

---

## Key Steps Performed

### 1. Import and Inspect Data
- Checked data types and missing values
- Viewed sample records with `.head()` and `.info()`

### 2. Handle Missing Values
- `Age`: Filled with median
- `Embarked`: Filled with mode
- `Cabin`: Dropped due to excessive nulls

### 3. Categorical Encoding
- `Sex`: Label encoded (male = 0, female = 1)
- `Embarked`: One-hot encoded

### 4. Feature Scaling
- Standardized `Age` and `Fare` using `StandardScaler`

### 5. Outlier Detection & Removal
- Boxplots for `Age` and `Fare`
- Removed outliers using IQR method

---

## Visualizations

Included boxplots for:
- `Age`
- `Fare`

These helped identify and remove outliers to improve data quality.

---
