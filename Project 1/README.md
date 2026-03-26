# Global AI Jobs Dashboard

![DataJobsDashboar gif](https://github.com/user-attachments/assets/b6d4f010-b71d-4951-8fcb-7e09557bc6c6)





## Overview
In this project, I utilized various Excel tools to analyze AI & Data Science jobs posted in different locations. The goal was to investigate salaries associated with these jobs to ensure job seekers are adequately compensated for their desired roles.

## Dashboard File
My Final Dashboard is in (./Project%201/Global_AI_Jobs_Dashboard Project 1.xlsx).


Excel Skills Used
The following Excel skills were utilized for analysis:

- 📊charts: Charts  
- 🧮 Formulas and Functions  
- ✅ Data Validation  


Data Jobs Dataset
The dataset used for this project contains real-world AI & data science job information from 2026. The data set was extracted from Kaggle.com. It includes detailed information on:

- 👤 Job titles  
- 💰 Salaries  
- 📍 Locations  
- ⚙️ Job Modes 

## Dashboard Build
## Charts

## 📊 Data Science Job Salaries - Bar Chart

![Data Jobs Chart](https://github.com/user-attachments/assets/ad897c09-e8be-41ca-9e56-31779267b103)

📊 Excel Features: Bar chart 
💡 Insights Gained: This enables quick identification of salary trends, noting that Senior roles and Engineers are higher-paying than Analyst roles.


🗺️ Country Median Salaries - Map Chart



![DataJobsMap gif](https://github.com/user-attachments/assets/eb26f773-26b5-4757-8f9a-a11267d67155)



🛠️ Excel Features: Utilized Excel's map chart feature to plot median salaries globally.
🎨 Design Choice: Color-coded map to visually differentiate salary levels across regions.
📊 Data Representation: Plotted median salary for each country with available data.
👁️ Visual Enhancement: Improved readability and immediate understanding of geographic salary trends.
💡 Insights Gained: Enables quick grasp of global salary disparities and highlights high/low salary regions.



=MEDIAN(  
IF(  
    (jobs[job_title_short]=A2)*  
    (jobs[job_country]=country)*  
    (ISNUMBER(SEARCH(type,jobs[job_schedule_type])))*  
    (jobs[salary_year_avg]<>0),  
    jobs[salary_year_avg]  
)  
)  



🔍 Multi-Criteria Filtering: Checks job title, country, schedule type, and excludes blank salaries.
📊 Array Formula: Utilizes MEDIAN() function with nested IF() statement to analyze an array.
🎯 Tailored Insights: Provides specific salary information for job titles, regions, and schedule types.
🔢 Formula Purpose: This formula populates the table below, returning the median salary based on job title, country, and type specified.



![Job Title Short + Median Salary](https://github.com/user-attachments/assets/d9f6b477-0f15-4274-b276-93c9d8e252a0)


📉 Dashboard Implementation

