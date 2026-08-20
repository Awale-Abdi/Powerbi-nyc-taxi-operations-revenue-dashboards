<h1 align="center">Operational Performance Analytics | End-to-End Business Intelligence with Power BI</h1>

This project showcases an **end-to-end Business Intelligence and data analytics workflow** built using approximately **49 million transportation records**. I developed it to demonstrate enterprise-scale data preparation, dimensional modeling, KPI development, interactive dashboard design, analytical interpretation, and executive reporting.

Although the project uses the **NYC Yellow Taxi dataset** as its case study, the techniques demonstrated, including **data transformation, dimensional modeling, KPI development, performance analysis, interactive dashboarding, and decision-support reporting**, are broadly transferable across operations, logistics, healthcare, retail, finance, manufacturing, and other data-driven fields.

Using **Amazon S3**, **Power Query**, **DAX**, and **Power BI**, I designed and delivered a complete analytical solution capable of transforming large-scale raw data into structured business intelligence for performance monitoring, resource allocation, operational analysis, and executive decision-making.

To challenge myself, I completed the entire project over **two standard working days (9–5)**, demonstrating my ability to rapidly execute an end-to-end analytics workflow from raw data ingestion through to executive-ready reporting.

## 💼 Executive Questions

The project simulates requests from an executive leadership team responsible for improving operational performance, resource allocation, revenue generation, and data quality.

The analysis addresses:

- How are demand and revenue trending over time?
- Is business performance driven primarily by transaction volume or revenue efficiency?
- When does peak operational demand occur, and are resources aligned accordingly?
- How does operational performance vary across regions?
- Which operational areas appear inefficient or underperforming?
- What customer payment behaviors are most common?
- Are there data quality issues impacting business decisions?

## 🎯 Project Goals

The project focuses on applying Business Intelligence and large-scale data analytics to transform raw operational data into actionable decision-support insights.

The primary goals were to:

- Prepare and transform approximately 49 million records
- Design a scalable dimensional data model
- Develop business KPIs using DAX
- Analyze operational, revenue, temporal, and geographic performance
- Identify resource allocation and data quality opportunities
- Build interactive executive dashboards
- Translate analytical findings into actionable business recommendations

## 🏗️ Solution Architecture

#### Workflow

```text
Raw Parquet Datasets
        ↓
Amazon S3
        ↓
Power Query ETL
        ↓
Data Cleaning & Transformation
        ↓
Feature Engineering
        ↓
Dimensional Modeling
        ↓
Star Schema Development
        ↓
DAX & KPI Development
        ↓
Interactive Power BI Dashboards
        ↓
Analytical Interpretation
        ↓
Executive Reporting
```

#### Data

- **Dataset:** NYC Yellow Taxi Trips
- **Size:** ~49 million records
- **Period:** 12 months
- **Format:** Parquet
- **Storage:** Amazon S3
- **Primary Focus:** Operational performance, demand, revenue, geographic activity, customer behavior, and data quality

**Data Source:** NYC Taxi & Limousine Commission Trip Record Data

#### Data Preparation & Engineering

Performed enterprise-scale ETL using **Power Query** by:

- Combining 12 monthly datasets
- Standardizing data types
- Cleaning null and inconsistent values
- Engineering new analytical fields
- Creating pickup date and hour features
- Calculating trip duration
- Standardizing categorical values
- Preparing the transformed data for dimensional modeling and reporting

#### Dimensional Modeling

Designed a dimensional **Star Schema** centered around:

- **Fact Table**
  - FactTrips

- **Dimension Tables**
  - Date
  - Payment Type
  - Rate Code
  - Zone Lookup

Created a dynamic **Calendar Table** using DAX to support time intelligence and temporal analysis.

#### KPI Development

Developed reusable **DAX measures and business KPIs** including:

- Total Trips
- Total Revenue
- Revenue per Trip
- Average Trip Distance
- Average Trip Duration
- Tip Percentage
- Executive KPI formatting

#### Business Intelligence & Dashboard Development

Developed three interactive Power BI dashboards focused on:

- Executive performance monitoring
- Operations and revenue analysis
- Temporal and geographic trends
- Resource allocation
- Revenue efficiency
- Customer payment behavior
- Data quality monitoring

The dashboards combine KPIs, comparative visualizations, time-series analysis, geographic analysis, and interactive filtering to support both high-level executive monitoring and deeper analytical exploration.

## 📊 Analytical Insights

Analysis of approximately **49 million transportation records** revealed several operational patterns related to demand, revenue, resource utilization, geographic performance, and data quality.

#### Executive Performance

- Revenue closely follows transaction volume, indicating primarily demand-driven performance.
- Demand patterns remain highly predictable throughout the day.
- Operational activity declines significantly between **1 AM and 7 AM**.
- Manhattan generates the highest concentration of revenue and demand, creating geographic concentration risk.
- Approximately **25%** of payment records contain unknown values, highlighting a meaningful data quality concern.

#### Operations & Revenue

- Revenue aligns with demand, suggesting effective resource allocation across the operating network.
- Queens demonstrates higher revenue efficiency despite lower average trip distances.
- Brooklyn and the Bronx require longer trips to generate comparable revenue.
- A substantial proportion of activity is assigned to unknown geographic locations.
- Payment data inconsistencies occur primarily outside core operating regions.

#### Performance Trends

