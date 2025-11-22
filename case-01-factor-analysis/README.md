# Customer Satisfaction Factor Analysis

##  Project Overview
This project analyzes customer satisfaction data from the company **TechnoServe Solutions**, which are a technology consulting firm. The objective is to identify underlying factors that explain how customers evaluate service quality and to determine factors that strongly influence, like for example overall satisfaction and renewal likelihood.


---

## Dataset Description

**File:** `customer_satisfaction_data.csv`  
**Observations:** 3,400  
**Time Period:** Q1–Q4 2024  

The dataset includes:
- Customer identification variables  
- 23 satisfaction variables (1–7 scale) from a survey.
- Outcome metrics such as overall satisfaction, NPS, and renewal likelihood. 

A full data dictionary is included in the
[Data Dictionary](data/CUSTOMER_SATISFACTION_DATA_DICTIONARY-1.md).

---

## Methods

### **1. Data Preparation**
- Removed ID/date/outcome variables for factor analysis  
- Handled missing values
- Standardized the dataset using `StandardScaler`  
- Visualized correlations through a heatmap  

### **2. Suitability Checks**
- **KMO score:** 0.959 (excellent)  
- **Bartlett’s Test:** significant (p < 0.001)  
- **Average item correlation:** 0.337  

These results confirm the dataset is suitable for factor analysis.

### **3. Factor Extraction**
- Scree plot and eigenvalues analyzed  
- Five factors selected using Kaiser’s >1 rule and the elbow method  

### **4. Factor Rotation**
Two rotation methods were compared:
- **Varimax (orthogonal)** → chosen for interpretation  
- **Promax (oblique)**  



---

## Key Finding

### **Five Factors Best Explain the Data**
1. **Technical skills and innovation**  
2. **Trust and relationships**  
3. **Project quality**  
4. **Financial Transparency**  
5. **Support**  


---

## Recommendations for TechnoServe

Based on the results TechnoServe should:

- Improve **pricing clarity** and cost communication  
- Strengthen **client relationships** through better communication and reliability  
- Maintain strong technical excellence and delivery quality  
- Enhance post-project **support and training**  
These actions support higher satisfaction, stronger loyalty, and improved renewal rates.

---

## Visualizations Included

The project generates the following plots:

- Correlation Matrix (heatmap)  
- Scree Plot of Eigenvalues  
- Varimax & Promax Factor Loading Heatmaps  
- Factor Score Distributions (boxplot)  
- Spider Chart (customer satisfaction profile)  

These visualizations are available in the [`visualizations`](visualizations) folder.

---


## Libraries Used

- `pandas`  
- `numpy`  
- `seaborn`  
- `matplotlib`  
- `sklearn.preprocessing`  
- `factor_analyzer`  



---

