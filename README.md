# 📊 Recruitment Pipeline Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-6A3FA0?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

An interactive Power BI dashboard that tracks **900 job applications** through a 6-stage recruitment funnel — **Applied → Screening → Interview 1 → Interview 2 → Offer → Hired** — built on a star schema data model with DAX-driven KPIs.

Dashboard <img width="1772" height="813" alt="Screenshot 2026-08-15 200950" src="https://github.com/user-attachments/assets/0281f46e-6256-4ee1-931d-f2901df93408"/>


---

## 🎯 Business Problem

HR had no single view of where candidates drop off, how long hiring takes, or which departments convert applicants best. This dashboard consolidates applicant, job, company, and stage-level data into one interactive report to answer those questions.

---

## 🔍 Key Insights

| Metric | Value | So what? |
|---|---|---|
| Conversion Rate | **5.7%** | 900 Applied → only 51 Hired |
| Biggest Bottleneck | **48% drop-off** | Between Interview 1 → Interview 2 (487 → 254) |
| Avg. Time-to-Hire | **43 days** | Benchmark for future hiring speed |
| Rejection Rate | **81.8%** | Most applications end in "Rejected" |
| Department Gap | **Varies widely** | Points to inconsistent screening practices |

---

## ⚙️ Dashboard Features

- 🧩 Star schema (`applicants`, `applications`, `application_stages`, `jobs`, `companies`)
- 📌 KPI cards — Total Applications, Total Hired, Conversion Rate %, Avg Days to Hire
- 🔻 Recruitment funnel with stage-by-stage counts
- 📈 Monthly application trend
- 🏢 Conversion rate by department
- 📊 Breakdown by job title, company, and final status
- 🎛️ Interactive slicers — Department, Company, Date Range

---

## 🛠️ Tech Stack

`Power BI Desktop` · `DAX` (CALCULATE, LOOKUPVALUE, DATEDIFF, AVERAGEX) · `Star Schema Modeling`

---

<details>
<summary>📁 <b>Project Structure</b> (click to expand)</summary>

```
recruitment-pipeline-dashboard/
├── data/              → Source CSV files
├── dashboard/          → recruitment_dashboard.pbix
├── docs/                 → Problem statement & solution write-up (Word)
```

</details>



---

## 🚀 How to Use

1. Download `dashboard/recruitment_dashboard.pbix`
2. Open in **Power BI Desktop** (free)
3. Use the slicers to filter by Department, Company, or Date

---

## 📬 Connect

If you have feedback or questions about this project, feel free to reach out or open an issue on this repo.
