# 📘 Academic Project Portfolio – Rowena Sagaria

This repository documents a series of academic data projects spanning data engineering, analytics, visualization, and strategic digital transformation. Each project addresses a real-world business or policy question and showcases practical application of data tools and methods.

---

## 📊 1. SAP Business Analysis Portfolio

**Objective**: Analyze SAP operational data to generate actionable insights across financials, sales, and logistics domains.

**Key Features**:
- Used SAP ECC/SAP GUI for structured ERP data analysis.
- Integrated pivot tables, dashboards, and KPIs in Excel for business review.
- Explored customer/vendor balances, delivery performance, sales reports.

**Outcomes**:
- Identified slow-moving items and bottlenecks in sales processes.
- Suggested improvements to logistics chain and purchase frequency.

---

## 📦 2. ETL Project – Slaughterhouse Analytics (MySQL + Cron Jobs)

**Objective**: Design a complete ETL pipeline for federally inspected Canadian livestock slaughterhouses data.

**Dataset**: Weekly data (1997–2024) from [open.canada.ca](https://open.canada.ca/data/en/dataset/3c981dfe-30ac-44cb-b9a3-0fb450913d1b)

**Tech Stack**:  
`MySQL` · `Shell Scripting` · `Linux Terminal` · `Cron Jobs`

**Process**:
- **Extract**: Ingested CSV via MySQL CLI into `slaughterdata` table.
- **Transform**: Created derived tables by season using `CASE` logic.
- **Load**: Exported cleansed data into CSVs using shell commands.
- **Automation**: Scheduled daily data refreshes using CRON job on Timberlea cluster.

**Outcomes**:
- Built automation pipelines for livestock categorization by season.
- Enabled historical trend analysis for agriculture & policy insights.

---

## 🌍 3. Emigration Analytics (Power BI)

**Objective**: Visualize international emigration trends and migration motivators using Power BI.

**Data Sources**:
- World Bank Open Data
- UN Migration Statistics

**Visuals & Features**:
- Global emigration map with country filters.
- Bar chart for top emigrating countries.
- Line graph tracking migration reasons over years.
- Card visuals for summary KPIs.

**Outcomes**:
- Showcased regions with highest economic and climate-driven migration.
- Supported use of interactive filters for dynamic story-telling.

---

## 🧭 4. Digital Transformation Project (Case Study Report)

**Objective**: Analyze digital maturity and transformation roadmap of a real business.

**Structure**:
- SWOT Analysis of digital capabilities.
- Alignment of current IT systems with business goals.
- Evaluation of cloud adoption, cybersecurity, and ERP implementation.

**Key Areas Covered**:
- Business Model Impact
- Technology Stack Evaluation
- Digital Risk Assessment

**Outcomes**:
- Proposed roadmap for gradual cloud migration.
- Emphasized need for cross-functional training in analytics tools.
- Mapped tech stack to maturity levels using industry benchmarks.

---

## 📁 Folder Structure

```
📦 AcademicProjects
 ┣ 📁 SAP_Business_Analysis
 ┣ 📁 ETL_Slaughterhouse_MySQL
 ┣ 📁 Emigration_PowerBI
 ┗ 📁 Digital_Transformation_CaseStudy
```

---

## 📬 Contact

For more details, questions, or access to raw datasets:

**Rowena Sagaria**  
📧 rowena.sagaria@email.com  
🌐 [LinkedIn](https://www.linkedin.com/in/rowenasagaria)

---