# wuzzuf-egypt-job-market-analysis
Egyptian job market analysis using WUZZUF data, Power BI, Power Query, and DAX — exploring job demand, companies, experience levels, skills, categories, and geographic distribution.
# WUZZUF Job Market Analysis — Egypt 2026

## Project Overview

This project presents a data-driven analysis of the Egyptian job market as reflected on **WUZZUF**, focusing on hiring demand, companies, job categories, experience requirements, required skills, employment types, and geographic distribution.

The project transforms raw job-posting data into an interactive **Power BI dashboard** and a detailed analytical report designed to turn market data into practical business insights.

### Key Dataset Metrics

| Metric | Value |
|---|---:|
| Raw Job Postings | **4,380** |
| Final Analyzable Jobs | **4,371** |
| Companies | **1,533** |
| Analytical Job Categories | **15** |
| Average Minimum Experience | **0 Years** |
| Average Maximum Experience | **4.90 Years** |
| Average Skills per Job | **16** |

The analysis focuses on questions such as:

- Where is hiring demand concentrated?
- Which job categories have the highest number of openings?
- Which skills appear most frequently within each category?
- How do experience requirements differ across functions?
- Which companies have the highest visible posting activity?
- Where are job opportunities geographically concentrated?
- Which roles show greater flexibility in work mode?
- What practical actions can HR teams and companies derive from the observed patterns?

---

## Project Workflow

```text
Raw WUZZUF Job Data
        ↓
Data Collection & Preparation
        ↓
Data Cleaning
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
Detailed Analytical Report
```

---

## Dataset & Data Preparation

The original dataset contained **4,380 WUZZUF job postings** collected through web scraping using **Selenium**.

After data cleaning and preparation, the final dataset contains:

- **4,371 analyzable jobs**
- **1,533 companies**
- **15 analytical job categories**

### Data Preparation

The preparation process included:

- Handling missing values
- Removing duplicate records
- Reviewing and handling outliers
- Standardizing data types
- Creating calculated columns
- Creating DAX measures
- Preparing experience-level classifications
- Preparing job categories for analysis
- Structuring the data for interactive Power BI reporting

### Analytical Note

The dataset contains **15 analytical job categories** used in the Jobs analysis.

The Companies Analysis section uses a separate **14-category grouping** because of the underlying classification/tagging structure. These two views are intentionally treated as different analytical frameworks rather than being forced into one classification.

---

# Power BI Dashboard

The dashboard was designed as an interactive analysis tool rather than a collection of static charts.

It is organized into the following main pages:

1. **Home**
2. **Overview**
3. **Companies Analysis**
4. **Jobs**
5. **Location Analysis**
6. **About**

The dashboard file itself is **not included in this repository**. The complete dashboard can be viewed through the YouTube demo linked below.

---

# 01 — Overview

### Purpose

The Overview page provides a high-level snapshot of the analyzed job market and establishes the main KPIs used throughout the project.

### Key Questions

- How many jobs are available?
- How many companies are hiring?
- What is the average minimum experience required?
- What is the average maximum experience required?
- How many skills are requested per job?
- Which cities contain the highest number of opportunities?
- How are experience requirements distributed?

### Main KPIs

- **Total Jobs:** 4,371
- **Companies:** 1,533
- **Average Minimum Experience:** 0 Years
- **Average Maximum Experience:** 4.90 Years
- **Average Skills per Job:** 16

### Business Interpretation

The dashboard provides a market-level baseline that can be used to compare hiring demand across functions, experience requirements, skills, companies, and locations.

The experience measures describe requirements stated in job postings and should not be interpreted as candidate outcomes or hiring success.

---

# 02 — Companies Analysis

### Purpose

This page examines employer-level hiring activity and connects company posting volume with job levels, experience requirements, and requested skills.

### Key Questions

- Which companies have the highest visible number of job openings?
- Which companies are hiring across different experience levels?
- What skills are associated with a company's vacancies?
- Which employers show junior-level opportunities?
- How do hiring requirements vary by company and role?

### Top Companies by Visible Job Openings

