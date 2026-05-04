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
- **Main Table:** `Heart_disease_table`

### Key Attributes:
- **Demographics:** Age, Gender  
- **Clinical Metrics:** Blood Pressure, Cholesterol Level, BMI  
- **Lifestyle Factors:** Smoking, Exercise Habits, Alcohol Consumption  
- **Medical History:** Family Heart Disease, Diabetes  
- **Biomarkers:** HDL, LDL, CRP Level, Homocysteine Level  
- **Other Factors:** Stress Level, Sleep Hours, Sugar Consumption  
- **Target Variable:** Heart Disease Status  

---

## 🧠 Data Model
The model is built around one main fact table with supporting calculated tables for better segmentation:

### 🔹 Main Table
- `Heart_disease_table` → Core dataset containing all patient records

### 🔹 Supporting Tables
- `Family_Smoking_Diabete`  
  - Groups: Smoking, Family Heart Disease, Diabetes, High Blood Pressure  

- `HDL_LDL`  
  - Groups cholesterol-related indicators (High LDL, Low HDL)  

- `Stress_Alcohol`  
  - Groups lifestyle factors (Stress Level, Sugar Consumption)  

---

## 🛠️ Tools & Technologies
- **Power BI**
- **Power Query** (Data Cleaning & Transformation)
- **DAX (Data Analysis Expressions)** for measures and calculations
- **Excel** (Data Source)

---

## 📈 Dashboard Features
- Interactive filters (Age, Gender, Lifestyle, Medical Conditions)
- KPI cards for quick insights
- Comparative analysis (Heart Disease vs No Heart Disease)
- Risk factor segmentation
- Visualizations:
  - Bar charts  
  - Pie charts  
  - Trend analysis  
  - Distribution visuals  

---

## 🔍 Key Insights
- Identifies the **most influential risk factors** for heart disease  
- Highlights relationships between:
  - Cholesterol levels (HDL/LDL)
  - Lifestyle habits (smoking, stress, alcohol)
  - Medical conditions (diabetes, blood pressure)
- Provides a clear comparison between affected and non-affected patients  

---

## 🖼️ Dashboard Preview
**Interactive Dashboard** <a href="https://app.powerbi.com/view?r=eyJrIjoiYmJmMjUxZTMtZWQwMS00ZTkwLTgwOGEtOGVjYzAwMTY0YTVlIiwidCI6IjE1ODgyNjJkLTIzZmItNDNiNC1iZDZlLWJjZTQ5YzhlNjE4NiIsImMiOjh9"> Disease Analysis Dashboard</a></br>

**Project Dashboard Image**
<img src="https://github.com/sameh-abdullah/Power_BI-Heart-Disease-Analytics/blob/main/Images/Screenshot%202026-05-03%20212815.png" width="1000" heigh="1000"/>

---

## 📁 Project Structure
 ├── dataset/ <a href="">Dataset (Excel file)</a> <br>
 ├── images/ <a href=""> Dashboard screenshots</a> <br>
 ├── reports template/ <a href="report template"> Power BI file (.pbit)</a> <br>
 └── README.md


---

## 🎯 Project Value
This project demonstrates:
- Data modeling in Power BI  
- Use of DAX for analytical calculations  
- Building interactive dashboards  
- Translating raw data into meaningful insights  

---

## 👤 Author
**Sameh Abdullah**  
**LinkedIn**: <a href="https://linkedin.com/in/sameh-abdullah-961554176"> My Profile </a> 

---

