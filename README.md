# Final Portfolio — MA2003B: Application of Multivariate Methods in Data Science
This repository contains the portfolio for the course MA2003B – Application of Multivariate Methods in Data Science (MA2003B). 
It includes the three multivariate analysis case studies developed during the course: Factor Analysis, Discriminant Analysis, and Cluster Analysis, along with documentation, reports, notebooks, and visualizations.

---

## Team

| Member | Student ID | 
|--------|-------------|
| Sofia Knutas | A01831481 | 
| Kristina Kristiansen Stapnes | A01830792|

---

## Table of Contents

- [Final Portfolio — MA2003B](#final-portfolio--ma2003b-application-of-multivariate-methods-in-data-science)
- [Team](#team)
- [Repository Structure](#repository-structure)
- [Summary of Case Studies](#summary-of-case-studies)
- [Reproducibility](#reproducibility)
- [Tools Used](#tools-used)
- [License](#license)

---
## Repository Structure
mi-portfolio-ma2003b/
│
├── README.md                     # Main portfolio overview
├── LICENSE                       # MIT License
├── .gitignore
├── requirements.txt              # Project dependencies
│
├── case-01-factor-analysis/
│   ├── README.md
│   ├── data/
│   │   ├── customer_satisfaction_data.csv
│   │   └── DATA_DICTIONARY.md
│   ├── notebooks/
│   │   └── factor_analysis.ipynb
│   ├── reports/
│   │   ├── executive_summary.pdf
│   │   └── technical_report.pdf
│   ├── src/
│   │   └── utils.py
│   └── visualizations/
│       ├── correlation_heatmap.png
│       ├── scree_plot.png
│       └── factor_loadings.png
│
├── case-02-discriminant-analysis/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── reports/
│   └── visualizations/
│
├── case-03-cluster-analysis/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── reports/
│   └── visualizations/
│
├── portfolio-summary/
│   ├── PORTFOLIO_OVERVIEW.md
│   ├── LESSONS_LEARNED.md
│   └── METHODOLOGY_COMPARISON.md
│
└── presentation/
    └── final_portfolio_presentation.pdf

---

## Summary of Case Studies

| Case | Method | Business Question | Key Finding | Link |
|------|---------|------------------|-------------|-------|
| TechnoServe Customer Satisfaction | Factor Analysis | What latent dimensions explain customer satisfaction? | Five factors explain ~67% of variance; “Technical Excellence” is the strongest driver. | [View Case](case-01-factor-analysis/) |
| LendSmart Credit Risk | Discriminant Analysis | How can applicants be classified into risk categories? | Model achieves ~85% accuracy; income and credit history are key predictors. | [View Case](case-02-discriminant-analysis/) |
| ShopSmart Customer Segmentation | Cluster Analysis | What natural customer segments exist? | Five clusters identified; “High-Value Loyalists” make up 18% but generate 45% of revenue. | [View Case](case-03-cluster-analysis/) |

---

## Reproducibility

### Requirements

- Python 3.10 or later  
- Jupyter Notebook or Jupyter Lab  

### Install dependencies

```bash
pip install -r requirements.txt



---

## Tools Used

This project was developed using:

- Visual Studio Code  
- Git and GitHub for version control  
- Jupyter Notebook (via Anaconda)  

---

## License

This repository is licensed under the MIT License. See the `LICENSE` file for full details.

---