| Company | Jobs |
|---|---:|
| Confidential | **585** |
| Mishkat Nour | **39** |
| Expand Cart | **35** |
| EGIC | **34** |
| Aqarmap.com | **25** |

### Companies with Junior-Level Opportunities

Examples visible in the dashboard include:

- Aqarmap.com — 19 jobs
- Majorel Egypt — 12 jobs
- EGIC — 11 jobs
- Mass Food Group / Kellogg's Company — 2 jobs

### Companies Open to Fresh Graduates / No Experience

Examples visible in the dashboard include:

- Google — 5
- Leadintop — 5
- AIESEC - MANSOURA — 4
- AIESEC Cairo University — 3
- Innovera for Education Technology — 3

### Business Interpretation

Company posting volume should not be treated as a direct measure of employer size or hiring success.

A more useful comparison is:

**Company × Job Function × Experience × Skills**

The large **Confidential** segment also means that some employer-level benchmarking is naturally limited because the actual company identity is hidden in the source data.

---

# 03 — Jobs Analysis

### Purpose

The Jobs page provides a detailed exploration of job categories, required experience, skills, employment types, job titles, and other job-level characteristics.

The analysis contains **15 job categories**.

Each category is examined through:

- Total jobs
- Minimum required experience
- Maximum required experience
- Average skills per job
- Most frequently requested skills
- Experience-level distribution
- Employment type
- Sample job titles
- Business interpretation
- Recommended actions

---

## Accounting & Finance

**314 jobs**

- Minimum experience: **3.88 years**
- Maximum experience: **5.86 years**
- Average skills per job: **24.87**
- Top skill: **Financial Analysis — 145 jobs**

### Key Insight

Financial Analysis appears in approximately 46% of jobs in this category, while the category also has one of the highest average skill counts in the dataset.

### Business Implication

Finance roles frequently combine accounting or financial responsibilities with analytical requirements.

### Recommended Actions

- Separate must-have financial qualifications from desirable analytical skills.
- Make finance-analysis responsibilities explicit in job descriptions.
- Use practical assessments where analytical capability is important.

---

## Administration & Office Support

**229 jobs**

- Minimum experience: **2.97 years**
- Maximum experience: **4.80 years**
- Average skills per job: **14.29**

### Key Insight

The category is dominated by broad Administration-related requirements and shows relatively balanced demand between experienced and entry-level positions.

### Recommended Actions

- Describe the actual administrative tasks and systems involved.
- Specify coordination, communication, reporting, or office-management responsibilities.
- Use clearer role definitions to improve candidate targeting.

---

## Customer Service & Support

**135 jobs**

- Minimum experience: **1.51 years**
- Maximum experience: **3.18 years**

### Key Insight

Entry-Level positions represent the largest experience-level group in this category, with **76 jobs**.

### Recommended Actions

- Build scalable junior recruitment pipelines.
- Use structured customer-service assessments.
- Define clear progression paths from junior support roles to more experienced positions.

---

## Design & Creative

**161 jobs**

- Minimum experience: **2.36 years**
- Maximum experience: **3.80 years**
- Average skills per job: **22.93**

### Key Insight

Adobe Illustrator is the most frequently requested skill, appearing in **71 jobs**. Traditional graphic-design requirements are more visible than specialized UI/UX requirements.

### Recommended Actions

- Separate Graphic Design, UI, UX, and Web Design roles clearly.
- Specify the required tools and portfolio expectations.
- Use project-based or flexible work models where operationally suitable.

---

## Education

**94 jobs**

- Minimum experience: **1.88 years**
- Maximum experience: **3.37 years**
- Average skills per job: **10.87**

### Key Insight

Part-Time opportunities represent approximately **21%** of this category.

### Recommended Actions

- Use part-time models where the role allows it.
- Clearly distinguish teaching, training, and educational-content roles.
- Consider graduate-entry and instructor development pipelines.

---

## Engineering

**358 jobs**

- Minimum experience: **3.42 years**
- Maximum experience: **5.35 years**
- Average skills per job: **13.77**

### Key Insight

Mechanical Engineering, AutoCAD, and Microsoft Office are among the most requested skills.

### Recommended Actions

