# HR Employee Attrition Insights Dashboard
Project Overview
Employee turnover costs organizations time, money, and productivity. This project features an interactive Power BI Dashboard built to analyze historical HR data, uncover the root causes of employee attrition, and deliver data-driven insights to executive stakeholders.

Following the visualization in image_769996.jpg, the dashboard is designed around a Data Storytelling Framework that systematically answers four critical business questions:

What Happened? (Descriptive Analytics)

Where did the Drop Happen? (Diagnostic Analytics)

Why did Attrition Rise? (Root Cause Analysis)

What can we do next? (Prescriptive Analytics)

Key Business Metrics (KPIs)
The dashboard monitors the health of workforce retention through primary high-level metrics:

Total Workforce: 1K+ Employees

Total Attrition: 416 Employees

Overall Attrition Rate: 28.30% (A significant spike was identified in June, primarily driven by core technical and sales roles).

Deep-Dive Analysis & Features
1. Descriptive: What Happened?
Departmental Impact: Measures the exact count of employees leaving across different sectors, pinpointing where the immediate volume of turnover is highest.

2. Diagnostic: Where did the Drop Happen?
Risk Matrix (Job vs. Environment Satisfaction): A cross-tabulated heat map that maps employee Job Satisfaction against Environment Satisfaction. It visually highlights that low satisfaction scores directly correlate with critical attrition spikes.

Department-Wise Share: A donut chart illustrating that the Research & Development (R&D) department bears the highest attrition burden at 65.14%, followed by Sales at 30.77%.

3. Root Cause: Why did Attrition Rise?
Top Risk Job Roles: A horizontal bar chart identifying that Research Scientists, Sales Executives, and Laboratory Technicians are the most vulnerable roles in the organization.

Demographic Breakdown: A clustered column chart evaluating Attrition Rate (%) by Marital Status and Gender, showing that Single employees exhibit higher turnover tendencies compared to married or divorced peers.

4. Prescriptive: Actionable Recommendations
The dashboard concludes with a dedicated executive summary section to drive HR policy changes:

Target High-Risk Roles: Review compensation, clear career progression paths, and balance workloads for Laboratory Technicians and Research Scientists.

Workplace Environment: Launch pulse surveys and targeted check-ins for teams reporting low environment satisfaction.

Early-Career Engagement: Develop tailored retention strategies focusing on the Single and younger demographic segments to stabilize headcount.

Technical Implementation & Tech Stack
Data Source: HR Employee Attrition Dataset (CSV/Excel).

Power Query (ETL): Handled data cleaning, removing duplicates, replacing null values, and creating conditional columns for satisfaction mapping.

Data Modeling: Established a clean star schema with dedicated dimension tables and a centralized fact table.

DAX Formulas: Developed custom measures for dynamic reporting, including:

Attrition Count = CALCULATE(COUNT(Employee[Attrition]), Employee[Attrition] = "Yes")

Attrition Rate = DIVIDE([Attrition Count], COUNT(Employee[EmployeeID]), 0)

How to Run the Project
https://github.com/Ms-Noor409/HR_Employee_Attrition_Dashboard.git


2. Download and install [Power BI Desktop](https://powerbi.microsoft.com/).
3. Open the .pbix file included in this repository.
4. Interact with the dashboard using the slicers for **Department**, **Gender**, and **Marital Status**.

# Thank You !
