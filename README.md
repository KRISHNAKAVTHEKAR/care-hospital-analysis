# care-hospital-analysis
🏥 Medical Care Hospital Analysis
## Problem Statement
This dashboard provides an insightful analysis of hospital operations, focusing on patient demographics, treatment efficiency, resource utilization, and operational bottlenecks. The goal is to help hospital administrators and healthcare professionals optimize hospital performance and improve patient care using data-driven decisions.
## Steps Followed
Step 1: Data Import & Preprocessing
- Loaded the dataset (CSV/SQL) into Power BI Desktop.
- Opened Power Query Editor to clean and transform data.
- Checked column distribution, quality, and profile for missing values.
Step 2: Data Cleaning
- Removed duplicates and handled missing values.
- Ensured data consistency.
Step 3: Data Modeling & DAX Calculations
- Created relationships between tables.
- Added DAX measures for key insights, such as:
  - 🏥 Total Patients Count = COUNT(Patients[Patient ID])
  - ⏳ Average Treatment Duration = AVERAGE(Appointments[Treatment Time])
  - 📈 Bed Occupancy Rate = SUM(Hospital[Occupied Beds]) / SUM(Hospital[Total Beds])
  - 💰 Revenue per Department = SUM(Billing[Total Revenue])
Step 4: Visualization & Dashboard Design
- Used interactive visuals including slicers, bar charts, pie charts, line charts, and KPI cards.
Step 5: Publishing & Sharing
- Published the report to Power BI Service.
- Set up role-based access for doctors, administrators, and staff.
## Key Insights
 *  Patient Trends:
- Majority of admissions are emergency cases (~65%).
- Readmission rate is high in certain departments.
  * Hospital Performance:
- Bed occupancy rate is at 85%.
- Surgical departments contribute the highest revenue.
  * Doctor & Staff Efficiency:
- Average consultation time is 20 minutes.
- Some doctors handle more than 50 patients per day.
## Conclusion
The Medical Care Hospital Analysis Dashboard empowers healthcare administrators with real-time insights into patient care, hospital operations, and financial performance. By leveraging data analytics, hospitals can improve efficiency, enhance patient satisfaction, and optimize resources effectively.
