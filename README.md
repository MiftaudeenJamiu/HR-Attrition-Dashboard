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
This project focuses on analysing employee attrition to help the HR department identify patterns and risk factors associated with staff turnover. The Power BI dashboard visualises key metrics that highlight which employee groups are more likely to leave and supports data-driven retention strategies.

### Data Sources
The dataset was obtained from Kaggle and includes employee-level data, such as age, job role, tenure, job satisfaction, commute distance, and attrition status. Its structure supports targeted analysis of the factors linked to employee turnover.


### Tools
- Excel: Data Cleaning
- Power BI: Data Analysis and Visualisation

### Data Cleaning
The raw dataset from Kaggle was cleaned in Power BI using Power Query  and Excel for a quality check before creating visualisations. The following steps were applied:
- Data Types: Converted data types for key fields such as age, distance from home, and date fields to ensure accurate analysis.
- Handling Missing Values: Removed records with null values in critical columns to maintain data integrity.
- Feature Creation: Created a new column to group job satisfaction scores into categories (e.g., Satisfied, Very Satisfied, Unsatisfied, Very Unsatisfied).
Added a descriptive column that classifies commute distance using conditional logic (e.g., “Nearby,” “Far", “Very far”).
- Standardisation: Standardised text formats and ensured consistency in categorical fields such as Job Role and Attrition status.


### Exploratory Data Analysis
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
- Years at Company Band: Segmented employees by tenure groups (e.g., 0–2 years, 3–5 years, 6–10 years, 10+ years) to analyse how long-term retention relates to attrition risk.
- Demographic Analysis: Breakdowns were created to compare attrition by gender and marital status. These views help determine if personal characteristics correlate with turnover trends.
- Role-Based Analysis: Visuals highlight attrition by job role, allowing HR to detect specific departments or positions with high exit rates.
-  Distance from Home: Used this field to analyse the relationship between commute distance and employee exits, identifying possible geographic or travel-related retention issues.
-  Job Satisfaction Category: Created a new column grouping satisfaction scores into categories (e.g., Low, Medium, High) to explore the link between internal engagement and attrition.
-  Employee-Level Drill-through: A detailed table allows HR to explore individual employee records, showing key attributes such as job role, age, satisfaction score, distance to work, and attrition status. This enables closer inspection of cases for HR review or case tracking.
  
### Visualisation and Reports
This section presents the Power BI dashboards developed to monitor employee attrition and assist the HR department in identifying workforce trends, risk factors, and retention challenges. Each visual was built to isolate patterns in turnover based on demographics, tenure, role, and commute distance.

1. Summary Cards: KPI visuals display key workforce metrics including Total Employees, Active Employees, Attrition Count, Attrition Rate, Average Age, and Average Tenure. These provide a high-level snapshot of workforce structure and turnover.
2. Attrition by Gender: Bar chart comparing attrition rates between male and female employees to detect gender-based differences in turnover.
3. Attrition by Marital Status: Visual shows how marital status relates to attrition, helping assess whether personal factors contribute to exit trends.
4. Attrition by Age Band: Categorised view of attrition across age groups (e.g., 18–25, 26–35, etc.), used to identify career stage attrition patterns.
5. Attrition by Job Role: Compares attrition rates across job functions to pinpoint roles with consistently higher exits.
6. Attrition by Years at Company: Highlights whether employees are more likely to leave early in their tenure or after long service periods.
7. Attrition by Distance from Home: Examines the impact of commute distance on employee retention, using binned distance categories.
8. Employee Details Drill-through: A detailed table report that allows HR to explore individual employee records by clicking through visuals. Fields include Opportunity ID, Reporting Date, Customer, Role, Age, Distance, Job Satisfaction, and Attrition Status — useful for case review and trend validation.

See the shots below for an overview of the fraud detection dashboard.

![Screenshot 2025-07-11 114232](https://github.com/user-attachments/assets/e0d3af3d-b332-4268-9d87-c3e78c46d61d)


### Results and Findings 
The employee attrition dashboard revealed the following:
Attrition Rate: 492 out of 2,925 employees left the company, resulting in a 16.82% attrition rate. The average age was 37, and average tenure was 11 years.
Gender: 63.41% of attrition cases were female employees, indicating higher turnover among women.
Marital Status: Single employees had the highest attrition (243), followed by married (174) and divorced (75).
Department: R&D (282) and Sales (186) saw the most exits. HR had the lowest (24).
Job Role: Laboratory Technicians (130) and Sales Executives (113) had the highest attrition by role. HR-related roles showed the least.
Tenure: 378 attrition cases were from employees with 0–10 years at the company. Few exits occurred after 30+ years.
Age Band: Most exits were from the 30–39 and 20–29 age groups.
Commute Distance: 60%+ of attrition came from employees with long commutes, suggesting distance is a factor.
Job Satisfaction: Most attrition came from those with low or very low job satisfaction.


### Conclusions
This project developed a Power BI dashboard to monitor and understand employee attrition across key demographics and job-related factors. The data revealed clear patterns:

- Higher attrition among female and single employees
- Most exits occurred in the R&D and Sales departments
- Employees with 0–10 years of tenure and aged 20–39 were most likely to leave
- Long commute distances and low job satisfaction are strongly correlated with attrition
- Specific roles, such as Laboratory Technician and Sales Executive, showed elevated exit rates

These insights help the HR team identify which employee groups are most at risk and where interventions are needed. The dashboard supports data-driven decision-making to reduce turnover and improve retention.
