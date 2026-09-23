# Hospital Emergency Room Dashboard
An interactive Power BI dashboard built to analyze emergency room (ER) operations, patient flow, and satisfaction for a hospital system. It combines KPI cards, trend charts, and a drillable patient table to give administrators a full view of ER performance from a single report.
## Data Model
•	Hospital ER_Data — the core fact table containing individual patient visit records (demographics, wait times, admission status, satisfaction, and department referrals)
•	Date Table — a dedicated date dimension table enabling time intelligence (day, month, year breakdowns) and consistent date filtering across all report pages
## Report Pages (4)
## Page	## Purpose
Consolidated View	Landing/summary page with overall KPI cards, charts, and slicers for a top-level view of ER performance
Monthly View	Time-series analysis of patient volume and wait times, broken down by month, day, and year
Patient Details	A searchable, filterable table of individual patient records for drill-down analysis
Key Takeaways	Narrative-style summary page highlighting the report's main insights
## Metrics & Fields Tracked
•	Volume: Number of patients, number of patients referred
•	Wait Times: Average wait time, total wait time, wait-time interval buckets
•	Satisfaction: Patient satisfaction score
•	Admissions: Admission status
•	Demographics: Patient age, age group, gender, race
•	Operations: Department referrals
•	Time: Patient admission date, day/month/year trends
## Visual Types Used
Card KPIs, area charts, column/bar charts (including clustered bars), donut charts, pivot tables, a detail table, slicers, and page navigation buttons — all built natively in Power BI.
## Tools & Skills
•	Power BI Desktop (data modeling, DAX measures, report design)
•	Data cleaning and relationship modeling between fact and date tables
•	Interactive filtering via slicers and cross-highlighting between visuals

