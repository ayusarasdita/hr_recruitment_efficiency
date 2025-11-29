# hr_recruitment_efficiency
End-to-end HR Recruitment Efficiency Data Science project. Includes data cleaning, feature engineering, exploratory analysis, and modeling (regression + classification) to optimize recruitment time, cost, and acceptance rate.

# HR Recruitment Efficiency — Data Science Final Project

Project ini menganalisis efisiensi proses rekrutmen menggunakan dataset HR yang berisi metrik seperti time_to_hire, cost_per_hire, num_applicants, dan acceptance_rate. Tujuannya adalah mengidentifikasi area proses rekrutmen yang lambat/mahal dan memberikan rekomendasi berbasis data.

## Business Goals
- Mengurangi average time-to-hire (~47 hari → target 38 hari)
- Menurunkan cost per hire (~$5,214 → target $4,430)
- Meningkatkan acceptance rate (65% → target ≥90%)

## Dataset Overview
Variabel utama:
- department  
- job_title  
- num_applicants  
- time_to_hire_days  
- cost_per_hire  
- source  
- offer_acceptance_rate  

## Data Preparation
Tahapan utama:
- Handling missing values  
- Standarisasi format data  
- Feature engineering (efficiency metrics, ratios, flags, indexing)  
- Exploratory analysis untuk melihat pola per department & sumber rekrutmen

## Key Insights
- Beberapa department memiliki time-to-hire jauh lebih tinggi dari rata-rata.  
- Sumber rekrutmen tertentu menghasilkan acceptance rate tinggi dengan cost yang lebih rendah.  
- Terdapat korelasi negatif antara jumlah pelamar dan durasi rekrutmen.

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

