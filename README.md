#  House Price Prediction — End-to-End Machine Learning Project

This repository contains a complete end-to-end **Machine Learning regression project** focused on predicting house prices.  
The workflow includes **Exploratory Data Analysis (EDA)**, **advanced feature engineering**, **feature selection**, and dataset preparation for building high-performance predictive models.

This project follows a real-world ML pipeline used in analytics teams and Kaggle competitions.

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Dataset Description](#dataset-description)  
3. [Project Workflow](#project-workflow)  
4. [Folder Structure](#folder-structure)  
5. [Notebooks Included](#notebooks-included)  
6. [Technologies Used](#technologies-used)  
7. [Future Work](#future-work)  
8. [Author](#author)

---

##  Project Overview

The objective of this project is to predict **house prices** using a structured dataset containing numerical, categorical, and engineered features.

This is a practical ML workflow demonstrating:
- Data cleaning  
- Missing value treatment  
- Outlier detection  
- Feature engineering  
- Variable encoding  
- Skewness correction  
- Feature selection  
- Preparing the final modeling dataset  

This structure reflects industry best practices for building accurate regression models.

---

##  Dataset Description

The dataset includes:
- **Numerical features**: area, square footage, year built, basement size, garage area, etc.  
- **Categorical features**: neighborhood, exterior quality, building type, heating/cooling type, and more  
- **Target variable**: **SalePrice**

Dataset is similar to the Kaggle *House Prices: Advanced Regression Techniques* competition.

---

##  Project Workflow

Below is the full ML pipeline followed in this project:

Raw Data
│
├ Exploratory Data Analysis (EDA)
│ - Missing values
│ - Outliers
│ - Distributions
│ - Correlation heatmaps
│
├ Advanced Feature Engineering
│ - Handling missing data (domain logic)
│ - Ordinal & label encoding
│ - Rare category grouping
│ - Skewness correction
│ - Creating new engineered features
│
├ Feature Selection
│ - Correlation-based selection
│ - Variance Inflation Factor (VIF)
│ - Recursive Feature Elimination (RFE)
│ - Feature importance ranking
│
├ Final Dataset Ready for Modeling
│
└ (Future) Model Training & Evaluation


---

##  Folder Structure


---

## 🧪 Notebooks Included

### **1. Exploratory Data Analysis (EDA)**  
File: `1_EDA/House_price_exploratory_data_analysis.ipynb`

Includes:
- Data overview  
- Missing values analysis  
- Outlier detection  
- Distribution plots  
- Correlation heatmap  
- Understanding relationships with SalePrice  

---

### **2. Advanced Feature Engineering**  
File: `2_Feature_Engineering/Feature_Engineering_advanced_house_prices.ipynb`

Key steps:
- Handling missing values using domain knowledge  
- Ordinal encoding for quality-related features  
- Label encoding for categorical variables  
- Rare category grouping  
- Creating meaningful engineered variables  
- Log-transformations for skewness  

---

### **3. Feature Selection**  
File: `3_Feature_Selection/Feature_selection_advance_house_price_prediction.ipynb`

Techniques applied:
- Correlation thresholding  
- Variance Inflation Factor (VIF)  
- Univariate selection  
- Recursive Feature Elimination (RFE)  
- Feature importance from Tree-based models  

Output:  
A final dataset ready for model training.

---

##  Technologies Used

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  

---

##  Future Work

Planned additions:
- Baseline Linear Regression model  
- Lasso & Ridge Regression  
- Random Forest & Gradient Boosting  
- XGBoost & LightGBM  
- Hyperparameter tuning  
- Cross-validation  
- Model explainability (SHAP values)  
- Deployment-ready pipeline  

---

## Author

**Soumen Manna**  
| Machine Learning & Data Science 

Focused on building well-structured ML projects that demonstrate strong analytical thinking and technical skills.

---

If you found this useful, please ★ **star this repository** to support the project!