- Revenue fluctuates more significantly than trip volume, suggesting pricing or trip-composition effects.
- Revenue recovers faster than transaction volume following declines.
- Late-year increases in revenue per trip indicate changing customer or pricing behavior.
- Mid-year performance suggests diminishing marginal revenue per trip.
- Overall business performance trends upward despite noticeable monthly volatility.

## ⚠️ Project Limitations

- The analysis is based on a 12-month historical period and does not capture longer-term multi-year trends.
- Unknown payment and geographic values limit the precision of some customer and regional analyses.
- The dataset captures completed trip activity but does not directly measure unmet demand or vehicle availability.
- Observed relationships between demand, revenue, and geography are descriptive and should not be interpreted as causal.
- External factors such as weather, major events, traffic conditions, and broader economic changes were not incorporated into the analysis.

These limitations do not prevent operational analysis but should be considered when interpreting findings or extending the dashboards for production decision-making.

## 📈 Analytical Recommendations

Based on the analyses:

- Optimize staffing and operational resources around predictable peak-demand periods.
- Investigate the factors contributing to higher revenue efficiency in Queens and evaluate their applicability elsewhere.
- Reduce geographic concentration risk by identifying viable opportunities outside Manhattan.
- Investigate the drivers of revenue volatility beyond transaction volume.
- Develop region-specific operational strategies based on observed performance differences.
- Improve payment and geographic data quality through stronger validation processes.
- Incorporate additional operational and external datasets to strengthen future explanatory and predictive analyses.

## 🛠️ Technical Skills Demonstrated

#### Business Intelligence

- Power BI
- Interactive Dashboard Development
- KPI Design
- Executive Reporting
- Business Storytelling
- Decision Support

#### Data Engineering

- Power Query
- ETL
- Data Cleaning
- Data Transformation
- Feature Engineering
- Data Integration
- Large-Scale Dataset Processing

#### Data Modeling

- Dimensional Modeling
- Star Schema Design
- Fact & Dimension Modeling
- DAX
- Time Intelligence
- Calendar Table Development

#### Data Analysis

- Exploratory Data Analysis (EDA)
- Operational Performance Analysis
- Revenue Analysis
- Trend Analysis
- Temporal Analysis
- Geographic Analysis
- Comparative Analysis
- Resource Allocation Analysis
- Data Quality Assessment

#### Data Visualization

- Interactive Dashboards
- KPI Visualization
- Time-Series Visualization
- Geographic Visualization
- Comparative Business Charts
- Executive Data Storytelling

#### Cloud & Software

- Amazon S3
- Microsoft Power BI
- Power Query Editor
- DAX

## 💡 What This Project Demonstrates

This project demonstrates the ability to independently and rapidly execute an end-to-end Business Intelligence and analytics solution using enterprise-scale structured data.

Specifically, it showcases proficiency in:

- Preparing and transforming tens of millions of records
- Designing scalable analytical data models
- Building dimensional star schemas
- Engineering analytical features from raw operational data
- Developing reusable DAX measures and business KPIs
- Performing operational, temporal, geographic, and revenue analysis
- Building interactive executive dashboards
- Identifying operational opportunities, business risks, and data quality issues
- Translating large datasets into actionable decision-support insights
- Communicating analytical findings through executive reporting
- Delivering a complete analytics solution under tight project timelines

Although transportation data provides the case study, the underlying workflow of **data ingestion → transformation → feature engineering → dimensional modeling → KPI development → analysis → visualization → decision support** is broadly transferable across Data Science, Business Analytics, operations, logistics, healthcare, retail, finance, manufacturing, and other data-driven fields.

## 📁 Repository Structure

```text
Datasets/
│
└── NYC Taxi Dataset
    └── Amazon S3 link to source data

Outputs/
│
├── Power BI Dashboard.pbix
├── Executive Report.pdf
├── Dashboard 1 - Executive Overview.png
├── Dashboard 2 - Operations & Revenue Analysis.png
├── Dashboard 3 - Performance Trends.png
└── Star Schema.png

README.md
```

**Datasets**

Provides access to the approximately **49 million transportation records** used throughout the analysis. The source Parquet files are hosted through **Amazon S3** to support large-scale data storage outside GitHub.

**Outputs**

Contains the complete Business Intelligence solution and supporting deliverables, including:

- Interactive Power BI dashboard
- Executive analytical report
- Dashboard exports
- Star schema visualization

## 📋 Replicating the Project

#### Clone the Repository

```bash
git clone <repository-url>
cd <repository-name>
```

#### Access the Data

Navigate to:

```text
Datasets/
```

and follow the provided **Amazon S3 link** to access the source Parquet datasets.

#### Open the Power BI Solution

Navigate to:

```text
Outputs/
```

and open:

```text
Power BI Dashboard.pbix
```

using **Microsoft Power BI Desktop**.

#### Review the Analytical Workflow

The Power BI solution contains the complete workflow required to explore and reproduce the project, including:

- Data ingestion
- Power Query ETL
- Data cleaning and transformation
- Feature engineering
- Dimensional modeling
- Star schema development
- DAX measures and KPIs
- Interactive dashboard development
- Operational and revenue analysis
- Executive reporting

The supporting files in `Outputs/` provide dashboard exports, the data model visualization, and the final executive report for comparison with the Power BI solution.

## 📬 Contact Me

**Email**

Awaleiabdi@outlook.com

**LinkedIn**

https://www.linkedin.com/in/awale-abdi