- Build graduate and trainee pathways alongside experienced hiring.
- Use practical screening for technical roles.
- Clearly distinguish site-based and office-based engineering positions.

---

## Human Resources

**155 jobs**

- Minimum experience: **3.22 years**
- Maximum experience: **4.72 years**
- Average skills per job: **17.45**

### Key Insight

Recruitment and Personnel are the most frequently appearing HR-related skill areas.

### Recommended Actions

- Separate Recruitment, Personnel, Talent Acquisition, and HR Operations requirements.
- Define the expected HR systems and processes.
- Avoid overly broad HR job titles when the role is specialized.

---

## IT & Software

**617 jobs**

- Minimum experience: **3.09 years**
- Maximum experience: **4.57 years**
- Average skills per job: **18.73**

### Top Skills

- Software Development — **119**
- Computer Science — **115**
- Information Technology — **78**
- Software Engineering — **46**
- Web Development — **15**

### Key Insight

IT & Software is one of the largest hiring categories in the dataset and has the highest number of Work From Home opportunities, with **28 jobs**.

### Recommended Actions

- Specify the technology stack and technical responsibilities.
- Build internship and junior hiring pipelines.
- Use remote or hybrid models where the role can support them.
- Align screening with the actual technical requirements of each role.

---

## Legal

**18 jobs**

- Minimum experience: **4.01 years**
- Maximum experience: **6.22 years**
- Average skills per job: **8.08**

### Key Insight

Legal is the smallest category in the dataset and has relatively high experience requirements.

Because of the small sample size, conclusions about the wider legal market should be treated cautiously.

### Recommended Actions

- Use targeted sourcing for specialized legal roles.
- Clearly define the required legal specialization and responsibilities.
- Avoid generalizing from this small category to the entire legal market.

---

## Logistics & Supply Chain

**124 jobs**

- Minimum experience: **4.06 years**
- Maximum experience: **6.33 years**
- Average skills per job: **17.15**

### Key Insight

All **124 jobs** in this category are full-time positions.

### Recommended Actions

- Make location and shift requirements explicit.
- Use hybrid models selectively for planning, analytics, and suitable office-based roles.
- Consider internal promotion pathways for experienced operational talent.

---

## Management & Leadership

**348 jobs**

- Minimum experience: **6.57 years**
- Maximum experience: **8.59 years**
- Average skills per job: **11.24**

### Key Insight

Manager-level positions account for **280 jobs**, making this category strongly concentrated around leadership roles.

This category also has the highest observed experience requirements in the dataset.

### Recommended Actions

- Define measurable leadership competencies.
- Strengthen internal leadership-development programs.
- Build promotion pathways before relying entirely on external management hiring.

---

## Marketing & Media

**330 jobs**

- Minimum experience: **2.86 years**
- Maximum experience: **4.61 years**
- Average skills per job: **21.40**

### Top Skills

- Social Media — **91**
- E-marketing — **79**
- Marketing/PR/Advertising — **38**
- Writing/Editorial — **31**
- Digital Marketing — **9**

### Key Insight

Specific execution areas such as Social Media and E-marketing appear more frequently than the broad Digital Marketing label.

### Recommended Actions

- Define the exact marketing discipline required.
- Separate content, social media, paid advertising, e-marketing, and broader marketing roles.
- Consider flexible work models for digitally deliverable responsibilities.

---

## Medical & Healthcare

**55 jobs**

- Minimum experience: **3.74 years**
- Maximum experience: **5.92 years**
- Average skills per job: **14.50**

### Key Insight

Sales Target is the most frequently appearing skill, with **13 jobs**, indicating that part of the observed healthcare demand has a commercial or medical-sales component.

### Recommended Actions

- Clearly distinguish clinical and commercial healthcare roles.
- Specify product, territory, customer type, and target responsibilities where applicable.
- Consider graduate-entry pathways for suitable medical-sales positions.

---

## Other

**574 jobs**

### Key Insight

The Other category represents approximately **13%** of the analyzed market.

However, this is a heterogeneous category containing roles that do not clearly fit into the main classifications.

Top observed skills include:

- Administration — **44**
- Computer Science — **24**
- Pharmaceutical — **18**
- Social Media — **14**
- Science — **12**

