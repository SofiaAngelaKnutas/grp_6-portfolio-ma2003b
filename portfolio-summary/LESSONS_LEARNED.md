
---
# LESSONS LEARNED 

This document summarizes the technical, analytical, and professional lessons learned during the development of the three multivariate business cases in this portfolio. The reflection highlights challenges faced, how they were addressed, and how the experience supports future applications of multivariate analysis.


# 1. Technical Challenges and How We Addressed Them

# 1.1 Managing High-Dimensional Data
In the TechnoServe case, working with 23 satisfaction variables required careful preprocessing, ensuring each metric contributed consistently to the factor extraction process. Key challenges included:
- Standardizing variables using `StandardScaler`
- Assessing dataset suitability through KMO and Bartlett’s tests  
- Comparing rotation methods (Varimax vs Promax)

Addressing these steps deepened our understanding of dimensionality reduction and model interpretability.


# 1.2 Building Reliable Classification Models
The LendSmart case required balancing predictive accuracy with interpretability. We learned:
- The importance of stratified sampling in train–test splits  
- The impact of covariance assumptions when selecting between LDA and QDA  
- How to evaluate classification models using confusion matrices, ROC curves, and precision-recall metrics

Choosing LDA as the recommended model helped reinforce the real-world benefit of simpler, more interpretable statistical techniques.


# 1.3 Constructing Meaningful Clusters
For MegaMart, determining the optimal number of clusters posed a practical challenge. We learned to:
- Compare different values of k using both statistical measures and business interpretability  
- Evaluate cluster cohesion and separation  
- Translate statistical patterns into actionable segments

This experience improved our ability to balance quantitative rigor with practical business value.


## 2. Interpretation Challenges and Growth

# 2.1 Translating Statistics into Business Insights
Across all three cases, a recurring challenge was moving from numbers to narrative. We strengthened our ability to:
- Frame statistical outputs within business questions  
- Prioritize insights that matter to stakeholders  
- Communicate results using visuals and concise explanations

This skill is essential for real-world data science roles.

# 2.2 Communicating for Non-Technical Audiences
Developing executive summaries and presentation materials helped us practice:
- Structuring messages clearly  
- Highlighting high-impact findings  
- Avoiding technical jargon when unnecessary  

The process emphasized the importance of tailoring analysis to decision-makers.

# 3. Key Learnings from the Course

Across the three cases, we developed several core competencies:

- Understanding when and why to apply each multivariate method**  
- Evaluating model assumptions and ensuring methodological validity**  
- Building reproducible notebooks with clean code, explanations, and consistent structure**  
- Applying a consulting-style approach to deliver insights with clarity and business relevance**  

---

## 4. Future Applications

The tools and methods applied in this portfolio have strong relevance for careers in:

- Data science  
- Marketing analytics  
- Financial risk management  
- Customer experience strategy  
- Consulting and business intelligence  

We now feel confident in applying multivariate methods to new datasets and business problems, and in presenting these findings effectively to both technical and non-technical audiences.

