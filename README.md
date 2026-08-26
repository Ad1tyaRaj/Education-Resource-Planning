🎓 Education Resource Planning & Enrolment Analytics

<p align="center">
<b>Raw School Data → Feature Engineering → Priority Scoring → Power BI Decision Dashboard</b>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
<img src="https://img.shields.io/badge/Python-Pandas-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/DAX-Analytics-1F4E79?style=for-the-badge">
<img src="https://img.shields.io/badge/Power%20Query-ETL-742774?style=for-the-badge">
</p>

Portfolio Project: A school-level education analytics case study focused on enrolment, gender composition and planning-priority analysis.

🚀 Project at a Glance

Area

Details

Dashboard

4-page interactive Power BI report

Schools

~2,121 in dashboard analysis

Students

~394,721

Core Tools

Python, Pandas, Power Query, DAX, Power BI

Key Output

Planning Priority Score & Priority Level

Focus

Education Resource Planning

🎯 Problem Statement

Raw enrolment data contains many school-level records, but stakeholders need concise answers:

Where is enrolment concentrated?
Where is gender imbalance higher?
Which schools have relatively high enrolment?
Which schools may require relatively higher planning attention?

This project converts raw records into derived analytical indicators and presents them through an interactive Power BI dashboard.

⚠️ Important: The Priority Score is a project-defined analytical framework. It is not an official government score and does not measure school performance or quality.

🔄 End-to-End Workflow

RAW SCHOOL DATA
      ↓
DATA CLEANING & TRANSFORMATION
      ↓
FEATURE ENGINEERING
      ↓
 ┌─────────────────────────────┐
 │ Total Students              │
 │ Active Class Count          │
 │ Boys % / Girls %            │
 │ Gender Gap                  │
 │ Absolute Gender Gap         │
 │ School Size Category        │
 │ High-Enrolment Status       │
 └─────────────────────────────┘
      ↓
WEIGHTED PRIORITY SCORE
      ↓
LOW / MEDIUM / HIGH / VERY HIGH
      ↓
INTERACTIVE POWER BI DASHBOARD
      ↓
PLANNING-ORIENTED INSIGHTS

<img width="1774" height="887" alt="Flow chart" src="https://github.com/user-attachments/assets/a1633240-b451-486e-b321-b9cb53d2560a" />


🧠 Feature Engineering

Feature

What it tells us

Total Students

Total enrolment at school level

Active Class Count

Number of classes/stages with active enrolment

Boys %

Share of boys among enrolled students

Girls %

Share of girls among enrolled students

Gender Gap

Direction of boys-vs-girls percentage difference

Absolute Gender Gap

Magnitude of gender imbalance

School Size Category

Relative school enrolment size

High-Enrolment Status

Schools at/above the 75th percentile of enrolment

Gender Metrics

Gender Gap = Boys % − Girls %

Absolute Gender Gap = |Boys % − Girls %|

High-Enrolment Logic

Grand Total ≥ 75th Percentile
              ↓
      High-Enrolment Status

This is an enrolment-based indicator, not a direct measure of actual demand.

🎯 Priority Score

The project combines selected indicators into a weighted planning score:

Indicator

Weight

Absolute Gender Gap

40%

High-Enrolment Status

20%

School Size Category

20%

Active Class Count

20%

Total

100%

Priority Levels

Priority

Score

🟢 Low

< 0.25

🟡 Medium

0.25 – < 0.50

🟠 High

0.50 – < 0.75

🔴 Very High

≥ 0.75

A higher level means higher relative planning attention under this project's framework — not poor school performance.

📊 Dashboard Structure

01 — Overview

High-level view of schools, students, gender composition, enrolment by block, priority distribution and education-stage share.

02 — Enrolment & Gender Analytics

Block-wise enrolment, active-class enrolment, boys vs girls and school-management analysis.

03 — Priority & School Analytics

Gender-gap analysis, education-stage share, priority-level distribution and schools ranked by Priority Score.

04 — Summary & School Analytics

School-level table with Block, Enrolment Status, School Name, Priority Score, Priority Level, Grand Total, Boys %, Girls % and Gender Gap.

🛠️ Technology Stack

Tool

Role

🐍 Python / Pandas

Cleaning, transformation & feature engineering

🔄 Power Query

ETL and data preparation

📐 DAX

KPIs, measures & interactive calculations

📊 Power BI

Dashboard, visualization & storytelling

📸 Dashboard Preview

After adding your sanitized screenshots:

## Dashboard Preview

### Overview
<img width="905" height="501" alt="overview" src="https://github.com/user-attachments/assets/29fc9b9a-3693-49fa-9c74-aaa115c8d104" />


### Enrolment & Gender Analytics
<img width="887" height="500" alt="enrolment-gender" src="https://github.com/user-attachments/assets/6574c54a-87ab-472e-b539-fdc6d994a8d5" />

### Priority & School Analytics
<img width="889" height="498" alt="priority" src="https://github.com/user-attachments/assets/f20ed4f1-293f-4e24-aa33-a405d1209896" />

### Summary & School Analytics
<img width="904" height="505" alt="summary" src="https://github.com/user-attachments/assets/7d2eca10-6346-40db-9cc4-8b5321f722f6" />


📁 Repository Structure

Education-Resource-Planning/
│
├── README.md
│
├── dashboard/
│   └── |
│       ├── overview.png
│       ├── enrolment-gender.png
│       ├── priority.png
│       └── summary.png
│
└── documentation/
    └── project-flow.png

💡 Key Questions Answered

Which blocks have the highest enrolment?


What is the boys/girls distribution?


Which blocks have a larger gender gap?


Which schools have relatively high enrolment?


How many active classes are present?


How are schools distributed across priority levels?


Which schools have higher Priority Scores?


How can raw enrolment data be transformed into planning-oriented insights?


## 🔐 Data Privacy

The original dataset contains confidential information.

For this public portfolio:

- ❌ Original confidential dataset is not published
- ❌ Sensitive school-level identifiers are not exposed
- ❌ Confidential Power BI reports are not shared publicly
- ✅ Only sanitized dashboard screenshots and project methodology are presented

📈 Project Outcome

Raw Data → Cleaning → Feature Engineering → Priority Scoring → Classification → Power BI → Planning Insights

The project demonstrates how data analytics can move beyond basic visualization and create a structured decision-support framework for identifying where further planning attention may be required.

## 👨‍💻 My Contribution

- Cleaned and prepared school-level enrolment data using Python/Pandas
- Created school-level analytical features
- Developed gender and enrolment indicators
- Designed a weighted Priority Score framework
- Created DAX measures for interactive analysis
- Built a 4-page Power BI dashboard
- Designed school-level and block-level visualizations
- Converted analytical results into planning-oriented insights
- Documented assumptions and data-privacy considerations

👤 Author

Aditya Raj

Data Analytics • Power BI • DAX • Python • Pandas • Feature Engineering • Education Analytics

⭐ Portfolio Note: The weights, thresholds and Priority Score are project-defined assumptions created to demonstrate analytical thinking; they are not official policy criteria.
