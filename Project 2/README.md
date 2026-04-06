# Project 2 - Data Jobs Analysis
## Introduction

This project analyzes the data science job market to identify high-demand skills and their direct impact on earning potentials. The goal is to guide job seekers to understand how skills correlate to pay and how to negotiate approriately, with respect to location.

## Questions Explored
To understand the data science job market, I asked the following:  

1️⃣ Do more skills get you better pay?  
2️⃣ What’s the salary for data jobs in different regions?  
3️⃣ What are the top skills of data professionals?  
4️⃣ What’s the pay for the top 10 skills?  

## Excel Skills Used  
The following Excel skills were utilized for analysis:  

📊 Pivot Tables  
📈 Pivot Charts  
🧮 DAX (Data Analysis Expressions)  
🔍 Power Query  
💪 Power Pivot  

## Data Jobs Dataset
Sourced from Luke Barousse's 2023 course materials, featuring real-world data.  

It includes detailed information on:  

👨‍💼 Job titles  
💰 Salaries  
📍 Locations  
🛠️ Skills  


# 1️⃣ Do more skills get you better pay?
## 🔍 Skill: Power Query (ETL)
### 📥 Extract
I started by extracting the original dataset (data_salary_all.xlsx) into power query then proceeded to remove unnecessary columns, changed column types, and cleaned the texts to remove specific words, and trimmed white spaces.

Data_jobs_all  

 
![Power query Applied steps](https://github.com/user-attachments/assets/c80fd85c-976f-4a10-9bba-eabc355d129f)

I then created a second query specifically for the job IDs and associated skills for easy analysis.  

Data_job_skills  

 
![Data Job Skills Ordered steps](https://github.com/user-attachments/assets/a666549e-a8ef-4ca3-b97c-e285940adb9f)

Loading the Data  

Loaded the transformed data into an Excel workbook to perform a deep-dive analysis on the data job trends.  


Data_jobs_all  

![Data Jobs Salary Table](https://github.com/user-attachments/assets/f00ff26c-0114-4f42-adf6-7c27ba90cd9c)

Data_job_skills  

![Power Query Data_Jobs_skill](https://github.com/user-attachments/assets/b516ea6b-a114-4106-9590-6fe1555ba609)

# Analysis  

##  Insights  
Data Engineers and Scientists command higher salaries due to complex skills requirements compared to Business Analyst roles.

![Scatter chart - project 2](https://github.com/user-attachments/assets/7fae6f22-9321-40a1-8b36-505f9c6b91dd)

## Recommendations  

Job seekers aiming for higher pay should priorotize high-demand technical skills.

# 2️⃣ What’s the salary for data jobs in different regions?
## 🧮 Skills: PivotTables & DAX
### 📈Pivot Table

- I created a PivotTable using the Data Model I created with Power Pivot.
- Then I added new measure to calculate the median salary for United States jobs.


# Analysis  
## 💡 Insights 
- Roles like Data engineer receive higher pay globally. This highlights the intense demand for high level tech expertise both in the US and internationally.

![Salary analysis - project 2](https://github.com/user-attachments/assets/3a213b4c-e1b9-426b-ac5b-dbb92cbaed23)


### Significance

This provides a clear roadmap for professionals to align their skill sets with current high-paying market benchmark.  

# 3️⃣ What are the top skills of data professionals?  
## 🔧 Skill: Power Pivot 
### 💪 Power Pivot 

🔗 I integrated the data_jobs_all and data_jobs_skills table into a unified model by establishing a relationship through the job_id columns. This made it seamless to create measures and perform a deep-dive analysis across multiple tables.  


![Power Pivot Relationship Table](https://github.com/user-attachments/assets/bd7d79a0-7fa9-41cd-ad4a-92658258ffc7)


## 📃 Power Pivot Menu  
The Power Pivot menu was used to refine my data model and makes it easy to create measures.  


![Power Pivot Table](https://github.com/user-attachments/assets/c6d4930d-aa61-4776-8a00-cf7fe481a9b3)

# 📊Analysis  
## 💡Insights  
This analysis reveals that SQL and Python are the most critical skills in the data market today. 


![Project 2 Chart](https://github.com/user-attachments/assets/65099cd0-2daa-4572-8dea-caccc74b183c)  


### Significance  
Their dominace reflects their foundational role in data processing and analysis; mastery of these tools  is a non-negotiable requirement for high-tier data roles. 

# 4️⃣ What’s the pay of the top 10 skills?  
## 📊 Skill: Advanced Charts (Pivot Chart)  
### 📈 PivotChart  

- I created a combo PivotChart to plot median salary and skill count from my PivotTable.  
- Primary Axis: Median Salary (as a Clustered Column)  
- Secondary Axis: Skill Count (as a Line with Markers)  
To customize the chart, I added a title axis title, removed the lines (skill count), and changed the markers to diamonds.

# 📊 Analysis  
## 💡Insights  
- 💰 High-Value skills like Python, Oracle, and SQL, command high paying jobs suggesting their critical role in the industry.  
  
![Data Jobs Chart](https://github.com/user-attachments/assets/05d95eef-3fdc-43e8-89c4-3a3667b9c49d)


## 🤔Significance  
This analysis showcase the importance of mastering specialized skills like Python and SQL. The data clearly shows that these high-value skills are non-negotiable for those looking to maximize their earning potentials in the industry.

## Conclusion  
I created this project to investigate the global data science market. By leveraging Power Query, Dax and Advanced Excel modeling, on a real-world dataset, I was able to create a link between specific data skills and high compensations.
