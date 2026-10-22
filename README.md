<div align="center">

# 📊 Data Professional Survey Dashboard (Power BI)

**An interactive Power BI dashboard exploring who works in data, what they earn, which tools they use, and how happy they are.**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-Calculated%20Columns-blue)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

Dashboard preview <img width="895" height="424" alt="Power BI DashBoard" src="https://github.com/user-attachments/assets/401215db-b94e-4fe0-8667-abcd92ee8db4" />

</div>

---

## Table of Contents

- [Overview](#overview)
- [Key Insights](#key-insights)
- [Dashboard Components](#dashboard-components)
- [Dataset](#dataset)
- [Data Preparation](#data-preparation)
- [Skills Demonstrated](#skills-demonstrated)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Next Steps](#next-steps)
- [Contact](#contact)

## Overview

What does the data profession look like? This project turns a survey of **630 data professionals** into a one-page Power BI dashboard. It shows the mix of job titles, salaries, favorite programming languages, countries, job satisfaction, and how hard it was to break into the field.

The dashboard is designed for anyone exploring a career in data, such as students, career switchers and recruiters, to see the field at a glance.

## Key Insights

| Topic | Finding |
|-------|---------|
| **Respondents** | 630 data professionals, with an average age of about 30 |
| **Roles** | Data Analysts are the largest group (381 of 630, about 60%), followed by Data Engineers (38) and Data Scientists (25) |
| **Programming languages** | **Python is the favorite for about two-thirds of respondents** (420), well ahead of R (101) |
| **Location** | 41% of respondents live in the United States, followed by India, the United Kingdom and Canada |
| **Career switchers** | 59% switched careers into data |
| **Breaking in** | About 32% found it difficult or very difficult to break into data, while 26% found it easy or very easy |
| **Satisfaction** | Respondents are least happy with **salary (4.3 average)** and **upward mobility (4.8)**, and happiest with coworkers (5.9) and work/life balance (5.7) |
| **Priorities** | **Better salary** is the most important factor when looking for a new job (47%), ahead of remote work (20%) and work/life balance (19%) |
| **Pay by role** | Estimated average salary (from range midpoints) is highest for Data Scientists (about $94K), then Data Engineers (about $65K) and Data Analysts (about $55K) |

## Dashboard Components

| Visual | Type | What It Shows |
|--------|------|---------------|
| **Count of Survey Takers** | KPI card | Total respondents (630) |
| **Average Age of Survey Takers** | KPI card | Average respondent age (29.87) |
| **Average Salary by Job Title** | Bar chart | Average salary (in $K) for each job title, from Data Scientist at the top to Student/Looking/None at the bottom |
| **Favorite Programming Language** | Stacked column chart | Language preferences, split by job title |
| **Country of Survey Takers** | Treemap | Where respondents live (United States, India, United Kingdom, Canada and Other) |
| **Happiness With Salary** | Gauge (0 to 10) | Average satisfaction with pay (4.27) |
| **Happy with Work/Life Balance** | Gauge (0 to 10) | Average satisfaction with work/life balance (5.74) |
| **Difficulty to Break Into Data** | Donut chart | How respondents rated entry difficulty (43% neutral, 25% difficult, 21% easy) |

## Dataset

| Property | Detail |
|----------|--------|
| File | `Power BI - Final Project.xlsx` |
| Records | 630 survey responses |
| Columns | 28 |
| Topics | Job title, career switch, salary range, industry, favorite language, six job-satisfaction ratings, difficulty of breaking into data, top job priority, gender, age, country, education, ethnicity |

> Data source: Data Professional Survey. *[Power BI - Final Project.xlsx](https://github.com/user-attachments/files/33821901/Power.BI.-.Final.Project.xlsx)
*

## Data Preparation

- Loaded the Excel survey data into Power BI
- Cleaned free-text answers (such as "Other (Please Specify)" job titles, languages and countries) into usable categories
- Created an **Average Salary** column that converts salary ranges (for example "41k-65k") into a numeric value for aggregation
- Built measures for respondent counts and average satisfaction scores
- Designed a single-page layout (1920 × 1080) with a title banner, KPI cards and chart grid

## Skills Demonstrated

| Area | Details |
|------|---------|
| **Data cleaning** | Standardizing free-text survey responses, handling "Other" categories |
| **Data modeling** | Calculated columns and measures for salary and counts |
| **Visualization** | Bar, column, treemap, donut and gauge charts, KPI cards |
| **Dashboard design** | Single-page layout with a clear visual hierarchy |
| **Survey analysis** | Segmenting responses by role, country and satisfaction |

## Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows)

### Open the dashboard
1. Download `PowerBI_Final_Project_DashBoard.pbix` and `Power BI - Final Project.xlsx`
2. Open the `.pbix` file in Power BI Desktop
3. If prompted, go to **Transform data → Data source settings** and point the data source to your local copy of the Excel file

## Project Structure

```
├── PowerBI_Final_Project_DashBoard.pbix   # Power BI dashboard
├── Power BI - Final Project.xlsx          # Survey dataset
├── images/
│   └── dashboard.png                      # Dashboard screenshot
└── README.md
```

## Next Steps

- Add slicers so viewers can filter by country, role or gender
- Add a second page for salary analysis by industry and education
- Add tooltips and a satisfaction comparison across all six categories
- Publish to Power BI Service and add a live link here

## Contact

Ali Eldin Mohamed · [LinkedIn](https://www.linkedin.com/in/alieldin190) · alyshaker2004@gmail.com
