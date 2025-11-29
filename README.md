# hr_recruitment_efficiency

End-to-end HR Recruitment Efficiency Data Science project. Includes data cleaning, feature engineering, exploratory analysis, and modeling (regression + classification) to optimize recruitment time, cost, and acceptance rate.

---

# HR Recruitment Efficiency — Data Science Final Project

This project analyzes the efficiency of the recruitment process using an HR dataset containing key metrics such as time_to_hire, cost_per_hire, num_applicants, and offer_acceptance_rate.  
The goal is to identify slow or high-cost stages in the hiring pipeline and provide data-driven recommendations.

---

## Business Goals
- Reduce average time-to-hire (~47 days → target 38 days)  
- Reduce cost per hire (~$5,214 → target $4,430)  
- Increase acceptance rate (65% → target ≥90%)

---

## Dataset Overview
Main variables:
- department  
- job_title  
- num_applicants  
- time_to_hire_days  
- cost_per_hire  
- source  
- offer_acceptance_rate  

---

## Data Preparation
Key steps:
- Handling missing values  
- Standardizing data formats  
- Feature engineering (efficiency metrics, ratios, flags, indexing)  
- Log transformations for regression  
- Creating classification targets (efficiency label, high acceptance label)

---


---

## Modeling
- Regression models for predicting time-to-hire and cost-per-hire  
- Classification models for recruitment efficiency and acceptance probability  
- Evaluation using RMSE, MAE, accuracy, precision, recall, F1-score  

---

## Key Deliverables
- Cleaned and validated dataset  
- Engineered features for HR efficiency analysis  
- Exploratory insights on bottlenecks, cost drivers, and source performance  
- Predictive & classification models  
- Data-driven recommendations to improve hiring speed, reduce cost, and increase engagement

---


## Repository Structure
├── recruitment_data.csv
├── HR_Recruitment_Efficiency.ipynb
└── README.md


## Tools
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- GitHub

## Author
Project by **NeuraLens** — Final Project Data Science Rakamin.

