# Methodology Comparison

This document compares the three multivariate methods used in the portfolio: Factor Analysis, Discriminant Analysis, and Cluster Analysis. The comparison highlights their purpose, data requirements, analytical outputs, and ideal use cases.

---

## 1. Comparative Table

| Aspect | Factor Analysis | Discriminant Analysis | Cluster Analysis |
|--------|-----------------|------------------------|------------------|
| Type of learning:| Unsupervised | Supervised | Unsupervised |
| Primary objective | Identify latent variables and reduce dimensionality | Classify observations into predefined categories | Discover natural groups in the data |
| Inputs required | Continuous variables | Categorical outcome + predictors | Mostly continuous variables |
| Output | Factor loadings and factor scores | Discriminant functions and classification rules | Cluster assignments and centroids |
| Best use case | Understanding underlying constructs; simplifying large variable sets | Predicting group membership; automated decision rules | Customer segmentation; grouping similar observations |
| Assumptions | Linear relationships; adequate sample size | Multivariate normality; equal covariances (LDA); independence | Distance-based similarity; standardized features |
| Limitations | Interpretation can be subjective | Sensitive to assumption violations | Clusters may vary depending on initialization |

---

## 2. When to Use Each Method

# Factor Analysis
Use when:
- Many variables measure related concepts  
- The goal is to uncover latent dimensions  
- The dataset requires simplification before further modeling  

Ideal for: customer satisfaction surveys, psychometric scales, product attributes.

---

# Discriminant Analysis
Use when:
- The outcome variable is categorical  
- The goal is accurate and interpretable classification  
- Predictive rules are needed to support decisions  

Ideal for: credit scoring, customer churn prediction, risk category assignment.

---

# Cluster Analysis
Use when:
- The goal is to find natural groups within data  
- No predefined labels exist  
- Segmentation supports marketing or personalization strategies  

Ideal for: customer segmentation, product grouping, behavioral segmentation.

---

# 3. Summary

Each method plays a critical role in transforming data into business value:

- Factor Analysis reveals the hidden structure behind complex datasets.  
- Discriminant Analysis converts insights into predictive decision frameworks.  
- Cluster Analysis translates behavior into actionable market segments.

Together, they illustrate the versatility and strategic impact of multivariate analytics in organizational decision-making.

