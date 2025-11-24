# Portfolio Overview

This portfolio consolidates three multivariate analyses completed throughout the course MA2003B. The work covers three distinct business cases and three core analytical techniques: Factor Analysis, Discriminant Analysis, and Cluster Analysis. Together, these methods offer a comprehensive understanding of how multivariate tools support strategic decision-making across industries.

The portfolio combines technical analysis with an emphasis on clear, business-oriented communication. Each case demonstrates how multivariate methods help organizations uncover patterns, improve predictions, and design more effective strategies.

---

# 1. How the Three Methods Relate

Although each method serves a different purpose, they complement each other when applied across a full analytical lifecycle:

- Factor Analysis: identifies latent structures within complex datasets, reducing dimensionality and revealing underlying behavioral drivers.
- Discriminant Analysis transforms those insights into predictive classification models, enabling organizations to distinguish between categories of interest (e.g., high- vs low-risk customers).
- Cluster Analysis groups observations into data-driven segments based on similarity, supporting targeted strategies.

Taken together, the three methods move from exploration → prediction → segmentation, forming a complete analytical pipeline.

---

# 2. Business Questions Answered by Each Method

# Case 1: TechnoServe – Customer Satisfaction (Factor Analysis)  
Business question:
"What underlying dimensions shape customer satisfaction, and which factors most strongly influence renewal likelihood?"  
Factor analysis reduced 23 survey variables into five interpretable factors, enabling TechnoServe to understand the core drivers of satisfaction and prioritize improvements in technical capabilities, communication, and support.  


# Case 2: LendSmart – Credit Risk Classification (Discriminant Analysis)  
Business question:  
"How can loan applicants be classified reliably into groups based on their likelihood of default?"  
Discriminant Analysis built predictive models (LDA and QDA) to classify applicants using financial and behavioral indicators. LDA provided the strongest performance and interpretability, supporting more consistent lending decisions.  


# Case 3: MegaMart – Customer Segmentation (Cluster Analysis)  
Business question:  
What natural customer segments exist within MegaMart’s shopper base, and how can they be targeted more effectively?  
Cluster Analysis identified four distinct segments based on purchase behavior, engagement, and value. These insights support personalized marketing and more efficient budget allocation.  


## 3. When to Use Each Multivariate Technique

| Method | Ideal Use Case | Data Requirement | Business Purpose |
|--------|----------------|------------------|------------------|
| Factor Analysis:  When many variables need to be simplified into core dimensions | Continuous variables | Reduce dimensionality; uncover latent constructs |
| Discriminant Analysis: When the goal is to classify observations into predefined categories | Categorical outcome + predictors | Predictive modeling and decision automation |
| Cluster Analysis: When natural segments or groups must be discovered | Mainly continuous variables | Customer segmentation; behavioral grouping |

Across business contexts, the three methods fill different but complementary roles, often forming a full end-to-end data science workflow.


## 4. Conceptual Map of Method Relationships


                ┌──────────────────────────────┐
                │      Exploratory Stage        │
                │      (Unsupervised)           │
                └──────────────┬───────────────┘
                               │
                     Factor Analysis
                               │
                               ▼
                Reduces variables into factors
                               │
                               ▼
       ┌─────────────────────────────────────────┐
       │        Modeling & Prediction Stage      │
       │              (Supervised)               │
       └──────────────────┬──────────────────────┘
                          │
                 Discriminant Analysis
                          │
          Classifies observations into categories
                          │
                          ▼
       ┌─────────────────────────────────────────┐
       │       Segmentation & Strategy Stage     │
       │            (Unsupervised)               │
       └──────────────────┬──────────────────────┘
                          │
                   Cluster Analysis
                          │
          Identifies groups for targeted action
