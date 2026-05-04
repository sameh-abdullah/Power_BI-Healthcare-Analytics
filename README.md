# 🩺 Healthcare Analysis Dashboard (Power BI)

## 📌 Overview
This project presents an interactive **Power BI dashboard** for healthcare analysis. It is designed to uncover insights that can drive better healthcare decisions, optimize costs, and improve patient outcomes.

The dashboard tells the story of patient care across hospitals, identifies trends, and helps stakeholders make data-informed decisions.

---

## ❗Key Questions to Answer in the Analysis:

- What are the most common age groups, genders, and blood types among patients? Are certain groups being admitted more often than others?
- Which medical conditions are diagnosed the most, and do they affect certain groups of people more than others?
- How long do patients typically stay in the hospital for different conditions? Does this vary depending on the hospital or type of admission (emergency, urgent, or planned)?
- How much does treatment usually cost for each condition? Are there big differences in costs between hospitals or insurance providers?
- Which hospitals are treating the most patients, and how do they compare in terms of patient outcomes, like test results?
- What medications are most often prescribed for each condition? Are they being used consistently across hospitals?
- How are patients admitted - mostly through emergency, urgent, or planned admissions - and how does that impact the length of stay or treatment costs?
- Which insurance companies are covering the most patients, and how does that relate to treatment costs and patient outcomes?
- Where are the hospitals located, and are there any regional differences in health conditions, treatment quality, or billing amounts?

---

## 📂 Dataset
- **Source:** Excel file (`Healthcare Analysis Dataset.xlsx`)
- **Main Table:** `healthcareData`

## 📝 Key Features
- Total patients, total bills, and average service time tracking
- Year-over-year comparisons for patients and billing
- Percentage-to-average metrics and color-coded performance indicators
- Age category, blood type, and medical condition analysis
- Hospital, doctor, medication, and insurance provider filtering
- Date-based analytics with admission and discharge date support
- Dynamic parameter selection for bill amount vs. average service time
- Geographic support via hospital latitude and longitude fields 

---

## 🧠 Data Model
Star schema with a fact table and lookup tables
---

## 🛠️ Tools & Technologies
- **Power BI**
- **Power Query** (Data Cleaning & Transformation)
- **DAX (Data Analysis Expressions)** for measures and calculations
- **Excel** (Data Source)

---

## 📈 Dashboard Features
- Interactive filter (year)
- KPI cards for quick insights
- Comparative analysis
- Visualizations:
  - KPIs
  - Bar charts  
  - Pie charts  
  - Trend analysis  
  - Distribution visuals

---

## 🖼️ Dashboard Preview
**Interactive Dashboard** <a href="https://app.powerbi.com/view?r=eyJrIjoiMzhhMTMxZmItM2I4Zi00NjgwLWE5MmItYTZhNmViMWM0YTYxIiwidCI6IjE1ODgyNjJkLTIzZmItNDNiNC1iZDZlLWJjZTQ5YzhlNjE4NiIsImMiOjh9"> Disease Analysis Dashboard</a></br>

**Project Dashboard Image**
<img src="https://github.com/sameh-abdullah/Power_BI-Healthcare-Analytics/blob/main/docs/Healthcare%20DB_p1.png" width="1000" heigh="1000"/></br>

<img src="https://github.com/sameh-abdullah/Power_BI-Healthcare-Analytics/blob/main/docs/Healthcare%20DB_p2.png" width="1000" heigh="1000"/>

---

## 📁 Project Structure
 ├── dataset/ <a href="dataset">Dataset (Excel file)</a> <br>
 ├── docs/ <a href="docs">docs</a> <br>
 ├── reports template/ <a href="report template"> Power BI file (.pbit)</a> <br>
 └── README.md


---

## 🎯 Project Value
This project demonstrates:
- Data modeling in Power BI  
- Use of DAX for analytical calculations  
- Building interactive dashboards  
- Translating raw data into meaningful insights
--------
## Architecture Notes
- The dashboard uses a clean star-schema architecture.
- Lookup tables normalize dimension data and improve filtering behavior.
- Measures are centralized in `_MeasuresTable` for easier maintenance.
- Date analysis is driven by a calculated `DateTable` rather than direct date columns.
- The model supports dynamic selections and parameter-driven report views.  

---

## 👤 Author
**Sameh Abdullah**  
**LinkedIn**: <a href="https://linkedin.com/in/sameh-abdullah-961554176"> My Profile </a> 

---

