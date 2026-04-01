# Hospital Operations Analytics Dashboard (Power BI)

## Power BI Portfolio Project | Healthcare Analytics

---

## Project Overview

This project simulates a real-world hospital analytics reporting system designed to replace manual Excel-based reporting with an interactive Power BI dashboard.

The goal was to recreate how hospital leadership would monitor key operational and financial metrics such as patient admissions, bed occupancy, wait times, and billing performance.

Due to data confidentiality, a publicly available Kaggle dataset was used to simulate a similar healthcare reporting environment.

---

## Business Problem

Hospitals often rely on manual Excel reports that are:
- Slow to generate
- Prone to human errors
- Not available in real-time

This leads to delays in operational decision-making, especially in areas like capacity planning and billing efficiency.

---

## Solution

An interactive **3-page Power BI dashboard** was developed to provide self-service reporting and real-time visibility into hospital operations.

The dashboard enables users to:
- Track patient flow across departments
- Monitor hospital capacity and wait times
- Analyze billing performance and payment delays

---

## Dashboard Pages

### 1. Patient Admissions Overview

Focuses on patient inflow, discharge trends, and department performance.

**KPIs:**
- Total Admissions
- Total Discharges
- Active Patients
- ICU Admissions
- Department-wise trends
- Patient demographics (age group, insurance type)

---

### 2. Bed Occupancy & Wait Time Analysis

Tracks hospital capacity utilization and patient waiting experience.

**KPIs:**
- Bed Occupancy Rate
- Available Beds
- Average & Maximum Wait Time
- Department-level capacity analysis

**Key Insight:**
Some departments consistently operate near full capacity, indicating resource constraints and demand imbalance.

---

### 3. Billing & Financial Performance

Analyzes billing efficiency, collections, and payment delays across insurance types.

**KPIs:**
- Total Billed vs Collected Amount
- Outstanding Payments
- Collection Rate %
- Billing Turnaround Time

**Key Insight:**
Payment delays vary significantly across insurance types, impacting cash flow and financial planning.

---

## Dataset Information

Public healthcare datasets from Kaggle were used to simulate hospital operations data.

The dataset includes:
- Patient admissions and demographics
- Bed occupancy by department
- Wait time records
- Billing transactions
- Daily hospital census data

---

## Tools & Technologies

- Power BI (Dashboard development, DAX measures, data modeling)
- Power Query (Data cleaning and transformation)
- SQL (Data validation and preparation)
- Excel (Initial data exploration and structuring)

---

## Data Modeling Approach

- Built relational data model connecting patient, department, and billing data
- Created calculated fields for segmentation (age groups, wait time bands, stay duration)
- Developed reusable DAX measures for KPI calculations
- Enabled cross-filtering across dashboard pages

---

## Key Insights

- Certain departments consistently operate near full capacity
- Emergency wait times exceed acceptable thresholds during peak demand
- Billing delays vary significantly across insurance categories
- Dashboard reduces manual reporting effort by centralizing KPI tracking

---

## How to Use

1. Download Power BI Desktop (free)
2. Open the `.pbix` file from this repository
3. Use filters to explore departments, time periods, and metrics
4. Hover over visuals for detailed insights

---

## About This Project

This project was created as part of a data analyst portfolio to demonstrate skills in:
- Data visualization
- KPI design
- Data modeling
- Business reporting using Power BI

---

## Author

**Divya Karunanithi**  
Data Analyst | Power BI • SQL • Excel  
mailtodivya2525@gmail.com  
LinkedIn: https://www.linkedin.com/in/divya-karunanithi251992
