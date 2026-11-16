# 📊 HR Analytics Dashboard — Employee Attrition Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Domain-HR%20Analytics-6A1B9A?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Project Overview
This interactive **HR Analytics Dashboard** built in **Microsoft Power BI** analyzes workforce demographics, job satisfaction, and employee turnover patterns. Designed to help Human Resources teams and organizational leaders identify key drivers of employee attrition, the report transforms raw HR records into actionable retention insights across departments, education backgrounds, age brackets, and job roles.

---

## 📸 Dashboard Preview
![HR Analytics Dashboard](./assets/dashboard_preview.png)
*(Note: Replace the path above with the actual path to your dashboard screenshot in your GitHub repository)*

---

## 🎯 Key Performance Indicators (KPIs)
At a glance, the top-level KPI cards summarize the organization's workforce health:
* **Overall Employees:** `1,470` (1.47K)
* **Total Attrition:** `237` employees
* **Attrition Rate:** `16.12%`
* **Active Employees:** `1,233` (displayed as `1K`)
* **Average Employee Age:** `37` years

---

## 🧩 Dashboard Features & Visual Breakdown

1. **Interactive Education Slicer:**
   * Top-bar tile filters allow dynamic slicing across education levels: *Associates Degree, Bachelor's Degree, Doctoral Degree, High School,* and *Master's Degree*.
2. **Department-Wise Attrition (Pie Chart):**
   * Breaks down total attrition (`237`) across core business units:
     * **R&D:** `133` (`56.12%`)
     * **Sales:** `92` (`38.82%`)
     * **HR:** `12` (`5.06%`)
3. **Employee Distribution by Age Group & Gender (Stacked Column Chart):**
   * Compares Male vs. Female headcount across five age brackets (*Under 25, 25–34, 35–44, 45–54,* and *Over 55*), highlighting a workforce heavily concentrated in the **25–34** (`554` total) and **35–44** (`505` total) age groups.
4. **Job Satisfaction Rating Matrix (Conditional Heat Map):**
   * Evaluates employee satisfaction scores (rated `1` to `4`) across specific job roles (*Sales Executive, Research Scientist, Manufacturing Director, Manager, Sales Representative, Research Director*), using color intensity to spotlight roles with the highest headcount and satisfaction distribution.
5. **Education Field-Wise Attrition (Horizontal Bar Chart):**
   * Tracks turnover across academic disciplines: *Life Sciences (`89`), Medical (`63`), Marketing (`35`), Technical Degree (`32`), Other (`11`),* and *Human Resources (`7`)*.
6. **Attrition by Gender Across Age Groups (Donut Chart Series):**
   * Five segmented donut charts comparing Male vs. Female attrition counts and percentages within each age bracket.

---

## 💡 Key Analytical Insights
* **High-Volume Turnover in R&D and Sales:** Together, Research & Development (`56.12%`) and Sales (`38.82%`) account for **nearly 95% of all employee attrition**, largely driven by their larger workforce sizes.
* **Early-to-Mid Career Vulnerability:** The **25–34 age bracket** experiences the highest total attrition (`112` employees, or **47.3% of all departures**), indicating a critical retention window for early-career professionals.
* **Gender Attrition Trends:** Across all age groups, male employees account for a higher proportion of departures than female employees—most notably in the **35–44** (`72.55%` male vs. `27.45%` female) and **25–34** (`61.61%` male vs. `38.39%` female) cohorts.
* **Academic Background Impact:** Employees from **Life Sciences** (`89`) and **Medical** (`63`) backgrounds represent the largest share of attrition by education field.
* **Role-Specific Satisfaction:** **Sales Executives** (`326` total) and **Research Scientists** (`292` total) represent the largest surveyed groups in the satisfaction matrix, making targeted engagement programs in these two roles high-impact levers for reducing overall turnover.

---

## 🛠️ Tools & Techniques Used
* **Power BI Desktop:** Data modeling, DAX calculations, custom purple-gradient UI theming, and interactive cross-filtering.
* **Power Query:** Data cleaning, column formatting, and conditional grouping (creating age brackets and satisfaction rating buckets).
* **DAX (Data Analysis Expressions):** Custom measures for `Overall Employees`, `Attrition Count`, `Attrition Rate (%)`, `Active Employees`, and `Average Age`.

---

## 🚀 How to Use This Project
1. Clone or download this repository:
   ```bash
   git clone [https://github.com/your-username/hr-analytics-powerbi.git](https://github.com/your-username/hr-analytics-powerbi.git)
