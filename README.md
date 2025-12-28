HR Analytics Dashboard – Power BI
📌 Project Overview

This project focuses on HR Analytics using Power BI to analyze employee data and uncover insights related to attrition, workforce demographics, job satisfaction, and compensation.
The goal of this dashboard is to help HR teams and management understand why employees leave, identify high-risk segments, and support data-driven workforce decisions.

🗂 Dataset Information

Source: Kaggle (HR Analytics Dataset)

Type: Dummy / Public dataset

Size: ~1000 records and 13 columns

Domain: Human Resources Analytics

🎯 Business Objectives

Analyze overall employee attrition

Identify departments and job roles with high attrition

Understand the impact of job satisfaction, tenure, gender, education, and performance

Provide an interactive dashboard for quick HR decision-making

📈 Key KPIs

The following KPIs were created using DAX measures in Power BI:

Total Employees

Attrition Count

Attrition Rate

Average Salary

Average Age

📊 Dashboard Visualizations

The dashboard includes multiple visuals for deep analysis:

Donut Chart: Attrition by Years at Company (Tenure)

Funnel Chart: Attrition by Job Satisfaction Level

Stacked Bar Chart: Attrition Rate by Job Role

Clustered Bar Chart: Attrition by Gender and Department

Table: Attrition by Education Qualification

Pie Chart: Attrition by Performance Rating

Top 5 Employees Table: Highest Monthly Salary

Drill-through Page: Employee → Department & Job Role details

Slicer: Department-wise filtering for interactive analysis

🧩 Data Modeling

To improve analysis and visualization clarity, two supporting tables were created:

Education Table

Used to provide a proper hierarchical order for education levels (e.g., Bachelor → Master → Doctorate)

Years at Company Table

Used to group employee tenure into consecutive ranges

Ensures correct sorting and logical trend analysis in visuals

These tables helped avoid unordered or misleading visual outputs.

🔍 Key Insights

Female employees are more in number than male employees

Attrition is higher among male employees

The HR department shows the highest attrition

Job dissatisfaction is a major reason for attrition

Dissatisfaction level accounts for 31.28%

Majority of employees hold a Master’s degree

Highest monthly income: 11,997

Job roles with the highest attrition:

HR Executive

Data Analyst

Sales Representative

🛠 Tools & Technologies Used

Power BI

DAX

Data Modeling

Interactive Visual Analytics

👩‍💼 My Role

End-to-end project implementation

Data understanding and cleaning

Data modeling and relationship creation

KPI creation using DAX

Dashboard design and insight generation

🚧 Challenges Faced

Ordering categorical fields like education level correctly

Grouping years at company into meaningful tenure ranges

Ensuring visuals displayed data in a logical and interpretable sequence

🚀 Future Enhancements

Add predictive attrition analysis

Include salary vs attrition correlation

Add hiring and promotion trend analysis

Automate refresh with live HR data
