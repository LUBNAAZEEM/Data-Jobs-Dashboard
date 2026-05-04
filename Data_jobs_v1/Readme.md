# 📊 Job Market Analysis Dashboard (SQL + Power BI)


![Data job DB](/Images/Image%20Db.png)

[🔗 **View the interactive dashboard on the Power BI Service**](https://app.powerbi.com/reportEmbed?reportId=b7bfb259-0bea-4aaa-89b9-b7a212f74017&autoAuth=true&ctid=fa4630b9-65b1-465d-9d71-2d6f9cb85a8b)



## 📌 Project Overview

This project analyzes job market data to uncover trends in salaries, job demand, and required skills across different roles. The goal is to provide actionable insights for job seekers and help understand current industry demands.

---

## 🎯 Objectives

* Identify high-paying roles in the data domain
* Analyze the most in-demand skills
* Compare job opportunities across locations
* Explore salary trends for different job titles

---

## 🗂️ Dataset

The dataset includes job postings with the following attributes:

* Job Title
* Salary
* Location
* Required Skills
* Employment Type

---

## 🛠️ Tools & Technologies

* **SQL** → Data extraction and transformation
* **Power BI** → Data visualization and dashboard creation
* **Excel** → Initial data exploration and cleaning

---

## 📊 Key KPIs

* Average Salary
* Total Job Count
* Top Paying Job Roles
* Most In-Demand Skills
* Jobs by Location

---

## 📈 Dashboard Features

* Interactive filters (job title, location, skills)
* Salary distribution analysis
* Job demand by role and region
* Skill frequency analysis

---

## 🔍 Key Insights

* Data Analyst roles show the highest demand across job postings
* Data Scientist roles generally offer higher average salaries
* SQL and Excel are the most frequently required skills
* Remote jobs tend to offer competitive salary ranges

---

## 💡 Business Recommendations

* Job seekers should prioritize learning SQL and data visualization tools to increase employability
* Focusing on high-demand roles like Data Analyst can improve job opportunities
* Companies can attract more candidates by offering remote flexibility and competitive salaries

---

## 🧾 Sample SQL Queries

### Top 5 Highest Paying Roles

```sql
SELECT job_title, AVG(salary) AS avg_salary
FROM jobs
GROUP BY job_title
ORDER BY avg_salary DESC
LIMIT 5;
```

### Most In-Demand Skills

```sql
SELECT skill, COUNT(*) AS demand_count
FROM job_skills
GROUP BY skill
ORDER BY demand_count DESC;
```

---

## 🚀 Conclusion

This project demonstrates how data analytics can be used to extract meaningful insights from job market data. By combining SQL and Power BI, the analysis provides valuable information for both job seekers and organizations.

---


Aspiring Data Analyst


[**View full Project details in (Readme)**](/Images/Readme.md)


---
