# 🏥 Healthcare Operations & Revenue Analytics | Power BI Project

An interactive **Power BI healthcare analytics dashboard** analyzing hospital operations, patient demand, financial performance, insurance dependency, and provider efficiency using a multi-table healthcare dataset.

This project transforms raw hospital operational data into actionable business insights through **Power BI, Power Query, DAX, SQL validation, and advanced dashboard storytelling**.

---

# 📊 Dashboard Preview

📌 Click on the image to see the working of this project as a presentation  

## 📺 Dashboard Screenshot
[![Healthcare Dashboard](Images/POWERBI%20P3.png)](https://www.linkedin.com/posts/moksh-kapoor-618495322_powerbi-healthcareanalytics-dataanalytics-activity-7447501025500069888-BLGg?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFGVzjQBQzKnpNzkuOZayyyvYW4FkHnrf28)

---

## 🧩 Data Model

[![Healthcare Data Model](Images/Healthcare%20schema.jpg)](https://www.linkedin.com/posts/moksh-kapoor-618495322_powerbi-healthcareanalytics-dataanalytics-activity-7447501025500069888-BLGg?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFGVzjQBQzKnpNzkuOZayyyvYW4FkHnrf28)

---

# 🌐 Live Interactive Dashboard

👉 **View Live Power BI Dashboard:**  

[Click Here to Open Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOWY2YzQyMGMtOTZkZC00NTM0LWJlMDQtY2YzMDkwYWJiMjJiIiwidCI6ImIwNWJjYjBjLWVlYjgtNDMyOC05NDNkLTE1ZmVkYTE3ODBkZiJ9&pageName=7d9c2c191c22e4cfc246)

👉 **Watch Video Here:**  

[Click Here to Open Video](https://www.linkedin.com/posts/moksh-kapoor-618495322_powerbi-healthcareanalytics-dataanalytics-activity-7447501025500069888-BLGg?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFGVzjQBQzKnpNzkuOZayyyvYW4FkHnrf28)

---

# 📁 Dataset Overview

This project analyzes a **multi-table healthcare dataset** containing **5,000+ patient visit records**, representing real-world hospital operations across:

- Patient admissions & discharge  
- Diagnosis & treatment tracking  
- Insurance & billing operations  
- Provider performance  
- Revenue & operational analytics  

The dataset captures the complete patient journey — from admission to follow-up — enabling a comprehensive view of hospital performance.

---

# 🗂️ Dataset Structure

The project uses multiple normalized healthcare tables:

| Table | Description |
|---|---|
| patients.csv | Patient demographics |
| providers.csv | Doctors & provider details |
| departments.csv | Department information |
| diagnoses.csv | Diagnosis classifications |
| procedures.csv | Medical procedures |
| insurance.csv | Insurance provider data |
| cities.csv | Geographic information |
| visit_cleaned.csv | Visit-level operational & financial data |

---

# 🧩 Data Modeling

A **star-schema model** was built inside Power BI.

### 📌 Fact Table
- `visit_cleaned.csv`

### 📌 Dimension Tables
- Patients  
- Providers  
- Departments  
- Diagnoses  
- Procedures  
- Insurance  
- Cities  

The relational model ensured:

- High-performance reporting  
- Clean relationships  
- Accurate KPI calculations  
- Scalable analytics  

---

# 🧹 Data Cleaning & Transformation

Extensive data preparation was performed using **Excel Power Query** and **Power BI Power Query Editor**.

## ✔ Data Preparation Steps

- Standardized mixed date formats into ISO format  
- Corrected admission dates occurring after discharge dates  
- Handled null values in:
  - Satisfaction scores  
  - Insurance coverage  
  - Room charges  
  - Follow-up dates  

## ✔ Data Validation

- Validated relationships across all tables  
- Ensured accurate operational & financial calculations  
- Verified payment and billing consistency  

---

# 🎯 Business Problem & Analysis

Hospitals face challenges balancing:

- Patient care quality  
- Operational efficiency  
- Financial sustainability  

This project addresses critical healthcare problems such as:

- Rising treatment costs  
- Insurance dependency  
- Uneven provider workload  
- Declining patient demand  
- Low follow-up compliance  
- High outstanding revenue  

The objective is to convert operational hospital data into strategic insights using KPI-driven dashboards.

---

# 📊 Dashboard Pages

## 🏥 1. Patient & Demand Analytics

- Total Visits & Unique Patients  
- Repeat Visit Rate  
- Emergency Visit %  
- Inpatient vs Outpatient Ratio  
- Average Patient Age  
- Follow-Up Compliance Rate  
- Satisfaction Score  
- MoM & YoY Patient Trends  
- Diagnosis-level repeat visit analysis  

---

## 💰 2. Financial & Revenue Analytics

- Total Revenue & Revenue Trends  
- Revenue per Visit  
- Insurance Coverage %  
- Out-of-Pocket Amount  
- Cost Breakdown Analysis  
- Outstanding Revenue  
- Payment Pending Rate  
- Revenue by Department  
- High-Cost Diagnosis Analysis  

---

## 👨‍⚕️ 3. Operational & Provider Performance

- Provider Workload Distribution  
- Visits per Provider  
- Average Length of Stay (LOS)  
- Bed Utilization Metrics  
- Satisfaction by Provider  
- Procedure Utilization Rate  
- Diagnosis-wise LOS Analysis  
- Emergency Dependency by City  

---

# 🛠️ Tools, Techniques & Concepts Used

## 🔹 Power BI

- Multi-page dashboard development  
- KPI reporting dashboards  
- Drill-through analysis  
- Interactive storytelling  
- Slicers & bookmarks  

## 🔹 Power Query

- Data cleaning & transformations  
- Date standardization  
- Null handling  
- Validation logic  

## 🔹 Data Modeling

- Star schema architecture  
- Relationship management  
- Date table implementation  
- Time intelligence modeling  

## 🔹 DAX Measures

- Total Revenue  
- Repeat Visit Rate  
- Follow-Up Compliance %  
- Insurance Coverage %  
- LOS (Length of Stay)  
- MoM Growth %  
- YoY Growth %  
- Collection Efficiency KPIs  

## 🔹 SQL Server

- Exploratory Data Analysis (EDA)  
- Data validation  
- Quality checks  

## 🔹 Advanced Visualizations

- KPI cards  
- Line charts  
- Stacked bar charts  
- Conditional formatting  
- Trend analysis visuals  
- Drill-through pages  

---

# 📊 Key Insights & Findings

| Insight Category | Finding |
|---|---|
| Patient Trends | Patient volume declined ~36% YoY |
| Revenue Growth | Revenue increased from 2.3M to 3.4M |
| Emergency Dependency | Emergency visits account for ~38.58% |
| Insurance Coverage | Only ~39% insurance coverage |
| Outstanding Revenue | Outstanding collections ~2.4M |
| Hospital Utilization | Outpatient services dominate (~67%) |
| Provider Efficiency | Workload uneven across providers |
| LOS Analysis | Average Length of Stay ~6.7 days |
| Follow-Up Compliance | Only ~50% compliance |
| Retention | Repeat visit rate extremely low (~0.52%) |
| Provider Capacity | Hospital operates with only 5 doctors |

---

# 💡 Business Insights

## 🏥 Patient Insights

- Senior patients contribute the largest demand share  
- Emergency dependency suggests preventive care gaps  
- Weak follow-up systems reduce long-term patient retention  

## 💰 Financial Insights

- Revenue increased despite declining patient volume  
- High outstanding revenue creates cash flow pressure  
- Low insurance coverage increases patient financial burden  

## 👨‍⚕️ Operational Insights

- Provider workload imbalance increases burnout risk  
- Certain diagnoses drive prolonged hospitalization  
- OPD services dominate hospital utilization patterns  

---

# 🎯 Strategic Recommendations

- Improve patient retention & follow-up systems  
- Expand insurance partnerships  
- Strengthen billing & collection workflows  
- Optimize provider workload allocation  
- Reduce Length of Stay for high-LOS diagnoses  
- Promote preventive care programs  
- Address declining patient demand through outreach initiatives  

---

# 🔍 Key Learnings

Through this project, I improved my skills in:

- Healthcare Analytics  
- Power BI Dashboarding  
- Data Modeling  
- Power Query Transformations  
- DAX Calculations  
- Time Intelligence Analysis  
- Revenue Analytics  
- Operational KPI Development  
- SQL Validation & EDA  
- Business Storytelling  

---

# 📂 Repository Structure

```bash
healthcare-operations-revenue-analytics-powerbi/
│
├── Datasets/
│   ├── Datasets.rar
|
├── Images/
│   ├── POWERBI P3.png
│   └── Healthcare schema.jpg
│
├── README.md
```

---

# 👤 Author

## Moksh Kapoor

📊 Aspiring Data Analyst  

### Skills
SQL • Power BI • Excel • Python

🔗 LinkedIn:  
[Visit My LinkedIn Profile](https://www.linkedin.com/in/moksh-kapoor-618495322/)

---

⭐ If you like this project, consider giving it a **star** on GitHub!
