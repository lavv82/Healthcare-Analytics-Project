# Healthcare Data Analytics & Insights

## 📌 Project Summary

This project analyzes **10,000 patient records (2023–2025)** across five hospital departments — General Medicine, Cardiology, Pediatrics, Neurology, and Orthopedics — to uncover patterns in patient volume, diagnoses, billing, lab test outcomes, and follow-up care. Using **SQL, Excel, Power BI, and Tableau**, the project builds 7 core KPIs and an interactive dashboard to help hospital stakeholders improve **care quality, operational efficiency, and cost control**.

The analysis goes beyond reporting numbers — it identifies where the hospital system is losing revenue (underperforming departments), where patient care is at risk (pending/abnormal test results, missed follow-ups), and provides a prioritized 90-day action plan.

## 🔑 Key Findings

- **Patient base:** 10,000 unique patients form the foundation of the analysis; one diagnosis and one visit recorded per patient, with monthly visits stable at ~400–460 (steady, not growing).
- **Diagnosis mix:** Nearly evenly split across five categories — Migraine (2,039), Hypertension (2,011), Asthma (2,009), Healthy (1,981), Diabetes (1,960). Chronic conditions (Diabetes, Asthma, Hypertension) account for **60% of patients (5,980)**, highlighting a large chronic-care population.
- **Billing concentration:** Total billing ≈ **$25.4M**. General Medicine ($5.51M), Cardiology ($5.31M), and Pediatrics ($5.25M) together drive **~63% of revenue**, while Neurology ($4.72M) and Orthopedics ($4.61M) trail behind — flagging a growth opportunity through service bundles and referral pathways.
- **Cost benchmark:** Average treatment cost is **$524.75 per patient**, useful as a baseline for cost control and pricing reviews across departments.
- **Lab turnaround risk:** Test results are split almost evenly — Abnormal (33.54%), Pending (33.44%), Normal (33.02%). A full third of results pending risks delayed treatment and lower patient satisfaction; a third abnormal requires prioritized clinical review.
- **Follow-up gap:** **49.84%** of patients require follow-up care — nearly half the population — creating a direct exposure to missed complications and lost revenue if follow-ups aren't tracked.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **MySQL** | Data validation — record counts, null/completeness checks, referential consistency, duplicate detection across Patient, Visit, Treatment, and Lab tables |
| **Excel** | Data preparation and KPI-level dashboard |
| **Power BI** | Interactive dashboard with KPI visualizations |
| **Tableau** | Additional dashboard and visual analysis layer |

## 📊 KPIs Tracked

1. Total Number of Patients
2. Diagnosis Count (by condition category)
3. Amount Billed by Department
4. Average Treatment Cost
5. Test Results Percentage (Normal / Abnormal / Pending)
6. Follow-up Rate (required vs. not required)
7. Interactive Dashboard combining all KPIs (Power BI, Tableau, Excel)

## 💡 Recommendations

- **Data & Tracking:** Enable patient-level IDs for repeat visits to track longitudinal care and readmissions.
- **Clinical Prioritization:** Set up auto-alerts for abnormal and pending lab results; fast-track diagnostics for urgent cases.
- **Operational Efficiency:** Use patient-volume trends for staffing and lab capacity planning.
- **Revenue Optimization:** Analyze Neurology/Orthopedics pricing and volumes; design targeted service bundles to close the billing gap with top-performing departments.
- **Patient Engagement:** Implement automated reminders (SMS/WhatsApp/Email) for follow-ups, with a completion dashboard to track outreach.
- **Priority (first 90 days):** Reduce the pending-test rate and strengthen chronic-care outreach.

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Healthcare_project_Sql.sql` | SQL schema and data-quality validation queries — record counts, completeness checks, consistency checks, and duplicate detection |
| `Healthcare_Project_Excel.xlsx` | Excel workbook with KPI-level analysis and dashboard |
| `Healthcare_Project_Power_Bi.pbix` | Power BI interactive dashboard covering all 7 KPIs |
| `Healthcare_Tableau_dashboard.twbx` | Tableau workbook with dashboard visualizations |
| `Healthcare-Data-Analytics-and-Insights.pptx` | Presentation summarizing findings, KPI breakdowns, and recommendations |



## 🎯 Skills Demonstrated

- SQL: Data validation, completeness checks, referential integrity (LEFT JOIN for orphan detection), duplicate detection (GROUP BY / HAVING)
- Excel: Data preparation and KPI computation
- Power BI & Tableau: Interactive dashboard design across multiple BI tools
- Business analysis: Translating clinical and billing data into prioritized, actionable recommendations

---
*This project was built as part of my Data Analyst portfolio, demonstrating an end-to-end healthcare analytics workflow across SQL, Excel, Power BI, and Tableau.*
