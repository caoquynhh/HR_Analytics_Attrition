# HR Data Analysis: Employee Attrition & Performance

##  1. Project Overview
The "HR Data Analysis in Organization" project aims to comprehensively evaluate the human resource landscape of an enterprise based on a dataset of 1,470 employees. 

With the current attrition rate at an alarming 16.12% (corresponding to 237 departed employees), the project dives deep into Personal Characteristics, Workplace Environment, Income, and Experience to identify root causes and propose effective talent retention strategies.

* **Data source:** [Kaggle - IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
* **Dataset size:** 1470 rows x 35 columns
* **Analytics & Visualization Tools:** Tableau, Microsoft Excel.

## 2. Dashboard Architecture & Key Findings
The analytical system is divided into 4 specialized Dashboards, each addressing a specific HR domain:

### Dashboard 1: General Overview
* **Workforce Structure:** Research & Development (R&D) is the heart of the enterprise, accounting for 65.37% of the total workforce. However, this department also records the highest attrition rate (accounting for 56.12% of total turnover).
* **Personnel Quality:** The organization possesses a strong intellectual foundation, with 38.91% holding a Bachelor's degree and 27.07% holding a Master's degree. Over 70% of the workforce is specialized in Life Sciences and Medical fields. Surprisingly, the Bachelor group is the most volatile (representing 41.77% of total attrition).


![General Overview](<dashboards/preview/001_overview.png>)

### Dashboard 2: Personal Characteristics
* **Attrition Hotspots:** The turnover trend is heavily concentrated in the young workforce (aged 26-35), accounting for 48.95% of departing personnel. The highest-risk group consists of single males within this age bracket.
* **The Geographical Paradox:** Contrary to common expectations, employees living closest to the company (0-5 miles) exhibit the highest attrition rate (36.71%). Notably, single employees living nearby are the most volatile subgroup (21.10%).

![Personal Characteristics](<dashboards/preview/002_personal.png>)

### Dashboard 3: Workplace Environment
* **The Resonance Effect (Overtime & Travel):** When employees face both "Overtime" and "Travel Frequently", the attrition rate skyrockets to 41.86%. This combination amplifies workplace pressure, leading to severe burnout and the intention to leave.
* **The "Time Bomb" Discovery:** Up to 12% of personnel achieve an "Excellent" performance rating while having "Low" Job Involvement. They maintain their output purely out of professional responsibility, but their departure—taking core know-how with them—is only a matter of time.

![Workplace](<dashboards/preview/003_workplace.png>)

### Dashboard 4: Income & Experience
* **Income Distribution:** The income distribution is significantly right-skewed, with over 50.95% of personnel falling into the low-income group (under $5,000). Compa-Ratio analysis highlights that the 5-10 years tenure group with "Below Standard" income is at a critical risk of leaving.
* **Quadrant Matrix Analysis:** Employees were classified into 4 strategic groups. An alarming finding is that 326 employees fall into the "Flight Risk" category—those with high tenure but salary increases lower than the company average, leading to a strong perception of unfairness.

![Income and Experience](<dashboards/preview/004_income_and_experience.png>)