### Business Interpretation

The size of the Other category should be treated as a **classification signal**, not as evidence that “Other” is one functional department.

### Recommended Actions

- Review job titles and descriptions to identify the actual function.
- Avoid direct benchmarking between Other and clearly defined categories.
- Break the category into functional subgroups in future versions of the analysis.

---

## Sales & Business Development

**859 jobs**

- Minimum experience: **2.42 years**
- Maximum experience: **4.15 years**
- Average skills per job: **23.51**

### Top Skills

- Sales Target — **379**
- Sales/Retail — **198**
- Business Development — **66**
- Sales Skills — **53**
- Customer Service — **39**

### Key Insight

Sales & Business Development is the largest observed job category, representing approximately **20%** of the analyzed postings.

The category recruits across multiple experience bands rather than being limited to one experience level.

### Recommended Actions

- Build scalable sales recruitment funnels.
- Use standardized, role-specific screening criteria.
- Define clear junior-to-senior progression paths.
- Separate field sales, retail, business development, and customer-facing roles where appropriate.

---

# 04 — Location Analysis

### Purpose

The Location Analysis page examines where job opportunities are concentrated and how geography relates to experience and job demand.

### Key Questions

- Where are most jobs located?
- Which Egyptian cities have the highest number of opportunities?
- Which foreign countries appear in the dataset?
- How concentrated is the market geographically?
- Where do remote opportunities appear?

### Main Findings

- Approximately **90%** of postings target job seekers inside Egypt.
- **Cairo** is the dominant location, with **2,784 jobs** in the analyzed dataset.
- **Saudi Arabia** is the leading foreign country with **51 jobs**.
- **Oman** follows with **6 jobs**.
- Other countries generally appear with only a small number of postings.
- Remote opportunities represent a relatively small share of the overall market.

### Business Interpretation

The strong concentration around Cairo suggests that companies may reach a broader talent pool by considering hybrid, remote, or relocation-supported models where operationally feasible.

---

# 05 — About the Dashboard

The About page provides the project context, purpose, and dashboard information.

### Project

**WUZZUF Job Market Analysis — Egypt 2026**

### Data Source

**WUZZUF job postings**

### Data Collection

**Web Scraping using Selenium**

### Data Preparation

**Power Query**

### Analysis & Visualization

**Power BI + DAX**

### Final Dataset

- **4,371 jobs**
- **1,533 companies**
- **15 analytical job categories**

### Dashboard Pages

- Home
- Overview
- Companies Analysis
- Jobs
- Location Analysis
- About

### Project Objective

To transform job-posting data into an interactive analytical tool that helps users understand:

- Hiring demand
- Job categories
- Experience requirements
- Required skills
- Companies and posting activity
- Employment types
- Geographic distribution

### Analytical Scope

The dashboard represents the **observed WUZZUF postings in the collected dataset**. It should therefore be interpreted as a snapshot of the platform’s visible job-posting activity during the collection period, not as a complete representation of the entire Egyptian labor market.

---

# Key Market Findings

## 1. Sales & Business Development is the largest observed category

With **859 jobs**, Sales & Business Development represents approximately **20%** of the analyzed postings.

## 2. Experience requirements vary significantly by function

Management & Leadership, Legal, and Logistics & Supply Chain show relatively high experience requirements, while Customer Service & Support and Education show lower observed requirements.

## 3. Cairo dominates geographic demand

Cairo contains the largest concentration of visible opportunities in the dataset, with **2,784 jobs**.

## 4. IT & Software is a major hiring category

IT & Software contains **617 jobs** and also shows the highest number of Work From Home opportunities among the analyzed categories.

## 5. Skill requirements are highly category-specific

The most frequently requested skills differ substantially between functions, supporting the need for category-specific recruitment and job-description strategies.

## 6. The Other category requires careful interpretation

With **574 jobs**, Other is large enough to affect overall market comparisons, but its heterogeneous composition means it should not be treated as a single functional department.

## 7. Company-level comparisons require context

Posting volume alone does not measure company size, hiring success, or employer competitiveness. Company comparisons become more meaningful when combined with function, experience, and skill requirements.

---

# Business Recommendations

