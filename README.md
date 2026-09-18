# wuzzuf-egypt-job-market-analysis
Egyptian job market analysis using WUZZUF data, Power BI, Power Query, and DAX — exploring job demand, companies, experience levels, skills, categories, and geographic distribution.
# WUZZUF Job Market Analysis — Egypt 2026

## Project Overview

This project provides a data-driven analysis of the Egyptian job market as reflected on **WUZZUF**, focusing on job demand, companies, experience levels, required skills, job categories, and geographic distribution.

The analysis is based on **4,380 scraped job postings**. After data cleaning and preparation, the final analyzable dataset contains:

* **4,371 jobs**
* **1,533 companies**
* **15 job categories**
* Multiple experience-level and employment-type indicators

The project combines **Power Query, Power BI, and DAX** to transform raw job-posting data into an interactive dashboard and a detailed analytical report.

The goal is not only to visualize the data, but to understand **where opportunities are concentrated, what skills employers are requesting, what experience levels are most demanded, and how companies can use these insights to improve their hiring strategy.**

---

## Project Workflow

```text
Raw WUZZUF Job Data
        ↓
Data Cleaning & Preparation
        ↓
Power Query Transformation
        ↓
Calculated Columns & DAX Measures
        ↓
Exploratory Analysis
        ↓
Power BI Dashboard
        ↓
Business Insights & Recommendations
        ↓
Analytical Report
```



---

## Dataset

The original dataset contained **4,380 job postings** collected through web scraping using Selenium.

After cleaning and preparation:

| Metric                      |      Value |
| --------------------------- | ---------: |
| Original Job Postings       |      4,380 |
| Final Analyzable Jobs       |      4,371 |
| Companies                   |      1,533 |
| Primary Categories          |         14 |
| Job Analysis Sub-Categories |         15 |
| Average Minimum Experience  |    0 Years |
| Average Maximum Experience  | 4.90 Years |
| Average Skills per Job      |         16 |

### Data Preparation

The cleaning process included:

* Handling missing values
* Handling duplicate records
* Handling outliers
* Unifying data types
* Creating calculated columns
* Creating DAX measures
* Preparing experience-level classifications
* Preparing categories for dashboard analysis

---

# Dashboard

The Power BI dashboard was designed to answer practical questions about the Egyptian job market rather than simply display charts.

## 01 — Overview

### Purpose

The Overview section provides a high-level snapshot of the job market and establishes the main KPIs used throughout the analysis.

### Key Questions

* How many jobs are available?
* How many companies are hiring?
* What is the average required experience?
* How many skills are employers requesting per job?
* What does the overall job market look like?

### Main KPIs

* Total Jobs: **4,371**
* Companies: **1,533**
* Average Minimum Experience: **0 Years**
* Average Maximum Experience: **4.90 Years**
* Average Skills per Job: **16**

### Dashboard Screenshot

---

# 02 — Company & Experience-Level Analysis

### Purpose

This section explores hiring activity across companies and examines the distribution of experience-level tags.

### Key Questions

* Which companies have the highest number of job openings?
* How much demand exists for Experienced candidates?
* How much demand exists for Entry-Level candidates?
* Which companies are hiring for Junior positions?
* Which companies are open to Fresh Graduates / No Experience?
* How common are remote and flexible opportunities?

### Experience-Level Tags

| Experience / Employment Tag |  Jobs |
| --------------------------- | ----: |
| Experienced                 | 2,193 |
| Entry Level                 | 1,137 |
| Manager                     |   737 |
| Work From Home              |   102 |
| Part Time                   |    74 |
| Shift Based                 |    47 |
| Senior Management           |    37 |
| Freelance / Project         |    32 |
| Student                     |    14 |

**Important:** Each `Job_Key` is counted once within each experience-level tag. A single job can carry more than one tag, so these figures represent **level-specific job counts rather than unique-job totals**.

### Top Companies by Job Openings

| Company      | Jobs |
| ------------ | ---: |
| Confidential |  585 |
| Mishkat Nour |   39 |
| Expand Cart  |   35 |
| EGIC         |   34 |
| Aqarmap.com  |   25 |

### Companies Hiring Most for Junior Level

* Aqarmap.com — 19 jobs
* Majorel Egypt — 12 jobs
* EGIC — 11 jobs
* Mass Food Group / Kellogg's Company — 2 jobs

### Companies Open to Fresh Graduates / No Experience

