HR Attrition Analytics - Power BI Project

📌 Project Overview
This project provides a comprehensive analysis of employee attrition to identify key factors contributing to turnover within an organization. By leveraging Power BI, I transformed raw HR data into an interactive dashboard that offers actionable insights into workforce demographics, job satisfaction, and performance metrics, enabling HR teams to develop data-driven retention strategies.

🛠️ Tech Stack & Tools
Power BI Desktop: Data Visualization, Dashboarding, and Report Generation.

Power Query: Data Extraction, Transformation, and Loading (ETL).

DAX (Data Analysis Expressions): Creating complex measures and calculated columns.

Microsoft Excel: Initial data source.

🔍 Key Steps in the Project
1. Data Cleaning & Transformation (Power Query)
ETL Process: Imported raw CSV/Excel data into Power BI.

Data Sanitization: Handled missing values, removed duplicates, and corrected data types.

Feature Engineering: Created custom columns for "Age Groups" (e.g., 18-25, 26-35) and "Tenure Buckets" to allow for better segmentation.

2. Data Modeling
Implemented a Star Schema to optimize report performance.

Established relationships between the main employee table and secondary dimension tables.

3. DAX Calculations
Developed essential KPIs to track workforce health:

Attrition Rate: DIVIDE(COUNTROWS(FILTER(Emp, Emp[Attrition]="Yes")), COUNTROWS(Emp))

Average Tenure: AVERAGE(Emp[YearsAtCompany])

Satisfaction Index: Calculated average ratings across Environment, Job, and Relationship satisfaction.

💡 Key Insights & Findings
Attrition Rate: The overall attrition rate stands at [X.X]%.

Critical Age Group: Employees in the [e.g., 26-35] age group show the highest turnover, often linked to salary growth opportunities.

Departmental Trends: The [e.g., Sales] department accounts for the highest percentage of departures.

Retention Drivers: High correlation found between "Frequent Business Travel" and increased attrition.

Income Factor: Employees with a monthly income below [e.g., $5,000] are [X] times more likely to leave the company.

🚀 Recommended Actions
Targeted Retention: Focus on the [Department Name] team with personalized growth plans.

Work-Life Balance: Review policies for roles requiring "Frequent Travel" to mitigate burnout.

Competitive Pay: Adjust salary benchmarks for entry-level roles where attrition is peak.

📂 How to View this Project
Download the Power BI Project - HR ATTRITION ANALYTICS.pbix file from this repository.

Open it using Power BI Desktop.

Interact with the slicers (Department, Gender, Education) to explore the data dynamically.