### For Companies

- Use clearer and more specific job descriptions.
- Prioritize truly required skills instead of unnecessarily long skill lists.
- Build graduate and internship pipelines for suitable roles.
- Consider hybrid and remote work where operationally feasible.
- Expand geographic sourcing beyond Cairo where the role allows it.
- Track hiring-market KPIs periodically instead of relying on one-time observations.

### For HR Teams

- Benchmark competitors by **job family**, not total posting volume alone.
- Use structured experience requirements to improve candidate targeting.
- Apply practical skill assessments to technical and skill-heavy positions.
- Define clear progression paths for junior and experienced employees.
- Separate specialized roles that are currently grouped under broad job titles.

### Recommended Market KPIs for Future Analysis

- Salary ranges by category and experience level
- Posting age and time-to-fill
- Application volume
- Applicant-to-interview conversion
- Skill combinations rather than individual skill frequency only
- Remote/hybrid availability by city and function
- Monthly or quarterly changes in hiring demand

---

# Methodology & Analytical Limitations

The project is based on observed job postings and therefore has several analytical boundaries.

- The dataset represents WUZZUF postings collected during the project period, not the entire Egyptian labor market.
- Skill frequency shows how often a skill appears in postings; it does not prove that the skill causes hiring success.
- Experience requirements describe advertised vacancies, not the actual experience of successful candidates.
- Work-mode fields describe the advertised arrangement, not the final employment arrangement.
- Category volume may be affected by WUZZUF’s taxonomy and posting behavior.
- The **Other** category is heterogeneous and should not be interpreted as one functional department.
- Company-level conclusions are limited when employer identity is listed as **Confidential**.
- The analysis does not include salary, application volume, interview outcomes, time-to-hire, or hiring-success data.

These limitations are important when translating dashboard observations into business decisions.

---

# Tools & Technologies

### Data Collection

- Selenium
- Web Scraping

### Data Preparation

- Power Query
- Data Cleaning
- Data Transformation

### Analysis & Visualization

- Power BI
- DAX
- KPI Analysis
- Interactive Dashboard
- Business Analysis

---

# Project Resources

## Power BI Dashboard

The `.pbix` dashboard file is **not included in the repository**.

The complete interactive dashboard can be explored through the project demo below.

## YouTube Dashboard Demo

A complete walkthrough of the Power BI dashboard and its analysis:

> **Add YouTube Demo Link Here**

`[YouTube Demo Link]`

## Full Analytical Report

The detailed English report contains the methodology, limitations, category-by-category analysis, business insights, recommendations, and strategic action plan.

**Google Drive Report:**

https://drive.google.com/file/d/1yajk_7Jizz4iHU6-AmYcSc87E5goOqjH/view?usp=sharing

---

# Dashboard Screenshots

Dashboard screenshots are included below to provide a visual preview of the interactive report.

The interactive dashboard itself is available through the YouTube demo.

<img width="1203" height="682" alt="image" src="https://github.com/user-attachments/assets/eccbb624-8e47-4062-b93e-3bdb0abd0099" />

<img width="1203" height="640" alt="image" src="https://github.com/user-attachments/assets/3b260d84-5edc-48e0-9b25-35ddc8a6ac38" />

<img width="1207" height="676" alt="image" src="https://github.com/user-attachments/assets/977f6f14-2f32-4284-aa22-d564ed434362" />

<img width="1209" height="685" alt="image" src="https://github.com/user-attachments/assets/8fda4cae-8b3c-4722-b522-7d0acefe345b" />

<img width="1203" height="684" alt="image" src="https://github.com/user-attachments/assets/42c0265e-5038-4d4f-ac39-c78e7ef04336" />

---

# Final Note

This project demonstrates an end-to-end **Data Analysis workflow**, starting from raw job-market data and ending with an interactive Power BI dashboard and business-focused analytical report.

The project focuses on transforming job-posting data into practical insights about:

**Hiring Demand | Experience Requirements | Skills | Companies | Job Categories | Employment Types | Geographic Distribution**

**Prepared by Habiba Ahmed Talaat**

**Power BI | Power Query | DAX | Data Analysis**

**September 2026**
