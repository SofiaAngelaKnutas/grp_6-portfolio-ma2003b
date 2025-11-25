# MegaMart Customer Segmentation – Cluster Analysis

# 1. Business Context

MegaMart currently uses a single, generic marketing strategy for all customers, regardless of their purchase frequency, spending level or engagement with campaigns.  
This leads to:

- Low response rates to promotions  
- Inefficient use of marketing budget  
- Difficulty identifying at-risk customers and high-value shoppers  

To address this, we analyzed data from 3,000 customers to find natural behavioral segments. These segments allow MegaMart to:

- Personalize communication and offers  
- Prioritize high-value and high-risk customers  
- Design more efficient, data-driven marketing strategies  


# 2. Methodology

# 2.1 Multivariate method

We applied an unsupervised cluster analysis to group customers with similar shopping behaviors.

- Main algorithm: k-means clustering (with different values of k explored)  
- Objective: find a small number of interpretable, business-relevant segments that can guide marketing actions  


# 2.2 Justification of the method

- Clustering is appropriate because we do not have predefined labels; we want to discover segments directly from behavior.  
- k-means provides compact, well-separated clusters and is widely used in marketing segmentation.  
- The resulting clusters are easy to interpret using averages of key variables (spend, frequency, engagement, returns, etc.), which is crucial for business stakeholders.

# 2.3 Tools and Libraries

The analysis was implemented in Python using:

- `pandas` – data loading, cleaning and feature engineering  
- `numpy` – numerical operations  
- `scikit-learn` – clustering algorithms and preprocessing  
- `matplotlib` / `seaborn` – visualizations  
- `jupyter` – interactive development of the notebook

The main notebook for this case is located in:  
`notebooks/` (see the cluster analysis notebook file in this folder).


# 3. Data)

# 3.1 Description of dataset

- Observations: ~3,000 customers  
- Level: one row per customer  
- Origin: synthetic dataset provided for the course.   

The dataset contains behavioral and value-related variables such as:

- Purchase frequency and recency  
- Total spending and average order value  
- Number of website visits / sessions  
- Number of items returned  
- Email engagement (opens, clicks)  

# 3.2 Key variables

The variables that most strongly defined the segments are, for example:

- Spending behavior – total annual spend, average basket size  
- Frequency – number of purchases / visits  
- Engagement – interaction with email campaigns and promotions  
- Risk / Friction – volume of returns  


### 3.3 Data dictionary

The data dictionary for this case is stored in the `data/` folder of this repository.

- Folder: `case-03-cluster-analysis/data/`  
- Link from this README: [Data folder](./data/)

## 4. Key Findings

Our analysis identified four meaningful customer segments, each with distinct behavior and value potential:

1. High-Value Frequent Shoppers (~17.5%)  
   - Shop often and spend well above average  
   - Rarely return items  
   - Highly engaged with emails and promotions  
   - Represent a critical, very profitable group that must be retained

2. Low-Activity Window-Shoppers (~31%)  
   - Browse or visit but rarely buy, small order values  
   - Higher return rates  
   - Low engagement with emails  
   - Largest churn risk, but also a large pool with conversion potential

3. Luxury Occasional Shoppers (~14.4%)
   - Purchase infrequently but choose high-ticket products  
   - See MegaMart as a place for special or premium purchases  
   - Segment with strong seasonal revenue potential

4. Budget-Conscious Regular Buyers (~37.1%)  
   - Buy consistently throughout the year with moderate spend  
   - Respond well to relevant discounts and practical offers  
   - Form the largest and most stable segment

# 4.1 Visualisation

A key visualization (cluster plot) is stored in:

```text
case-03-cluster-analysis/visualizations/

