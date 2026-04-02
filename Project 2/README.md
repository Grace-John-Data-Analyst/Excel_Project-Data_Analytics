# Project 2 - Data Jobs Analysis
## Introduction

There are lots of information surrounding the data science market but not much is being said about what skills top employers request and how to leverage these skills for better pay.

## Questions Explored
To understand the data science job market, I asked the following:  

Do more skills get you better pay?  
What’s the salary for data jobs in different regions?  
What are the top skills of data professionals?  
What’s the pay for the top 10 skills?  

## Excel Skills Used  
The following Excel skills were utilized for analysis:  

📊 Pivot Tables  
📈 Pivot Charts  
🧮 DAX (Data Analysis Expressions)  
🔍 Power Query  
💪 Power Pivot  

## Data Jobs Dataset
The dataset used is from Luke Barousse as part of the resources for his Data Analytics Course and it contains real-world data science job information from 2023.

It includes detailed information on:

👨‍💼 Job titles  
💰 Salaries  
📍 Locations  
🛠️ Skills  


# 1️⃣ Do more skills get you better pay?
## 🔍 Skill: Power Query (ETL)
### 📥 Extract
I started by extracting the original dataset (data_salary_all.xlsx) into power query editor then proceeded to transform same by removing unecessary columns, changing column types, and cleaning the the texts to remove specific words, and trimming white spaces.

Data_jobs_all  

 
![Power query Applied steps](https://github.com/user-attachments/assets/c80fd85c-976f-4a10-9bba-eabc355d129f)

I then created a second query specifically for the job IDs and associated skills for easy analysis.  

Data_job_skills  

 
![Data Job Skills Ordered steps](https://github.com/user-attachments/assets/a666549e-a8ef-4ca3-b97c-e285940adb9f)

Loading the Data  

After cleaning, I proceeded to load my data into a workbook, getting ready for my analysis.  


Data_jobs_all  

![Data Jobs Salary Table](https://github.com/user-attachments/assets/f00ff26c-0114-4f42-adf6-7c27ba90cd9c)

Data_job_skills  

![Power Query Data_Jobs_skill](https://github.com/user-attachments/assets/b516ea6b-a114-4106-9590-6fe1555ba609)

# Analysis  

##  Insights  

Results show that roles like Data Engineers and Data Scientists require more skills and offers higher pay when compared to roles like Business Analyst which requiers fewer skills.

![Scatter chart - project 2](https://github.com/user-attachments/assets/7fae6f22-9321-40a1-8b36-505f9c6b91dd)

## Recommendations  

Job seekers aiming for higher pay should consider acquiring more skills.  

# 2. What’s the salary for data jobs in different regions?
## 🧮 Skills: PivotTables & DAX
### 📈Pivot Table

I created a pivote table using the data model I created with Power pivot  
Next, I dragged the Job Titles Short ino the roles and salary year average into the value. Then I created a messure a measure to calculate the median salary in the US.   

# Analysis  
## 💡 Insights 
- Roles like Data engineer recieve hiher pay both i the US and internationally, showig the demand for higher tech expertise globally.

![Salary analysis - project 2](https://github.com/user-attachments/assets/3a213b4c-e1b9-426b-ac5b-dbb92cbaed23)


### Impotance

These Salary analysis will help professionals in negotiating salary appropriately with respect to skills and regions.

# 3️⃣ What are the top skills of data professionals?  
## 🔧 Skill: Power Pivot 
### 💪 Power Pivot 

![Power Pivot Relationship Table](https://github.com/user-attachments/assets/bd7d79a0-7fa9-41cd-ad4a-92658258ffc7)


![Power Pivot Table](https://github.com/user-attachments/assets/c6d4930d-aa61-4776-8a00-cf7fe481a9b3)


![Project 2 Chart](https://github.com/user-attachments/assets/65099cd0-2daa-4572-8dea-caccc74b183c)


![Data Jobs Chart](https://github.com/user-attachments/assets/05d95eef-3fdc-43e8-89c4-3a3667b9c49d)
