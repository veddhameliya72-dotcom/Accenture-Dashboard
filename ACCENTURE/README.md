<div align="center">

# 💼 Accenture India – HR & Workforce Analytics Dashboard
### *Power BI Human Resources Analytics & Interactive Dashboard Project*

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Preparation-blue?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-HR%20Analytics-5A1DBB?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-Workforce%20Analysis-24104F?style=for-the-badge)

**Power BI · Accenture India Workforce Dashboard Project**

</div>

---

# 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Objective](#-objective)
- [📦 Data Model](#-data-model)
- [✨ Features](#-features)
- [🏗️ Repository Structure](#️-repository-structure)
- [🗂️ Report Pages](#️-report-pages)
  - [👥 Page 1: Workforce Overview](#-page-1-workforce-overview)
  - [📉 Page 2: Attrition & Retention](#-page-2-attrition--retention)
  - [💰 Page 3: Compensation Analytics](#-page-3-compensation-analytics)
  - [🏅 Page 4: Performance & Promotion](#-page-4-performance--promotion)
  - [📊 Page 5: Executive Summary](#-page-5-executive-summary)
- [🔍 Filters & Slicers](#-filters--slicers)
- [💡 Key Insights](#-key-insights)
- [🎨 Theme & Formatting](#-theme--formatting)
- [🛠️ Tools & Techniques](#️-tools--techniques)
- [🚀 How to Use This Project](#-how-to-use-this-project)
- [🎥 Video Walkthrough](#-video-walkthrough)
- [📈 Learning Outcomes](#-learning-outcomes)
- [👤 Author](#-author)

---

# 📌 Overview

The **Accenture India – HR & Workforce Analytics Dashboard** is a five-page Microsoft Power BI report that presents workforce composition, employee attrition, compensation, performance, promotions and executive-level HR indicators. The dashboard screenshots are dated **30 April 2025**.

The five interactive report pages are:

- 👥 **Workforce Overview:** headcount, active employees, department and city distribution, gender mix and hiring trends.
- 📉 **Attrition & Retention:** exits, retention, employee segments, attrition trends and exit tenure.
- 💰 **Compensation Analytics:** payroll, salary distribution, pay by department, job level, location and gender.
- 🏅 **Performance & Promotion:** employee ratings, promotion rates, training completion and high performers.
- 📊 **Executive Summary:** consolidated KPIs, employee lifecycle, workforce costs, department health and strategic insights.

The design uses an Accenture-inspired purple palette, dark left navigation, KPI cards, interactive charts, India maps, detailed tables and insight panels.

---

# 🎯 Objective

The objective is to turn HR data into an accessible decision-support dashboard that helps users:

- Monitor employee headcount, active workforce and workforce composition.
- Track hiring patterns and geographical distribution.
- Identify departments, age groups and locations with higher attrition.
- Evaluate employee retention and exit tenure.
- Compare compensation across departments, job levels and cities.
- Examine salary distribution, payroll and gender pay differences.
- Assess performance ratings, promotion activity and training completion.
- Present consolidated workforce health indicators to leadership.
- Explore metrics through slicers, drill-down charts and detailed tables.

---

# 📦 Data Model

The supplied screenshots show **report pages and the project folder**, not the Power BI Model view. Accordingly, exact table names, relationships, dataset schemas, row counts and DAX definitions **cannot be verified** from the provided material.

The report visibly analyzes these data areas:

| Data area | Fields or metrics visible in the report |
|---|---|
| Employee workforce | Total employees, active employees, gender, age group, tenure |
| Organization | Department, business unit, job level, grade |
| Geography | City / location |
| Calendar | Financial year, quarter, month |
| Hiring and exits | Hiring trend, attritions, attrition rate, retention rate, exit tenure |
| Compensation | Salary LPA, payroll, median salary, salary bands, experience |
| Performance | Performance rating, high performers, promotions, promotion rate |
| Learning | Training completion percentage |
| Executive analysis | Employee lifecycle stages, workforce cost, department health score |

**Note:** These are analytical categories observed in the visuals, **not confirmed Power BI table names**. The original model should be inspected before documenting its physical schema or relationships.

---

# ✨ Features

- 👥 Headcount and active-employee KPI cards with previous-year comparisons.
- 📉 Attrition, retention and exit-tenure analysis.
- 📊 Department, business-unit, age-group and gender breakdowns.
- 🗺️ Employee distribution and attrition maps across Indian cities.
- 📈 Hiring, attrition and promotion trends with **Year → Quarter → Month** drill-down.
- 💰 Payroll, average/median salary and salary-band analysis.
- 📍 Salary comparisons by department, job level, location and gender.
- 🏅 Employee performance-rating distribution and high-performer analysis.
- 🎓 Training completion and promotion KPIs.
- 🌳 Treemap visuals for high-risk employee segments and workforce cost.
- 🔎 Detailed department and job-level summary tables.
- 🎛️ Page-specific slicers and **Clear Filters** controls.
- 💡 Key insights on each report page.
- 🧭 Five-page sidebar navigation.

---

# 🏗️ Repository Structure

The supplied folder screenshot shows `Assets`, `Dataset` and a Power BI report file named `Workpice (Accenture) Dashboard` (as displayed in File Explorer). A recommended GitHub layout is:

```text
📦 Accenture (Workplace) Dashboard
│
├── 📊 Workpice (Accenture) Dashboard.pbix  → Power BI report (verify exact filename/extension)
│
├── 📁 Dataset                             → Source dataset files
│
├── 📁 Assets                              → Dashboard assets
│   └── 📁 Images                          → Dashboard screenshots (add these files)
│       ├── Page-1.png                     → Workforce Overview
│       ├── Page-2.png                     → Attrition & Retention
│       ├── Page-3.png                     → Compensation Analytics
│       ├── Page-4.png                     → Performance & Promotion
│       └── Page-5.png                     → Executive Summary
│
└── 📝 README.md                            → Project documentation
```

**Note:** The `Assets/Images` directory and filenames above are suggested for README screenshots; the screenshot only confirms the top-level `Assets` and `Dataset` folders. Rename the PBIX entry if its actual filename differs.

---

# 🗂️ Report Pages

## 👥 Page 1: Workforce Overview

The **Workforce Overview** page summarizes workforce size, active employees, employee composition, location and department distribution, and hiring activity.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| 👥 Total Employees | 50,000 |
| ✅ Active Employees | 48,006 |
| 📉 Attrition Rate | 16.00% |
| 📅 Average Tenure | 10.26 years |
| ⚥ Gender Ratio (Male : Female) | 61 : 39 |

### Visuals

| Visual | Analysis |
|---|---|
| Employee Distribution by Department | Column chart comparing departmental headcounts |
| Employee Distribution by Location | Bubble map of workforce across Indian cities |
| Workforce Composition | Doughnut chart of male/female employee distribution |
| Hiring Trend | Time-series with Year → Quarter → Month drill-down |
| Workforce Summary by Business Unit and Department | Department-level headcount, employee share, attrition, salary and experience |
| Key Insights | Summary of headcount growth, workforce mix and tenure |

### Workforce Composition

| Gender | Employees | Share displayed |
|---|---:|---:|
| Male | 30,388 | 60.78% |
| Female | 19,612 | 39.22% |

### Key Insights displayed on the page

- Total headcount increased **11.67%** compared with the previous year.
- The insight panel states that **Technology and Consulting** together contribute **79.71%** of the workforce.
- **Bengaluru** has the highest employee base (**3,020**), followed by **Hyderabad (1,920)** and **Mumbai (1,680)**.
- Average tenure improved by **0.5 years** compared with the previous year.

### 📸 Dashboard Screenshot

<img src="Assets/Dashboard image/Page-1.png" alt="Accenture India Workforce Overview Dashboard">

---

## 📉 Page 2: Attrition & Retention

The **Attrition & Retention Analysis** page examines employee exits, retention, attrition risk by department and age group, and the timing and location of employee departures.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| 🚪 Total Attritions | 8,000 |
| 📉 Attrition Rate | 16.00% |
| 🛡️ Retention Rate | 84.00% |
| 📅 Average Exit Tenure | 10.21 years |

### Visuals

| Visual | Analysis |
|---|---|
| Attrition by Department | Horizontal bars comparing exits across departments |
| Attrition by Age Group | Employee exits across five age bands |
| Attrition Trend | Year → Quarter → Month time-series drill-down |
| Attrition by Gender | Male/female attrition breakdown |
| Attrition by Location | Bubble map showing exits by city |
| High-Risk Employee Segment Analysis | Treemap highlighting departments with higher exit counts |
| Attrition Detail by Department | Attrition count, rate, average exit tenure and change |

### Attrition by Age Group

| Age group | Attritions |
|---|---:|
| 36–45 | 2,056 |
| 26–35 | 2,003 |
| 46–55 | 1,973 |
| 55+ | 996 |
| 18–25 | 972 |

### Attrition by Gender

| Gender | Attritions | Share displayed |
|---|---:|---:|
| Male | 4,815 | 60.19% |
| Female | 3,185 | 39.81% |

### Key Insights displayed on the page

- Attrition increased from **14.06%** to **16.00%**, approximately **1.9 percentage points**.
- **SAP (575)** records the highest department attrition count in the visible chart, followed by **Data Science (570)** and **AI & ML (563)**.
- Employees aged **36–45** show the highest exit count (**2,056**).
- The displayed exit tenure stays near **10 years** across departments.

### 📸 Dashboard Screenshot

<img src="Assets/Dashboard image/Page-2.png" alt="Accenture India Attrition and Retention Dashboard">

---

## 💰 Page 3: Compensation Analytics

The **Compensation & Salary Analytics** page compares payroll and employee compensation across salary bands, departments, job levels, experience, cities and gender.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| 💼 Total Payroll | 15.72K (dashboard display) |
| 💰 Average Salary | 31.45 LPA |
| 🏆 Highest Salary | 60.00 LPA |
| 📊 Median Salary | 31.34 LPA |
| 👥 Total Employees | 50,000 |

### Visuals

| Visual | Analysis |
|---|---|
| Salary Distribution (LPA) | Employee counts across salary bands |
| Average Salary by Department | Department-wise average salary comparison |
| Average Salary by Job Level | Compensation comparison by job role |
| Salary vs Experience | Scatterplot of salary and experience |
| Salary by Location | Geographic view of average salary |
| Salary by Gender | Doughnut chart comparing male/female salary figures |
| Compensation Summary by Department and Job Level | Employees, payroll, average/median/minimum/maximum salary |

### Salary Distribution (LPA)

| Salary band (LPA) | Employees shown |
|---|---:|
| 3–6 | 2,596 |
| 6–9 | 2,644 |
| 9–12 | 2,655 |
| 12–15 | 2,560 |
| 15–20 | 4,453 |
| 20–30 | 8,862 |
| 30–40 | 8,816 |
| 40–50 | 8,727 |
| 50+ | 8,687 |

### Key Insights displayed on the page

- Average salary increased **12.50%** compared with the previous year, from **27.95** to **31.45 LPA**.
- The insight panel identifies **Strategy & Consulting** as the highest average-salary business unit.
- **Gurugram** is highlighted as having the highest average salary, approximately **₹32 LPA**.
- The insight panel reports a **13.27% gender pay gap**. This is a dashboard-reported figure; its calculation method is not visible.

### 📸 Dashboard Screenshot

<img src="Assets/Dashboard image/Page-3.png" alt="Accenture India Compensation and Salary Analytics Dashboard">

---

## 🏅 Page 4: Performance & Promotion

The **Performance & Promotion Analytics** page focuses on employee ratings, promotion outcomes, high performers and training participation.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| ⭐ Average Performance Rating | 3.6 / 5 |
| 📈 Promotion Rate | 8.94% |
| 🏅 High Performers | 22,659 |
| 🎓 Training Completion | 92.01% |

### Visuals

| Visual | Analysis |
|---|---|
| Performance Rating Distribution | Counts for ratings 1 through 5 |
| Promotions by Department | Department-level promotion counts |
| Training Completion Analysis | Completed vs pending training doughnut chart |
| Performance by Location | Map of high performers across cities |
| Promotion Trend | Year → Quarter → Month drill-down |
| Department Performance Summary | Rating, promotions, promotion rate, training completion and high performers |

### Performance Rating Distribution

| Rating | Employees shown |
|---|---:|
| 1 | 2,902 |
| 2 | 10,963 |
| 3 | 36,320 |
| 4 | 39,203 |
| 5 | 19,061 |

**Note:** The displayed rating counts sum to more than 50,000; they may reflect a different grain or reporting population. The screenshots do not establish why, so these should not be interpreted as a unique-employee breakdown without checking the model.

### Key Insights displayed on the page

- Average performance rating is approximately **3.6 / 5**.
- Promotion rate is **8.94%**, compared with **8.98%** in the previous year.
- Training completion improved by **2.5 percentage points** to **92.01%**.
- High performers increased by **13.87%** to **22,659**.
- The insight panel highlights **Bengaluru** as the location with the highest number of high performers (**688**).

### 📸 Dashboard Screenshot

<img src="Assets/Dashboard image/Page-4.png" alt="Accenture India Performance and Promotion Analytics Dashboard">

---

## 📊 Page 5: Executive Summary

The **Executive HR Summary Dashboard** combines major workforce metrics and strategic visualizations into a consolidated leadership view.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| 👥 Total Employees | 50,000 |
| 📉 Attrition Rate | 16.00% |
| 💰 Average Salary | 31.45 LPA |
| 📈 Promotion Rate | 8.94% |
| 🏅 High Performers | 22,659 |

### Visuals

| Visual | Analysis |
|---|---|
| Employee Lifecycle Funnel | Applied → Interviewed → Offered → Joined → Retained |
| Workforce Cost by Department (₹ Cr) | Treemap comparing departmental workforce costs |
| Attrition % vs Average Salary (LPA) | Bubble chart comparing attrition and pay by department |
| Employee Distribution by Location | Workforce bubble map across India |
| Department Health Scorecard | Attrition, salary, performance, promotion, training and health score |
| Key Executive Insights | Leadership-focused summary of workforce indicators |

### Employee Lifecycle Funnel

| Stage | Value displayed |
|---|---:|
| Applied | 275K |
| Interviewed | 110K |
| Offered | 50K |
| Joined | 40K |
| Retained | 25K |

The funnel labels show **9.1%** retained relative to applicants (25K out of 275K).

### Key Insights displayed on the page

- Workforce headcount is **50,000**, up **11.67%** year over year.
- Attrition is **16.00%**, approximately **1.9 percentage points** higher than the previous year.
- Average salary is **31.45 LPA**, up **12.50%** year over year.
- Promotion rate is **8.94%**, slightly below the previous year's **8.98%**.
- High performers total **22,659**.
- The funnel shows **25K retained** from **275K applicants**.

### 📸 Dashboard Screenshot

<img src="Assets/Dashboard image/Page-5.png" alt="Accenture India Executive HR Summary Dashboard">

---

# 🔍 Filters & Slicers

The report provides page-specific filters:

| Page | Available filters |
|---|---|
| Workforce Overview | Financial Year, Quarter, Department, Business Unit, City, Job Level, Gender |
| Attrition & Retention | Year, Department, City, Job Role, Gender |
| Compensation Analytics | Department, Job Level, Grade, Location |
| Performance & Promotion | Department, Location, Grade, Business Unit |
| Executive Summary | No top-row slicers visible in the supplied screenshot |

A **Clear Filters** button appears on the first four pages. Charts and tables may support additional cross-filtering interactions within Power BI.

---

# 💡 Key Insights

Based on the dashboard screenshots dated **30 April 2025**:

- 👥 The dashboard reports **50,000 total employees** and **48,006 active employees**.
- 📈 Total headcount grew **11.67%** compared with the previous year.
- 🚪 **8,000 attritions** correspond to a displayed **16.00% attrition rate** and **84.00% retention rate**.
- 👤 Employees aged **36–45** have the highest displayed attrition count (**2,056**).
- 💰 Average salary is **31.45 LPA**, with a **12.50%** year-over-year increase.
- 📊 Median salary is **31.34 LPA**, while the highest salary KPI is **60.00 LPA**.
- 🏅 The report shows **22,659 high performers** and an **8.94% promotion rate**.
- 🎓 Training completion reaches **92.01%**, an increase of approximately **2.5 percentage points**.
- 🗺️ Bengaluru is highlighted for the largest employee population (**3,020**).
- 🧩 The executive page consolidates workforce costs, attrition versus salary, lifecycle stages and department health scores.

**Interpretation note:** These figures are transcribed from the supplied report pages. Some displayed totals or visual labels use different aggregation contexts; validating their definitions requires access to the underlying PBIX model and dataset.

---

# 🎨 Theme & Formatting

### Design

- Accenture-inspired **purple, violet and dark-navy** color palette.
- White canvas with rounded cards and subtle outlines.
- Dark left sidebar with icons and an active-page purple highlight.
- Large KPI values, purple icons and green/red comparison indicators.
- Consistent headings, chart colors and data labels across pages.
- Geographic maps with city markers.
- Compact matrix tables, treemaps, doughnut charts and line charts.
- Dedicated **Key Insights** panels for contextual storytelling.

### Dashboard Layout

- **Workforce Overview:** slicers and KPI cards at the top; distribution charts, map and hiring trend in the middle; business-unit table and insights below.
- **Attrition & Retention:** KPI cards and attrition comparisons at the top; gender, location, risk treemap and department details below.
- **Compensation Analytics:** payroll and salary KPIs, salary charts, geographic pay view, compensation table and insights.
- **Performance & Promotion:** performance KPIs, rating and promotion charts, training completion, geographic performance and department summary.
- **Executive Summary:** strategic KPIs, employee funnel, cost treemap, salary-versus-attrition scatterplot, map and department health scorecard.

---

# 🛠️ Tools & Techniques

| Tool / Feature | Purpose |
|---|---|
| Microsoft Power BI Desktop | Creating and viewing the report |
| Power Query Editor | Preparing and transforming data, if required by the source model |
| Power BI Data Model | Supporting relationships and aggregations; exact model not supplied |
| DAX Measures | Potential implementation of KPIs; exact expressions not provided |
| Card / KPI Visuals | Displaying headcount, salary, attrition and performance |
| Column and Bar Charts | Comparing departments, ratings and salary ranges |
| Line Charts | Visualizing hiring, attrition and promotion trends |
| Doughnut Charts | Showing gender and training distributions |
| Scatterplot | Exploring salary versus experience and attrition |
| Treemap | Highlighting high-risk segments and workforce cost |
| Map Visuals | Displaying geographic workforce indicators |
| Table / Matrix Visuals | Department, job-level and health-score details |
| Slicers | Filtering by year, organization, location and demographics |
| Drill-down | Exploring Year → Quarter → Month trends |

**Note:** Power Query and DAX are common Power BI techniques, but their specific transformations and formulas cannot be confirmed from the screenshots alone.

---

# 🚀 How to Use This Project

1. **Clone or download** the repository.
2. Open the project's **`.pbix` file** using **Microsoft Power BI Desktop**.
3. If a data-source error appears, select **Home → Transform data → Data source settings** and point the report to the files in `Dataset` as needed.
4. Select **Refresh** after configuring any required data connections.
5. Use the left sidebar to navigate among the five report pages.
6. Apply page-specific slicers to explore departments, cities, job levels, genders or time periods.
7. Explore chart interactions, drill-downs and summary tables to examine HR trends.
8. Use **Clear Filters** on supported pages to reset selections.

**Note:** The exact PBIX filename, dataset filenames, data-source paths and refresh requirements should be confirmed in the local project.

---

# 📈 Learning Outcomes

- ✅ Design a professional, multi-page HR analytics dashboard in Power BI.
- ✅ Present workforce KPIs with previous-year comparisons.
- ✅ Analyze headcount, department distribution and gender composition.
- ✅ Evaluate employee attrition, retention and exit patterns.
- ✅ Compare salary bands, average pay and compensation across groups.
- ✅ Analyze performance ratings, promotions and training completion.
- ✅ Use geographic maps for location-based workforce analysis.
- ✅ Create drill-down time-series and interactive slicers.
- ✅ Build executive summaries with funnels, treemaps and health scorecards.
- ✅ Communicate HR findings through data storytelling and visual consistency.

---

# 👤 Author

<div align="center">

# Ved Dhameliya

**Accenture India – HR & Workforce Analytics Dashboard | Power BI Project**

*Power BI · HR Analytics · Workforce Data Visualization*

---

### ⭐ Thank You For Visiting This Project ⭐

Made with ❤️ using Microsoft Power BI

</div>
