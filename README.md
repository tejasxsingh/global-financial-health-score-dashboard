
# 📊Global Financial Health Score (FHS) Dashboard  

This project was built for the **Tableau Next Hackathon**.  
It introduces a **Financial Health Score (FHS)** that combines World Bank indicators on consumption, savings, and credit to measure the financial wellness of countries over time.  


##  Project Overview  
- **Data Source:** World Bank Open Data  
- **Technologies:** Python (pandas), Tableau Next (Salesforce), GitHub  
- **Goal:** Create a Financial Health Score to help visualize and compare the financial resilience of countries globally.  
- **Outcome:** An interactive Tableau dashboard hosted in Salesforce, with insights into country-level financial health trends from 2000–2023.  


## 📂 Repository Structure  
```
financial-health-score-dashboard/
├── data/ # Raw World Bank datasets (CSV)
├── notebooks/ # Jupyter notebooks for cleaning & merging data
│ └── data_prep.ipynb
├── output/ # Final cleaned dataset (financial_health_score.csv)
├── README.md # Project documentation
└── LICENSE # MIT license
```

##  How to Run Locally  

1. Clone this repo:  
   ```bash
   git clone https://github.com/tejasxsingh/global-financial-health-score-dashboard.git
   cd financial-health-score-dashboard

Install Required Libraries:

pip install pandas matplotlib

Jupyter notebook:

jupyter notebook notebooks/data_prep.ipynb

Run all cells to generate:

output/financial_health_score.csv

---

##  Dashboard  

The interactive dashboard is hosted inside **Tableau Next on Salesforce**.  
 *[Link will be added after deployment]*

##  Demo Video  

 *[Link to Demo Video will be added here]*  

##  Financial Health Score Formula  

We defined the Financial Health Score (FHS) as:  

\[
FHS = 100 - (0.4 \cdot \text{Consumption}) - (0.3 \cdot \text{Credit}) + (0.3 \cdot \text{Savings})
\]  

- Higher FHS → Stronger financial health (balanced spending, controlled credit, high savings).  
- Lower FHS → At-risk economies (high consumption/credit, low savings).  

##  Team  

This project was developed as part of the Tableau Next Hackathon.  

- **Tejas Singh** — *Project Lead*  
  - Designed the Financial Health Score metric.  
  - Led data preparation, Python coding, Tableau dashboard building, and Salesforce integration.  
- **Raghumani Mehta** — *Contributor* (Add role here).  
- **Dishika Taneja** — *Contributor* (Add role here).

##  License  

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

##  Acknowledgements  

- World Bank Open Data for providing public financial datasets.  
- Tableau & Salesforce for enabling cloud-based analytics.  
- Hackathon organizers for the opportunity to build and showcase this project.


  






