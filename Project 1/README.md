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
         (AI_Jobs!C2:C90001=Jobs!A2)*  
         (AI_Jobs!G2:G90001<>0)*  
         (AI_Jobs!B2:B90001=Country)*  
         (AI_Jobs!N2:N90001=mode),  
          AI_Jobs!G2:G90001  
)  
)  



🔍 Multi-Criteria Filtering: Checks job title, country, schedule type, and excludes blank salaries.   
📊 Array Formula: Utilizes MEDIAN() function with nested IF() statement to analyze an array.  
🎯 Tailored Insights: Provides specific salary information for job titles, regions, and schedule types.  
🔢 Formula Purpose: This formula populates the table below, returning the median salary based on job title, country,   and type specified.


🍽️ Background Table


![Job Title Short + Median Salary](https://github.com/user-attachments/assets/076889dc-dce5-4a4e-9f2e-62acbe4df83d)

📉 Dashboard Implementation:


![Data Jobs Chart + KPI](https://github.com/user-attachments/assets/2b695172-3cc1-4759-b2b3-39ad34424295)

🍽️ Background Table

![Job Mode Sorted](https://github.com/user-attachments/assets/95fbfd5e-e68a-45bb-ad88-ed0750d51461)

📉 Dashboard Implementation:

![Data jobs mode](https://github.com/user-attachments/assets/e8bdfdaf-4a11-4cf4-8038-c362299a838b)


❎ Data Validation
🔍 Filtered List


- 🔒 Enhanced Data Validation: Implementing the filtered list as a data validation rule under the Job Title, Country, and Type option in the Data tab ensures:
- 🎯 User input is restricted to predefined, validated schedule types
- 🚫 Incorrect or inconsistent entries are prevented
- 👥 Overall usability of the dashboard is enhanced


![Data Job Title Short gif](https://github.com/user-attachments/assets/b0d3aa22-07ab-44c4-a208-2b76c235fcf4)


# Conclusion

I created this dashboard to showcase insights into salary trends across various data-related job titles. Utilizing data from my Excel course, this dashboard allows users to make informed decisions about their career paths. Exploring the functionalities to understand how location and job type influence salaries.
