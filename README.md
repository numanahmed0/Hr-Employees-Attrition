# Hr-Employees-Attrition
# HR-Analytics-Dashboard

## 1. Project Title / Headline
👥 HR Analytics Dashboard: Employee Attrition & Workforce Insights
A dynamic, interactive data visualization tool built to explore employee demographics, job satisfaction, and turnover patterns—focusing on departmental attrition, age group distribution, educational backgrounds, and role-specific retention drivers[cite: 1].

---

## 2. Short Description / Purpose
The HR Analytics Dashboard is a visually engaging and analytical Power BI report designed to help users explore and evaluate workforce trends across 1,470 employees[cite: 1]. The dashboard focuses on highlighting major attrition drivers such as department, age bracket, gender, education level, and job satisfaction ratings[cite: 1]. This tool is intended for use by HR professionals, department heads, organizational leaders, and people-analytics strategists who seek to understand turnover trends and improve employee retention[cite: 1].

---

## 3. Tech Stack
The dashboard was built using the following tools and technologies:<br>
• 📊 Power BI Desktop – Main data visualization platform used for report creation and custom purple-themed UI design[cite: 1, 3].<br>
• 📂 Power Query – Data transformation and cleaning layer for reshaping data, creating age brackets, and formatting attributes[cite: 1, 3].<br>
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures (Attrition Rate, Active Employees, Average Age), dynamic visuals, and conditional formatting[cite: 1, 3].<br>
• 📝 Data Modeling – Structured HR dataset schema enabling dynamic cross-filtering across demographics, job roles, and education slicers[cite: 1, 3].<br>
• 📁 File Format – `.pbix` for development and `.png` / `.jpg` for dashboard previews[cite: 1, 3].

---

## 4. Data Source
Source: IBM HR Analytics Employee Attrition & Performance Dataset (1,470 employee records)[cite: 1].

Data on 1,470 employees across three core departments (R&D, Sales, and HR), including details on employee age, gender, education level, education field, job role, job satisfaction scores (1–4 scale), and attrition status[cite: 1].

---

## 5. Features / Highlights

• **Business Problem**
High employee turnover creates significant recruitment, onboarding, and productivity costs, yet HR teams and managers often lack an intuitive way to pinpoint where and why attrition occurs across the workforce.

Key questions such as:
- Which departments and education fields experience the highest employee turnover?
- How does attrition vary across different age groups and genders?
- Which job roles have the lowest or highest job satisfaction ratings?
… are difficult to answer quickly with raw HR spreadsheets.

• **Goal of the Dashboard**
To deliver an interactive visual tool that:
- Enables HR leaders to monitor key workforce KPIs and attrition rates in real time[cite: 1].
- Supports data-driven retention strategies, targeted employee engagement, and workforce planning.
- Uncovers demographic, departmental, and role-level patterns driving employee departures[cite: 1].

• **Walkthrough of Key Visuals**
- **Key KPIs (Top Banner)**[cite: 1]
  - Overall Employees: `1.47K` (`1,470`)[cite: 1]
  - Attrition: `237`[cite: 1]
  - Attrition Rate: `16.12%`[cite: 1]
  - Active Employees: `1K` (`1,233`)[cite: 1]
  - Average Age: `37`[cite: 1]
- **Education Level Filter Panel (Top Right Slicers)**[cite: 1]
  - Interactive tile slicers let users filter all visuals by education qualification: *Associates Degree, Bachelor's Degree, Doctoral Degree, High School,* and *Master's Degree*[cite: 1].
- **Department-Wise Attrition (Pie Chart)**[cite: 1]
  - Breaks down the `237` total departures across departments: **R&D** (`133` / `56.12%`), **Sales** (`92` / `38.82%`), and **HR** (`12` / `5.06%`)[cite: 1].
- **No. of Employees by Age Group (Stacked Column Chart)**[cite: 1]
  - Displays Male vs. Female employee headcount across five age brackets (*Under 25, 25–34, 35–44, 45–54,* and *Over 55*), showing peak workforce concentration in the **25–34** (`337` Male, `217` Female) and **35–44** (`309` Male, `196` Female) cohorts[cite: 1].
- **Job Satisfaction Rating (Conditional Matrix Table)**[cite: 1]
  - Evaluates satisfaction ratings (`1` to `4`) across job roles (*Sales Executive, Research Scientist, Manufacturing Director, Manager, Sales Representative, Research Director*) with color-coded intensity highlighting high-headcount roles like **Sales Executive** (`326` total) and **Research Scientist** (`292` total)[cite: 1].
- **Education Field-Wise Attrition (Horizontal Bar Chart)**[cite: 1]
  - Ranks attrition counts across academic fields: *Life Sciences (`89`), Medical (`63`), Marketing (`35`), Technical Degree (`32`), Other (`11`),* and *Human Resources (`7`)*[cite: 1].
- **Attrition Rate by Gender for Different Age Groups (Donut Chart Series)**[cite: 1]
  - Five segmented donut charts comparing Male vs. Female attrition counts and percentages within each age bracket, highlighting that the **25–34** age group accounts for the highest volume of attrition (`112` employees: `61.61%` Male, `38.39%` Female)[cite: 1].

• **Business Impact & Insights**
- **Targeted Departmental Retention:** R&D (`56.12%`) and Sales (`38.82%`) generate nearly **95% of all company attrition**, signaling an urgent need for workload, career-growth, and compensation reviews in these two divisions[cite: 1].
- **Early-Career Retention Focus:** Nearly half of all departures occur in the **25–34 age group** (`112` out of `237`), allowing HR to design targeted mentorship and career-progression programs for early-to-mid career staff[cite: 1].
- **Gender & Demographic Strategy:** Male employees represent a higher share of attrition across age cohorts—particularly in the **35–44** (`72.55%`) and **25–34** (`61.61%`) brackets—helping leadership tailor engagement initiatives[cite: 1].
- **Role-Specific Engagement:** Tracking satisfaction scores across high-population roles like **Sales Executives** and **Research Scientists** enables managers to proactively address dissatisfaction before it leads to turnover[cite: 1].

---

## 6. Screenshots / Demos
![Dashboard Preview](https://github.com/your-username/HR-Analytics-Dashboard/blob/main/Screenshot%202026-11-16%20103409.jpg)
*(Note: Update `your-username` with your actual GitHub username and ensure the image filename matches your uploaded screenshot)*
