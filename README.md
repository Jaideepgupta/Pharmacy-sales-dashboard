# 💊 Pharmacy Sales Performance Dashboard
### Built with Tableau | Data Source: Excel/CSV

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

> *Tracking effort, outcomes, and field effectiveness across pharma sales teams*

![Dashboard Preview](https://raw.githubusercontent.com/Jaideepgupta/Pharmacy-sales-dashboard/main/Pharmacy%20Performance.png)

## 🔗 Live Dashboard

Explore the interactive dashboard on Tableau Public:

👉 https://public.tableau.com/app/profile/jaideep.gupta7070/viz/PharmacyDashboard_5_17696851082490/PharmacyPerformance

---

## 📌 Overview

An end-to-end **Tableau dashboard** designed for pharma sales managers and executives to monitor field rep performance, doctor engagement, and sales outcomes — all in one view.

The dashboard goes beyond vanity metrics. Every chart is built around a **business question**, and every tooltip delivers a **contextual insight** — not just raw numbers.

---

## 🧠 Business Questions Answered

| Chart | Question |
| :--- | :--- |
| Effort vs Output Efficiency | Do higher doctor calls actually translate into higher sales? |
| Sales Performance vs Target | Who is meeting targets — and who needs intervention? |
| Leave Impact on Field Coverage | How does monthly leave affect doctor call continuity? |
| Call Duration vs Outcome Quality | Do longer calls consistently improve engagement outcomes? |
| Doctor Class Coverage vs Sales | Is call effort concentrated on the right doctor segments? |
| Gift Distribution by Specialty & Region | Where is promotional spend actually going? |
| Operational Discipline: Reminder Calls | Which reps follow up consistently vs sporadically? |
| Doctor Call Activity Calendar | What day-of-week and seasonal patterns exist in field activity? |

---

## ✨ Key Features

- **Insight-driven tooltips** — hover over any data point to get a contextual business insight, not just a number
- **Dual navigation** — toggle between *Salesperson Performance Profile* and *Executive Dashboard* views
- **Multi-level filters** — slice by Salesperson, Manager, Region, State, City, or Brand
- **Effort vs Value analysis** — identifies where call effort is not translating into proportional sales
- **Leave correlation** — unique analysis linking HR data (monthly leave) to field productivity metrics
- **Consistent visual language** — coral/navy palette with clear target lines and average benchmarks

---

## 📊 Dashboard Sections

### 1. Effort vs Output Efficiency
Scatter plot showing Total Doctor Calls vs Total Sales by City. Average lines create four quadrants — instantly surfacing high-effort/low-return and low-effort/high-return outliers.

### 2. Monthly Sales Trend by City
Line chart tracking consistency, volatility, and growth patterns across 12 months for key cities.

### 3. Sales Performance vs Target
Horizontal bar chart comparing actual sales vs targets per salesperson, with clear visual encoding of target achieved vs not achieved.

### 4. Leave Impact on Field Coverage
Bubble chart correlating monthly leave days with monthly doctor calls — revealing how absenteeism affects field coverage continuity.

### 5. Gift Distribution by Doctor Specialty & Region
Stacked bar showing where promotional spend is concentrated across Diabetologist, Cardiologist, Orthopedic, and General Physician segments by region.

### 6. Doctor Call Activity Calendar
Heatmap of call activity by day-of-week and month — surfaces behavioral patterns and low-activity periods.

### 7. Sales Contribution vs Call Effort by Salesperson
Dual bar comparison of call volume vs sales contribution per rep — identifies efficiency gaps.

### 8. Doctor Class Coverage vs Sales
Grouped bar comparing call effort and revenue across doctor classes (A, B, C) — reveals the classic effort-value mismatch.

### 9. Call Duration vs Outcome Quality
Segmented bar showing outcome quality (Positive / Neutral / Negative) across three call duration bands (0-3 min, 3-6 min, 6-9 min).

### 10. Operational Discipline: Reminder Calls
Area chart showing reminder call consistency per salesperson across months — a proxy for structured sales execution.

---

## 🗂️ Repository Structure

```
📦 pharmacy-sales-dashboard
 ┣ 📊 Pharmacy_Dashboard_with_salesforce_data.twbx   # Tableau packaged workbook
 ┣ 🖼️ Pharmacy_Performance.png                        # Dashboard screenshot
 ┣ 📄 README.md                                        # This file
 ┗ 📁 data/
    ┗ (source CSV/Excel files)
```

---

## 🛠️ Tools & Tech

- **Tableau Desktop** — dashboard design, calculated fields, tooltip customization
- **Excel / CSV** — data source
- **Data modelling** — relationships, blended metrics across HR and sales datasets

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Pharmacy_Dashboard_with_salesforce_data.twbx` in **Tableau Desktop** or **Tableau Public**
3. Use the filter panel (left sidebar) to explore by Salesperson, Region, City, or Brand
4. Hover over any chart element to read the **insight tooltip**
5. Toggle between **Salesperson Performance Profile** and **Executive Dashboard** using the top navigation tabs

---

## 💡 Design Decisions

- **Subtitles as hypotheses** — each chart subtitle poses the business question being tested, making the dashboard self-explanatory
- **Tooltip-as-insight** — tooltips are written as analytical commentary, not just field values
- **Leave data integration** — connecting HR leave records to field activity data is a non-obvious but high-value correlation
- **Quadrant analysis** — average reference lines on the scatter plot create instant segmentation without complex calculations

---

## 👤 Author

**Jaideep Gupta** — Built as a portfolio project demonstrating pharma sales analytics, Tableau design principles, and business-first dashboard thinking.

> **Data Note:** The dataset used in this dashboard is synthetic/anonymized and intended solely for demonstration purposes.

---

## 📬 Connect

If you found this useful or want to discuss the design approach, feel free to reach out:

- 🔗 [LinkedIn — Jaideep Gupta](https://www.linkedin.com/in/guptajaideep/)
- 📊 [Tableau Public Profile](https://public.tableau.com/app/profile/jaideep.gupta7070/vizzes)

---

*⭐ Star this repo if you found it helpful!*
