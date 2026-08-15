Recruitment Pipeline Dashboard (Power BI)

An interactive Power BI dashboard that tracks 900 job applications through a 6-stage recruitment funnel — Applied → Screening → Interview 1 → Interview 2 → Offer → Hired — built on a star schema data model with DAX-driven KPIs.

Business Problem

HR had no single view of where candidates drop off, how long hiring takes, or which departments convert applicants best. This dashboard consolidates applicant, job, company, and stage-level data into one interactive report to answer those questions.

Key Insights
Overall conversion rate: 5.7% (900 Applied → 51 Hired)
Biggest bottleneck: 48% drop-off between Interview 1 and Interview 2 (487 → 254) — the steepest stage in the funnel
Average time-to-hire: 43 days
81.8% of applications end in "Rejected" status
Conversion rate varies notably by department, pointing to inconsistent screening practices
Dashboard Features
Star schema (applicants, applications, application_stages, jobs, companies)
KPI cards: Total Applications, Total Hired, Conversion Rate %, Avg Days to Hire
Recruitment funnel with stage-by-stage counts
Monthly application trend
Conversion rate by department
Breakdown by job title, company, and final status
Interactive slicers: Department, Company, Date Range
Tech Used

Power BI Desktop · DAX (CALCULATE, LOOKUPVALUE, DATEDIFF, AVERAGEX) · Star Schema Modeling

Note on Data

This is a synthetic dataset I generated myself to simulate a realistic recruitment pipeline, so I could practice star schema design and DAX without needing real HR data. The schema mirrors a real ATS structure, with realistic patterns like funnel drop-off and time gaps built in.

Screenshot

Show Image <img width="1772" height="813" alt="Screenshot 2026-08-15 200950" src="https://github.com/user-attachments/assets/0d369704-0d8a-458a-8b73-759ee7bc415f" />


Files
/data — Source CSV files
/dashboard/recruitment_dashboard.pbix — Power BI file (open in Power BI Desktop)
/docs — Problem statement & solution write-up (Word)
How to Use
Download recruitment_dashboard.pbix
Open in Power BI Desktop (free)
Use the slicers to filter by Department, Company, or Date
