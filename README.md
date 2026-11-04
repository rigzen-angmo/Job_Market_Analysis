# Job Market Analysis

## Project Overview

The job market is constantly changing, making it important to understand which jobs are in demand, what skills employers require, and what salaries are offered.

This project analyzes **742 job postings** to identify job trends, salary patterns, popular industries, hiring locations, and in-demand technical skills.

## Project Objectives

- Identify the most in-demand job titles.
- Analyze salary trends across different states.
- Find industries and companies with the most job openings.
- Identify the most required technical skills.
- Compare average salaries based on educational qualifications.

## Tools Used

- **MySQL** – Data cleaning and analysis
- **Power BI** – Data visualization and dashboard creation

## Data Preparation

- Cleaned the dataset and removed an empty column.
- Checked and handled invalid values.
- Created additional columns for better analysis.
- Created a separate Skill Analysis table using Unpivot in Power Query.
- Established a one-to-many relationship between the main table and Skill Analysis table in Model View.

## Key Insights

- **742** total job postings were analyzed.
- Data Scientist was the most common job title, with **313 postings**.
- Python, Excel, and SQL were among the most in-demand skills.
- California had the highest number of job postings, with **152**.
- Biotech & Pharmaceuticals had the highest number of postings by industry, with **112**.
- The overall average salary was approximately **$101.5K**.

## Dashboard Preview

### Dashboard Overview
![Dashboard Overview](Dashboard%20Overview.png)

### Detailed Job Market Analysis
![Detailed Analysis](Detailed%20Analysis.png)

### Skill Analysis
![Skill Analysis](Skill%20Analysis.png)

### Model View
![Model View](Model%20View.png)

## Project Files

- `job.pbix` – Power BI project file
- `Job_Market_Analysis_Report.docx` – Detailed project report
- `Job Market Analysis PPT.pptx` – Project presentation
- Dashboard screenshots and Model View image

## Conclusion

This project provides insights into job market trends, salary patterns, and the skills employers are looking for. These findings can help job seekers understand market requirements and make better career decisions.
