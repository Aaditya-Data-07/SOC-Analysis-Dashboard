# 🛡️ Cyber Defense - SOC Analysis Dashboard (Power BI)

![SOC Command Center](Images/soc-command-center.png)

## 📌 Project Overview

The **Cyber Defense - SOC Analysis Dashboard** is an end-to-end interactive Power BI project designed to simulate a real-world **Security Operations Center (SOC)** environment. The dashboard enables cybersecurity teams and business stakeholders to monitor security incidents, analyze attack patterns, track analyst performance, evaluate SLA compliance, and gain actionable insights through dynamic visualizations.

The project is built using a **dataset containing 100,000 cybersecurity incident records**, making it suitable for demonstrating enterprise-scale data analysis and dashboard development.

---

# 🎯 Project Objectives

- Monitor cybersecurity incidents in real time.
- Analyze attack trends and incident distribution.
- Identify high-risk departments and targeted assets.
- Measure analyst performance and productivity.
- Track SLA compliance and breach analysis.
- Provide management with interactive insights for better decision making.

---

# 🚀 Dashboard Features

This project contains **6 fully interactive dashboard pages**, each focusing on a different aspect of Security Operations.

---

## 🖥️ 1. SOC Command Center

Provides a high-level overview of the organization's security posture.

![SOC Command Center](Images/soc-command-center.png)

### Includes

- Total Incidents
- Open Incidents
- Critical Incidents
- SLA Compliance
- Average Response Time
- Average Resolution Hours
- Incident Trend
- High Risk Departments
- Top Threats
- Analyst Snapshot
- Top Targeted Assets
- SLA Status

---

## 📈 2. Executive Overview

Designed for management and leadership teams to quickly understand the organization's security health.

![Executive Overview](Images/executive-overview.png)

### Includes

- Overall Incident Trend
- High Risk Departments
- Executive KPIs
- Department-wise Incident Analysis

---

## 🚨 3. Incident Analysis

Deep dive into incident-related analytics.

![Incident Analysis](Images/incident-analysis.png)

### Includes

- Incidents by Attack Type
- Severity Distribution
- Incident Status Distribution
- Attack Type Distribution (Top 10)
- Attack Type vs Severity Analysis

---

## 🌍 4. Threat Intelligence

Focused on identifying threat patterns and targeted infrastructure.

![Threat Intelligence](Images/threat-intelligence.png)

### Includes

- Monthly Attack Trend
- Incident Locations (World Map)
- Incidents by Asset Type
- Top Targeted Assets
- Attack Trend Analysis

---

## 👨‍💻 5. Analyst Performance

Designed to evaluate SOC analyst productivity.

![Analyst Performance](Images/analyst-performance.png)

### Includes

- Top Analysts by Closed Incidents
- Resolution Hours by Analyst
- Average Resolution Hours
- Average Severity Score
- Analyst Performance Metrics

---

## ⏱️ 6. SLA & Operations

Measures operational efficiency.

![SLA & Operations](Images/sla-&-operations.png)

### Includes

- SLA Compliance Gauge
- High Risk Severity
- High Risk Departments
- Top SLA Breaches
- Resolution Hours vs Allowed SLA
- SLA Performance Analysis

---

# 🎛 Interactive Filters

Every report page includes interactive slicers allowing users to dynamically explore the data.

Available filters include:

- Year
- Month
- Quarter
- Day
- Date Range
- Attack Type
- Severity
- Department
- Location
- Asset Type
- Analyst Name
- Incident Status
- SLA Status

These filters provide drill-down capabilities for detailed analysis across all dashboard pages.

---

# 📊 Visualizations Used

The dashboard includes a variety of professional Power BI visuals chosen according to business requirements.

### Visual Types

- KPI Cards
- Line Charts
- Area Charts
- Bar Charts
- Clustered Bar Charts
- Stacked Column Charts
- Donut Charts
- Pie Charts
- Treemap
- Gauge Chart
- Map Visualization
- Data Tables
- Interactive Slicers

Each visualization has been selected to communicate specific cybersecurity insights effectively while maintaining a clean and executive-friendly layout.

---

# ⚡ Data Modeling

The project follows a structured relational data model using multiple connected tables.

Main tables include:

- Incident
- Asset
- Analyst
- Department
- Date

Relationships have been created to support efficient filtering and accurate analytical calculations.

---

# 🧮 DAX & Calculated Columns

This dashboard makes extensive use of **DAX (Data Analysis Expressions)** and calculated columns to perform advanced analytics.

Examples include:

- KPI Calculations
- SLA Compliance Percentage
- Average Resolution Hours
- Average Response Time
- Open Incident Count
- Critical Incident Count
- Severity Score
- Incident Status Analysis
- Time Intelligence Calculations
- Custom Measures
- Calculated Columns
- Conditional Logic using SWITCH() and IF()
- Percentage Calculations
- Ranking Calculations

These calculations enhance reporting accuracy and enable deeper business insights.

---

# 📈 Key Insights Generated

The dashboard helps answer important business questions such as:

- Which departments experience the highest number of security incidents?
- Which attack types occur most frequently?
- Which assets are most commonly targeted?
- Which analysts resolve the highest number of incidents?
- What is the current SLA compliance rate?
- Which incidents breached SLA targets?
- How are incidents distributed by severity?
- What are the monthly attack trends?
- Which geographical locations experience the most attacks?
- How efficiently are analysts resolving incidents?

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- CSV Dataset
- Data Modeling
- Star Schema
- Microsoft Bing Maps

