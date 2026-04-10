📊 HR Analytics Dashboard | Power BI | End-to-End Data Analysis Project
🧩 Business Problem

Employee attrition is a critical challenge for organizations, impacting productivity, cost, and team stability. However, HR teams often lack granular visibility into attrition drivers across demographics, compensation, and job roles.

This project aims to solve this by building a data-driven HR Analytics Dashboard that transforms raw employee data into actionable insights.

🎯 Objective
 1. Analyze and monitor employee attrition trends.
 2. Identify key drivers of workforce turnover.
 3. Segment employees based on demographic and business attributes.
 4. Enable HR stakeholders to take data-backed retention decisions.

🛠️ Technical Implementation
🔄 Data Transformation (Power Query - ETL)

Performed structured data preparation to ensure analytical accuracy:

1. Cleaned and standardized raw HR dataset.
2. Handled missing and inconsistent values.
3. Created Attrition Count (Binary Encoding).
4. Converted categorical attrition into numeric (1 = Yes, 0 = No).
5. Enabled aggregation and KPI computation.
6. Implemented Age Banding with Custom Sorting.
7. Grouped employees into logical age brackets.
8. Applied Sort by Column to maintain correct chronological order in visuals.

📌 Why this matters:
Default alphabetical sorting leads to misleading visuals — this fix ensures correct analytical storytelling.

🧮 Data Modeling & DAX

Developed dynamic KPIs using DAX measures:

Key Measures:

1. Total Employees = COUNT(Employee[Employee ID])

2. Attrition Count = SUM(Employee[Attrition Count])

3. Attrition Rate = 
DIVIDE([Attrition Count], [Total Employees], 0)

Analytical Design Choices:
1. Used measures instead of calculated columns for dynamic filtering
2. Ensured all KPIs respond to slicers (interactive analysis)
3. Optimized calculations for performance and scalability


📊 Dashboard Capabilities
🔍 Attrition Analysis
1. Overall attrition rate
2. Department-wise and role-wise breakdown
3. Identification of high-risk segments

👥 Workforce Demographics
1. Age distribution (correctly sorted)
2. Gender-based insights
3. Education-level segmentation
   
💰 Compensation Insights
1. Salary distribution across workforce
2. Correlation between salary bands and attrition

🎛️ Interactivity
1. Fully dynamic dashboard using slicers
2. Drill-down capability for deeper analysis

📈 Key Insights
1. Higher attrition observed in specific job roles and departments
2. Employees in lower salary bands show significantly higher turnover
3. Mid-career professionals contribute most to attrition
4. Demographic segmentation reveals targeted retention opportunities

💡 Business Impact

This dashboard enables HR teams to:

1. Proactively identify high-risk employee segments
2. Optimize compensation and retention strategies
3. Improve workforce planning
4. Transition from reactive to data-driven HR decision-making

🚀 How to Use
1. Open .pbix file in Power BI Desktop
2. Refresh dataset if required
3. Use slicers to interact with insights


🔮 Future Enhancements
1. Predictive attrition modeling (ML integration)
2. Real-time HR data pipeline
3. Advanced drill-through analytics


👨‍💻 Author

Rishav Sarkar
Aspiring Data Analyst | Power BI Developer
