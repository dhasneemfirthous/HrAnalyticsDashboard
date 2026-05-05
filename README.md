# 📊 HR Analytics Dashboard — Power BI

An interactive Power BI dashboard that analyzes employee attrition, demographics, and workforce metrics to help HR teams identify trends and make data-driven decisions.

---

## 🖼️ Dashboard Preview

> Open `HrAnalytics_Dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to explore the interactive report.

---

## 📁 File

| File | Description |
|------|-------------|
| `HrAnalytics_Dashboard.pbix` | Power BI report file with embedded data and visuals |

---

## 📌 Dashboard Overview

The dashboard is built on a single page with **29 visuals** covering the following areas:

### 🔢 KPI Cards
| Metric | Description |
|--------|-------------|
| **Count of Employees** | Total headcount in the dataset |
| **Attrition Rate** | Percentage of employees who left |
| **Attrition Count** | Absolute number of employees who left |
| **Avg Age** | Average age of the workforce |
| **Avg Salary** | Average monthly income |
| **Avg Years at Company** | Average employee tenure |

### 📈 Charts & Visuals
| Visual | Type | Description |
|--------|------|-------------|
| Attrition Count by Age Group | Clustered Bar Chart | Breakdown of attrition across different age bands |
| Attrition Count by Education Field | Column Chart | Which education backgrounds have higher attrition |
| Attrition Count by Salary | Line Chart | Relationship between salary hike % and attrition |
| Employees Attrition Count by Gender | Donut Chart | Gender-wise attrition split |
| Job Role Summary Table | Table | Headcount, average age, and tenure by job role |
| Department Filter | Card Visual | Department-level breakdown |

### 🎛️ Slicers (Filters)
- **Job Role** — Filter all visuals by specific job roles
- **Education Field** — Filter by employee education background

---

## 🗂️ Dataset

The report uses the **HR Employee Attrition** dataset — a widely used HR analytics dataset containing the following fields:

| Category | Fields |
|----------|--------|
| **Demographics** | Age, Gender, Education, EducationField |
| **Job Info** | JobRole, Department, BusinessTravel, DistanceFromHome |
| **Compensation** | MonthlyIncome, PercentSalaryHike, StockOptionLevel |
| **Satisfaction** | JobSatisfaction, EnvironmentSatisfaction, WorkLifeBalance |
| **Performance** | PerformanceRating, TrainingTimesLastYear |
| **Tenure** | YearsAtCompany, YearsInCurrentRole |
| **Target** | Attrition (Yes/No) |

> The dataset is embedded within the `.pbix` file.

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) — Windows only
- Alternatively, upload to [Power BI Service](https://app.powerbi.com) (web)

### Steps
1. Clone or download this repository
2. Open `HrAnalytics_Dashboard.pbix` in Power BI Desktop
3. Explore the visuals — use the **Job Role** and **Education Field** slicers to filter the report
4. To publish: go to **Home → Publish** and select your Power BI workspace

---

## 💡 Key Insights (from visuals)

- Monitor which **age groups** and **education fields** drive the most attrition
- Compare **salary hike trends** against attrition patterns
- Use the **job role table** to identify departments with high turnover risk
- Filter by **department** to drill into specific business units

---

## 🛠️ Built With

- **Power BI Desktop** — Report authoring
- **HR Employee Attrition Dataset** — Source data (Kaggle)
- **DAX** — Measures for Attrition Rate and aggregated KPIs