* Google — 5
* Leadintop — 5
* AIESEC - MANSOURA — 4
* AIESEC Cairo University — 3
* Innovera for Education Technology — 3

---

# 03 — Geographic Distribution

### Purpose

This section analyzes where available jobs are geographically concentrated.

### Key Questions

* What percentage of jobs target candidates inside Egypt?
* Which foreign countries have available opportunities?
* Which Egyptian governorates have the highest number of jobs?
* How significant are remote opportunities?

### Main Findings

* Approximately **90%** of postings target job seekers inside Egypt.
* **Cairo** accounts for approximately **90%** of available jobs, with **2,784 jobs**.
* Saudi Arabia is the leading foreign country with **51 jobs**.
* Oman follows with **6 jobs**.
* Other countries generally have between **2 and 4 jobs**.
* Remote opportunities represent a very small share of the total market.



---

# 04 — Jobs by Category

The Jobs Analysis section contains **15 job categories**, allowing the market to be analyzed individually rather than treating all jobs as one group.

Each category is examined through:

* Total available jobs
* Minimum required experience
* Maximum required experience
* Average skills per job
* Most requested skills
* Experience-level distribution
* Employment type
* Sample job titles
* Analytical insights
* Recommendations

---

## Accounting & Finance

**314 jobs**

* Minimum experience: 3.88 years
* Maximum experience: 5.86 years
* Average skills per job: 24.87
* Top skill: Financial Analysis — 145 jobs

### Key Insight

Financial Analysis appears in approximately 46% of jobs in this category, while the category also has one of the highest average skill counts in the dataset.



---

## Administration & Office Support

**229 jobs**

* Minimum experience: 2.97 years
* Maximum experience: 4.80 years
* Average skills per job: 14.29

The category shows a relatively balanced demand between Experienced and Entry-Level positions.



---

## Customer Service & Support

**135 jobs**

* Minimum experience: 1.51 years
* Maximum experience: 3.18 years

Entry-Level jobs represent the largest experience-level group in this category, with **76 jobs**.



---

## Design & Creative

**161 jobs**

* Minimum experience: 2.36 years
* Maximum experience: 3.80 years
* Average skills per job: 22.93

Adobe Illustrator is the most frequently requested skill, appearing in **71 jobs**.



---

## Education

**94 jobs**

* Minimum experience: 1.88 years
* Maximum experience: 3.37 years
* Average skills per job: 10.87

Part-Time opportunities represent approximately **21%** of this category.



---

## Engineering

**358 jobs**

* Minimum experience: 3.42 years
* Maximum experience: 5.35 years
* Average skills per job: 13.77

Mechanical Engineering, AutoCAD, and Microsoft Office are among the most requested skills.


---

## Human Resources

**155 jobs**

* Minimum experience: 3.22 years
* Maximum experience: 4.72 years
* Average skills per job: 17.45

Recruitment and Personnel represent the most frequently requested HR-related skills.


---

## IT & Software

**617 jobs**

* Minimum experience: 3.09 years
* Maximum experience: 4.57 years
* Average skills per job: 18.73

Top skills include:

* Software Development — 119
* Computer Science — 115
* Information Technology — 78
* Software Engineering — 46
* Web Development — 15

IT & Software is the largest category in the dataset and also contains the highest number of Work From Home opportunities, with **28 jobs**.


---

## Legal

**18 jobs**

* Minimum experience: 4.01 years
* Maximum experience: 6.22 years
* Average skills per job: 8.08

Legal is the smallest category in the dataset and has relatively high experience requirements.



---

## Logistics & Supply Chain

**124 jobs**

* Minimum experience: 4.06 years
* Maximum experience: 6.33 years
* Average skills per job: 17.15

All **124 jobs** in this category are full-time positions.



---

## Management & Leadership

**348 jobs**

* Minimum experience: 6.57 years
* Maximum experience: 8.59 years
* Average skills per job: 11.24

Manager-level positions account for **280 jobs**, making this category strongly concentrated around management roles.



---

## Marketing & Media

**330 jobs**

* Minimum experience: 2.86 years
* Maximum experience: 4.61 years
* Average skills per job: 21.40

The most frequently requested skills include:

* Social Media — 91
* E-marketing — 79
* Marketing/PR/Advertising — 38
* Writing/Editorial — 31
* Digital Marketing — 9


---

## Medical & Healthcare

**55 jobs**

