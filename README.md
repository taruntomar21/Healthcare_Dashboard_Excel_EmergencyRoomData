# 🏥 Hospital Emergency Room Analytics Dashboard (Excel)
 
An interactive Excel dashboard built to analyze hospital emergency room patient data. It covers admissions, wait times, patient satisfaction, and department referrals to help hospital administrators identify bottlenecks and improve patient flow.
 
![Dashboard Preview](dashboard_preview.png)
 
---
 
## Project Overview
 
Emergency rooms generate large volumes of patient data every day, but raw records rarely translate into action on their own. This project takes a real-world-style hospital ER dataset and transforms it into a single-page, decision-ready dashboard using Excel's native BI capabilities like Pivot Tables, Pivot Charts, Slicers, and calculated KPIs.
 
The objective: give hospital staff a fast, visual way to answer questions like *"Are patients waiting too long?"*, *"Which departments get the most referrals?"*, and *"How does patient volume vary across age groups?"*
 
---
 
## Dataset
 
- **Source file:** `Hospital_Emergency_Room_Data.csv`
- **Records:** 9,216 patient visits
- **Time period:** Jan 2023 – Dec 2024
- **Columns:** Patient ID, Admission Date, First Initial, Last Name, Gender, Age, Race, Department Referral, Admission Flag, Satisfaction Score, Wait Time
 
## Tools & Techniques
 
| Category | Details |
|---|---|
| **Tool** | Microsoft Excel |
| **Data Modeling** | Pivot Tables, Calendar (Date) Table for time intelligence |
| **Visuals** | Pivot Charts, Donut Charts, Pie Charts, Bar Charts, KPI Cards |
| **Interactivity** | Slicers (Year: 2023 / 2024) |
| **Data Cleaning** | Standardizing gender labels, handling blanks/nulls, removing duplicate columns |
| **KPIs Calculated** | Monthly Report Count, Average Wait Time, Average Satisfaction Score, Admission % |
 
---
 
## Dashboard Features
 
- **KPI Summary Cards** — Monthly patient count, average wait time, and average satisfaction score at a glance
- **Admission Status Breakdown** — Admitted vs. Not Admitted patients with percentage split
- **Patient Volume by Age Group** — Bar chart across 8 age bands (0–9 through 70–79)
- **Patient Attend Status** — On-time vs. Delayed attendance (donut chart)
- **Gender-Wise Analysis** — Male vs. Female patient distribution
- **Department Referral Analysis** — Ranked bar chart of referrals (General Practice, Orthopedics, Physiotherapy, Cardiology, Neurology, Renal, etc.)
- **Year Slicer (2023/2024)** — Toggle the entire dashboard between reporting years
---
 
## Key Insights
 
- Patient attendance was split **56% delayed vs. 44% on-time**, suggesting scheduling or capacity constraints during peak periods.
- Admission outcomes were nearly balanced — **52.3% Not Admitted** vs. **47.7% Admitted** — indicating a large share of ER visits are resolved without hospital admission.
- The **30–39 age group** recorded the highest patient volume among all age bands.
- **General Practice** and **Orthopedics** were the top referred departments after direct ER discharge (no referral).
- Gender distribution was fairly even, with a slight skew toward female patients (54% vs. 46%).
---
 
## Repository Structure
 
```
├── Hospital_Emergency_Room_Data.csv   # Raw dataset
├── healthcare_analysis.xlsx           # Excel file with data model, pivot tables & dashboard
├── dashboard_preview.png              # Dashboard screenshot
└── README.md                          # Project documentation
```
 
---
 
## How to Use
 
1. Clone or download this repository.
2. Open `healthcare_analysis.xlsx` in Microsoft Excel (2016 or later recommended for full Pivot/Slicer support).
3. Navigate to the **Dashboard** sheet.
4. Use the **Year slicer** to filter the view between 2023 and 2024.
5. Explore the underlying data model in the **Hospital Emergency Room Data** and **Calendar Table** sheets.
---

 
## Author
 
**Tarun Kumar**
- B.Tech, NIT Jalandhar
- Data Analytics 
