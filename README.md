# Hospital-Emergency-Room-Dashboard
Hospital Emergency Room Dashboard using excel


# Hospital Emergency Room Dashboard

An interactive Excel dashboard that turns raw ER patient records into a monthly operational report — built to help hospital administration track patient inflow, wait times, admissions, and department load at a glance.

## Overview

Emergency Room teams generate huge volumes of patient-level data every day, but most of it sits unused in raw form. This project takes a **9,216-record patient dataset** and converts it into a single-screen, filterable dashboard that answers the questions hospital administrators actually ask every month:

- How many patients came in, and how long did they wait?
- Are we admitting more patients than we're discharging?
- Are patients being seen on time, or are delays piling up?
- Which departments are under the most referral pressure?
- What does our patient base look like by age and gender?

## Dashboard Features

| Component | What it shows |
|---|---|
| **Year & Month slicers** | Filter the entire report by 2023 / 2024 and by individual month |
| **KPI cards** | No. of Patients, Average Wait Time, Patient Satisfaction Score — each with a trend sparkline |
| **Admission Status** | Admitted vs Not Admitted, with count and % |
| **Patient Attend Status** | On-Time vs Delay split (donut chart) |
| **Gender-wise Analysis** | Male vs Female patient distribution (donut chart) |
| **Patient by Age** | 10-year age bands from 0–79 (bar chart) |
| **Patient by Department Referral** | Ranked referral volume across departments — General Practice, Orthopedics, Cardiology, Physiotherapy, Neurology, Renal, Gastroenterology |

## Sample Insight (January 2024 snapshot)

- **513** patients treated
- **36.3 min** average wait time
- **4.96 / 10** average patient satisfaction score
- **52%** of patients were admitted vs 48% not admitted
- **62%** of patients faced a delay vs 38% seen on time
- Roughly even gender split (53% F / 47% M)
- **General Practice** and **Orthopedics** accounted for the majority of department referrals

## Tools & Skills Used

- **Microsoft Excel** — Pivot Tables, Pivot Charts, Slicers, KPI cards, conditional formatting (in-cell data bars)
- **Data Cleaning** — handling duplicate columns, missing values, and inconsistent date formats in the raw export
- **Dashboard Design** — single-page layout principles, chart selection for categorical vs distribution data

## Dataset

`Hospital_Emergency_Room_Data.csv` — 9,216 rows, one record per patient visit, with fields including Patient ID, Admission Date, Gender, Age, Race, Department Referral, Admission Flag, Satisfaction Score, and Wait Time.


## About Me

I'm Shahid, a Data Analyst working with SQL, Python, Power BI, and Excel. This project is part of my growing portfolio as I build toward a full-time Data Analyst role.

📫 Feel free to connect or reach out if you'd like to discuss this project or data analytics in general.