* Minimum experience: 3.74 years
* Maximum experience: 5.92 years
* Average skills per job: 14.50

Sales Target is the most frequently appearing skill, with **13 jobs**.


---

## Other

**574 jobs**

The Other category represents approximately **13% of the market**, containing roles that do not clearly fit into one of the main classifications.

### Key Insight

The size of this category highlights the importance of considering job-title classification when interpreting market data.


---

## Sales & Business Development

**859 jobs**

* Minimum experience: 2.42 years
* Maximum experience: 4.15 years
* Average skills per job: 23.51

Top requested skills:

* Sales Target — 379
* Sales/Retail — 198
* Business Development — 66
* Sales Skills — 53
* Customer Service — 39

The category contains **859 jobs**, representing approximately **20%** of the available postings in the dataset.


---

# Key Market Findings

Across the dashboard analysis, several patterns stand out:

### 1. Sales represents a major share of hiring demand

Sales & Business Development contains **859 jobs**, approximately 20% of the analyzed market.

### 2. Experienced hiring exceeds Entry-Level demand

The corrected experience-tag counts show:

**Experienced: 2,193**

vs.

**Entry Level: 1,137**

This represents a gap of approximately **1.9 times**.

### 3. Cairo dominates geographic demand

Approximately **90%** of available jobs are concentrated in Cairo, creating a strong geographic concentration in the Egyptian market.

### 4. IT & Software is a major hiring category

IT & Software contains **617 jobs** and also has the highest number of Work From Home opportunities among the analyzed categories.

### 5. Company visibility varies significantly

The `Confidential` company label appears in **585 jobs**, making it an important consideration when interpreting company-level market comparisons.

---

# Business Recommendations

Based on the analysis:

### For Companies

* Review job descriptions to ensure required skills are specific and relevant.
* Consider Hybrid and Remote models where the role allows it.
* Improve transparency around company identity when possible.
* Build graduate and internship pipelines for entry-level talent.
* Use category-specific skills when defining job requirements.

### For HR Teams

* Use experience-level data when planning recruitment pipelines.
* Develop dedicated graduate programs rather than relying only on experienced hiring.
* Use practical skill assessments for highly technical or skill-heavy roles.
* Consider geographic flexibility when recruiting outside Cairo.
* Monitor market KPIs periodically to identify changes in hiring demand.

---

# Tools & Technologies

### Data Collection

* Selenium
* Web Scraping

### Data Preparation

* Power Query
* Data Cleaning
* Data Transformation

### Analysis & Visualization

* Power BI
* DAX
* Interactive Dashboard
* KPI Analysis
* Category Analysis

---

# Project Files & Resources

## Power BI Dashboard

---

## YouTube Demo

A complete walkthrough of the dashboard and project analysis:

> **Add YouTube Demo Link Here**

`[YouTube Demo Link]`

---

## Full Analytical Report

The full English analytical report containing the methodology, category analysis, insights, and recommendations:

> **Add Google Drive Report Link Here**

[https://drive.google.com/file/d/1yajk_7Jizz4iHU6-AmYcSc87E5goOqjH/view?usp=sharing]

---

# Dashboard Screenshots

All dashboard screenshots will be stored inside the repository 


# Final Note

This project demonstrates an end-to-end **Data Analysis workflow**, starting from raw job-market data and ending with an interactive Power BI dashboard and business-focused analytical report.

The project focuses on transforming job-posting data into practical insights about **hiring demand, experience requirements, skills, companies, categories, and geographic distribution**.

**Prepared by Habiba Ahmed Talaat**

**Power BI | Power Query | DAX | Data Analysis**

September 2026

<img width="1203" height="682" alt="image" src="https://github.com/user-attachments/assets/eccbb624-8e47-4062-b93e-3bdb0abd0099" />

<img width="1203" height="640" alt="image" src="https://github.com/user-attachments/assets/3b260d84-5edc-48e0-9b25-35ddc8a6ac38" />

<img width="1207" height="676" alt="image" src="https://github.com/user-attachments/assets/977f6f14-2f32-4284-aa22-d564ed434362" />

<img width="1209" height="685" alt="image" src="https://github.com/user-attachments/assets/8fda4cae-8b3c-4722-b522-7d0acefe345b" />

<img width="1203" height="684" alt="image" src="https://github.com/user-attachments/assets/42c0265e-5038-4d4f-ac39-c78e7ef04336" />
