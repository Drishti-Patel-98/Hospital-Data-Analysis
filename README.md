Goal:
To build an interactive Power BI dashboard to analyze MASSACHUSETTS GENERAL HOSPITAL’s encounters and patient care. It provides an overview of patient statistics, including total counts, average visits and their duration, as well as patient admissions and readmissions. By analyzing patient demographics and admission trends, the dashboard helps identify patterns essential for staffing and resource planning.

The dashboard also includes statistical data on procedures performed in the hospital, such as total procedures, procedure length, and costs. This information helps analyze metrics like operating room/ICU availability and assists in critical care management. Financial data provides insights into the hospital’s overall economic health. The dashboard aims to deliver actionable insights to hospital management for data-driven decision-making.

Key Tasks:
1. Data Connection and Transformation:
   - Connected to CSV data sources, including Patients, encounters, payers, and procedures using Power Query.
   - Applied data-cleaning techniques to ensure accuracy and consistency across all data sources.
   - Transformed and merged datasets to create a unified, comprehensive data model for analysis.
2. Data Analysis and DAX:
   - Created calculated Calendar and Time tables using DAX functions.
   - Created calculated columns and measures using DAX to compute essential metrics.
3. Interactive Dashboard:
   - Designed a user-friendly interactive dashboard with the following key elements:
   - KPI Cards
   - Bar Charts
   - Line Chart
   - Donut Charts
   - Funnel Charts
   - Table
   - Matrix
   - Added dynamic Slicers for easy filtering.

Insights:
- Total Patients: 974
- Total Encounters: ~28K
- The distribution of male (494) and female (480) patients is nearly equal.
- Suffolk County has the highest number of patients.
- Seniors outnumber other age groups.
- Higher patient visits are noticeable in colder months (February and March).
- The busiest hours are 7 PM on Tuesday and 9 AM on Wednesday.
- The Average Hours of encounter is ~7.
- The ambulatory class has the highest patients.
- The average encounter cost is 3.64K.
- 2.4% of patients are readmitted over the years.
- The average length of procedures is ~34 minutes.
- The Average daily procedures performed are 11. The highest in one day is 201 and the lowest is 1.
- The most performed procedure is the Assessment of health and social care needs, followed by Hospice care.
- Normal pregnancy (5.7K out of 47.7K) is the common reason for the procedure.
- February 2014 had the highest number of procedures performed.
- 30.6% was covered by insurance providers.
- Medicaid has the highest payer coverage (94.01%), followed by Dual eligible (89.25%).
- Nearly 50% of the cost was out of pocket.
- Wellness class has the highest % of payer coverage.
