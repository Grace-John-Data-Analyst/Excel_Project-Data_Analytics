# Global AI Jobs Dashboard



![AI   data salary dashboard gif](https://github.com/user-attachments/assets/67af97c0-a840-4a36-beab-5d93625d8ac2)




## Overview
This project analyzes global AI & Data Science job postings to identify which roles, locations, and work mode offer the highest salary, helping job seekers make informed career decisions.

## 📁 Dashboard File
Access the full analysis here: [Final Excel Dashboard](./Global_AI_Jobs_Dashboard%Project%201.xlsx)



🛠️Technical Skills


- 📊 Visualization: Dynamic Charts & Formatting  
- 🧮 Analysis: Advanced Formulas & Functions  
- ✅ Data Validation
    

Data Jobs Dataset

This project utilized a 2026 AI & Data Science job dataset sourced from Kaggle. It includes detailed information on:

- 👤 Job titles  
- 💰 Salaries  
- 📍 Locations  
- ⚙️ Job Modes 

## 📊 Visualization & Insights


## Job Salaries by Role (Bar Chart)

![Data Job Titles](https://github.com/user-attachments/assets/b3be12ff-b11f-441c-8915-e13986d16aa5)


- 📊 Visualized salary difference across AI roles to highligh top-paying career paths.
- 💡 Insights Gained: Research scientists and Machine Learning roles consistently offer the highest salaries, indicating strong market demand for advanced AI skills.


## Recommendation
- Job seekers should prioritize ML and Research roles for higher earning potentials.
- Target countries like USA and Australia for better compensation.
  
## 🗺️ Country Median Salaries - Map Chart



![DataJobsMap gif](https://github.com/user-attachments/assets/eb26f773-26b5-4757-8f9a-a11267d67155)



- 🛠️ Features: Excel Map Charts
- 💡 Insigts: Visualized median salary benchmarks across different countries to highlight regional market variations.

### Formulas  
- Used dynamic array formulas for salary calculations 
- Created dynamic charts based on user selections 

=MEDIAN(  
       IF(  
         (AI_Jobs!C2:C90001=Jobs!A2)*  
         (AI_Jobs!G2:G90001<>0)*  
         (AI_Jobs!B2:B90001=Country)*  
         (AI_Jobs!N2:N90001=mode),  
          AI_Jobs!G2:G90001  
)  
)  


Importance

- Dynamic Filtering: Automatically updates based on job Title, Country, and Work Mode.

- Data Accuracy: Excludes blank entries to ensure insight remains reliable


🍽️ Background Table


![Job Title Short + Median Salary](https://github.com/user-attachments/assets/076889dc-dce5-4a4e-9f2e-62acbe4df83d)

📉 Dashboard Implementation:


![Data Jobs Chart + KPI](https://github.com/user-attachments/assets/2b695172-3cc1-4759-b2b3-39ad34424295)

🍽️ Background Table

![Job Mode Sorted](https://github.com/user-attachments/assets/95fbfd5e-e68a-45bb-ad88-ed0750d51461)

📉 Dashboard Implementation:

![Data jobs mode](https://github.com/user-attachments/assets/e8bdfdaf-4a11-4cf4-8038-c362299a838b)


❎ Data Validation & Filtering


Implemented Data Validation to restrict inputs for job Title, Country, and Job Mode.


![Data Job Title Short gif](https://github.com/user-attachments/assets/b0d3aa22-07ab-44c4-a208-2b76c235fcf4)

## Key Findings  
- AI roles like Research Scientist and ML Engineer earn the highest salaries
- USA and Austrialia offer the strongest compensation
- Work mode impacts salary, with onsite roles often paying more
# Conclusion

I created this dashboard to provide a clear look into global AI & Data Science Salary trends. By visualizing how location and job type affect pay, it helps job seekers to make data-driven career decision.
