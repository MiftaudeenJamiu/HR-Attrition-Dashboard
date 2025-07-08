# Employee-Attrition-Dashboard

## Table of Contents 
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data analysis](data-analysis)
- [Visualisations and report](Visualisation-and-reports)
- [Results and Findings](#results-and-findings)
- [Conclusions](#conclusions)


### Project Overview
This project focuses on analyzing employee attrition to help the HR department identify patterns and risk factors associated with staff turnover. The Power BI dashboard visualizes key metrics that highlight which employee groups are more likely to leave and supports data-driven retention strategies.

### Data Sources
The dataset was taken from Kaggle and includes employee-level data such as age, job role, tenure, job satisfaction, commute distance, and attrition status. Its structure supports targeted analysis of which factors are linked to employee turnover.

### Tools
- Excel: Data Cleaning
- PowerBi: Data Analysis and Visualisation

### Data Cleaning
The raw dataset from Kaggle was cleaned in Power BI using Power Query before creating visualizations. The following steps were applied:
- Data Types: Converted data types for key fields such as age, distance from home, and date fields to ensure accurate analysis.
- Handling Missing Values: Removed records with null values in critical columns to maintain data integrity.
- Feature Creation: Created a new column to group job satisfaction scores into categories (e.g., Satisfied, Very Satisfied, Unsatisfied, Very Unsatisfied).
Added a descriptive column that classifies commute distance using conditional logic (e.g., “Nearby,” “Far", “Very far”).
- Standardization: Standardized text formats and ensured consistency in categorical fields such as Job Role and Attrition status.


### ExPloratory Data Analysis
This stage focused on identifying measurable patterns linked to employee attrition. The analysis answered the following:
- Which groups have the highest attrition? Breakdown by gender, marital status, and age band.
- Which job roles and tenure lengths show the most exits? Attrition rates by role and years at the company.
- Is commute distance a contributing factor? Attrition by distance from home.
- What do workforce-level metrics show? Total employees, active staff, attrition count and rate, average age, and average years in the company.
- Can we examine individual records? A drill-through page displays details of each employee who left, including age, role, satisfaction score, and other key fields.

The goal was to surface specific trends that help HR target areas with high turnover and understand contributing factors.

### Data Analysis
As part of the data analysis process to develop the Power BI dashboard, several calculated measures and categorical breakdowns were created to identify key drivers of employee attrition and present workforce trends clearly:

- Attrition Rate: Calculated as the percentage of employees who left the company over the total employee count. This metric tracks overall turnover and serves as a benchmark for workforce stability.
- Total Attrition: Created a categorical column that groups employees by age ranges (e.g., 18–25, 26–35, 36–45, etc.) to reveal how attrition varies by career stage.
- Years at Company Band: Segmented employees by tenure groups (e.g., 0–2 years, 3–5 years, 6–10 years, 10+ years) to analyze how long-term retention relates to attrition risk.
- Demographic Analysis: Breakdowns were created to compare attrition by gender and marital status. These views help determine if personal characteristics correlate with turnover trends.
- Role-Based Analysis: Visuals highlight attrition by job role, allowing HR to detect specific departments or positions with high exit rates.
-  Distance from Home: Used this field to analyze the relationship between commute distance and employee exits, identifying possible geographic or travel-related retention issues.
-  Job Satisfaction Category: Created a new column grouping satisfaction scores into categories (e.g., Low, Medium, High) to explore the link between internal engagement and attrition.
-  Employee-Level Drill-through: A detailed table allows HR to explore individual employee records, showing key attributes such as job role, age, satisfaction score, distance to work, and attrition status. This enables closer inspection of cases for HR review or case tracking.
  

