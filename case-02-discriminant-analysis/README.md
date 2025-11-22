# LendSmart Credit Risk – Discriminant Analysis

## Project Overview
This project analyzes loan applicant data from **LendSmart**, a financial services company seeking to reduce its loan default rate.  
The objective is to build a statistical classification model that predicts whether a new applicant is likely to default, enabling more informed credit decisions.

Two supervised classification methods were applied and compared:
- **Linear Discriminant Analysis (LDA)**
- **Quadratic Discriminant Analysis (QDA)**

---

## Dataset Description

**File:** `credit_risk_data-1.csv`  
**Observations:** 2,500  
**Variables:** 18 applicant and financial attributes  

The dataset includes:
- Demographic characteristics  
- Financial stability indicators  
- Credit behavior metrics  
- Binary loan default outcome (`loan_status`)  

A full data dictionary is included in the  
[Data Dictionary](data/CREDIT_RISK_DATA_DICTIONARY-2.pdf).

---

## Methods

### **1. Exploratory Data Analysis (EDA)**
- Summary statistics and data validation  
- Distribution plots for continuous variables  
- Default rate calculation (28%)  
- Correlation heatmap for numeric predictors  

### **2. Data Preparation**
- Dummy encoding of categorical variables  
- Train–test split with stratification  
- Feature scaling using `StandardScaler`  

### **3. Modeling**
Two discriminant models were trained and evaluated:
- **LDA:** assumes equal covariance matrices across classes  
- **QDA:** allows class-specific covariance structures  

### **4. Evaluation Metrics**
- Accuracy, precision, recall, F1-score  
- Confusion matrices  
- ROC curves and AUC scores  
- Business interpretability of coefficients  

---

## Key Findings
- Both LDA and QDA achieved strong predictive performance.
  - **LDA slightly outperformed QDA** while remaining simpler to interpret.
- The most influential risk indicators included:
  - Credit utilization  
  - Debt-to-income ratio  
  - Payment history  
  - Job stability  

---

## Visualizations Included

The project generates the following plots:

- Correlation Matrix of Numeric Variables 
- LDA & QDA Confusion Matrices  
- ROC Curve Comparison  

These visualizations are available in the [`visualizations`](visualizations) folder.

---

## Libraries Used

- `pandas`  
- `numpy`  
- `seaborn`  
- `matplotlib`  
- `scikit-learn` 

---