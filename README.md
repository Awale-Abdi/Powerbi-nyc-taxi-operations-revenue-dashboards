<h1 align="center">Operational Performance Analytics | End-to-End Business Intelligence with Power BI</h1>


This project showcases an **end-to-end Business Intelligence workflow** built using approximately **49 million transportation records**. I developed it to demonstrate enterprise-scale data preparation, dimensional modeling, KPI development, dashboard design, and executive reporting.

Although the project uses the **NYC Yellow Taxi dataset** as its case study, the Business Intelligence techniques I apply such as data transformation, dimensional modeling, KPI development, interactive dashboard design, and analytical reporting are broadly transferable to operations, logistics, healthcare, retail, finance, manufacturing, and other data-driven organizations seeking to transform large datasets into actionable business insights.

Using **Amazon S3**, **Power Query**, **DAX**, and **Power BI**, I designed and delivered a complete Business Intelligence solution capable of answering strategic operational questions, improving resource allocation, monitoring business performance, and supporting executive decision-making through interactive dashboards and analytical reporting.

To challenge myself, I completed the entire project over **two standard working days (9–5)**, demonstrating my ability to rapidly execute an end-to-end Business Intelligence workflow from raw data ingestion through executive-ready reporting.

## 💼 Executive Questions

The project simulates requests from an executive leadership team responsible for improving operational performance, resource allocation, revenue generation, and data quality:

- How are demand and revenue trending over time?
- Is business performance driven primarily by transaction volume or revenue efficiency?
- When does peak operational demand occur, and are resources aligned accordingly?
- How does operational performance vary across regions?
- Which operational areas appear inefficient or underperforming?
- What customer payment behaviors are most common?
- Are there data quality issues impacting business decisions?

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
Executive Reporting
```
### Data

- **Dataset:** NYC Yellow Taxi Trips
- **Size:** ~49 million records
- **Period:** 12 months
- **Format:** Parquet
- **Storage:** Amazon S3

Dataset:

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

### Data Modeling

Designed a dimensional **Star Schema** consisting of:

- **1 Fact Table**
  - FactTrips

- **Dimension Tables**
  - Date
  - Payment Type
  - Rate Code
  - Zone Lookup

Created a dynamic **Calendar Table** using DAX to support time intelligence.

### Data Engineering (Power Query)

Performed enterprise-style ETL by:

- Combining 12 monthly datasets
- Standardizing data types
- Cleaning null values
- Engineering new analytical fields:
  - Pickup Date
  - Pickup Hour
  - Trip Duration
- Standardizing categorical values
- Preparing the data model for reporting

### KPI Development (DAX)

Created business KPIs including:

- Total Trips
- Total Revenue
- Revenue per Trip
- Average Trip Distance
- Average Trip Duration
- Tip Percentage
- Executive KPI formatting

## 📁 Repository Structure

```
Datasets/
    NYC Taxi Dataset (Amazon S3)

Outputs/
    Power BI Dashboard.pbix
    Executive Report.pdf
    Dashboard 1 - Executive Overview.png
    Dashboard 2 - Operations & Revenue Analysis.png
    Dashboard 3 - Performance Trends.png
    Star Schema.png
```

## 📊 Operational Insights

### Executive Overview

- Revenue closely follows transaction volume, indicating demand-driven performance.
- Demand patterns remain highly predictable throughout the day.
- Operational activity declines significantly between **1 AM and 7 AM**.
- Manhattan generates the highest concentration of revenue and demand, creating geographic concentration risk.
- Approximately **25%** of payment records contain unknown values, highlighting a meaningful data quality concern.

### Operations & Revenue Analysis

- Revenue aligns closely with demand, suggesting generally effective operational resource allocation.
- Queens demonstrates higher revenue efficiency despite lower average trip distances.
- Brooklyn and the Bronx require longer trips to generate comparable revenue.
- A substantial proportion of activity is assigned to unknown geographic locations.
- Payment data inconsistencies occur primarily outside core operating regions.

### Performance Trends

- Revenue fluctuates more significantly than trip volume, suggesting pricing or trip composition effects.
- Revenue recovers faster than transaction volume following declines.
- Late-year increases in revenue per trip indicate changing customer or pricing behavior.
- Mid-year performance suggests diminishing marginal revenue per trip.
- Overall business performance trends upward despite noticeable monthly volatility.

### 📈 Executive Recommendations

- Improve pricing consistency to reduce revenue volatility.
- Optimize staffing and operational resources during peak demand periods.
- Investigate operational practices contributing to higher efficiency in Queens.
- Reduce geographic concentration risk by identifying opportunities outside Manhattan.
- Improve payment and geographic data quality through stronger validation processes.
- Develop region-specific operational strategies based on observed performance differences.

## 🛠️ Technical Skills Demonstrated

### Business Intelligence

- Power BI Dashboard Development
- KPI Design
- Executive Reporting
- Business Storytelling
- Decision Support

### Data Engineering

- Power Query
- ETL
- Data Cleaning
- Data Transformation
- Feature Engineering
- Large-scale Dataset Preparation

### Data Modeling

- Star Schema Design
- Fact & Dimension Modeling
- DAX
- Time Intelligence
- Calendar Table Development

### Analytics

- Operational Performance Analysis
- Revenue Analysis
- Trend Analysis
- Resource Allocation Analysis
- Geographic Performance Analysis
- Data Quality Assessment

### Cloud Technologies

- Cloud-based Data Storage via Amazon S3

## 💡 What This Project Demonstrates

This project demonstrates the ability to independently and rapidly execute a complete Business Intelligence solution from raw data through to executive decision support.

Specifically, it showcases proficiency in:

- Designing scalable Business Intelligence workflows
- Building enterprise-ready dimensional data models
- Developing executive dashboards and KPIs
- Performing enterprise-scale ETL using Power Query
- Translating large datasets into actionable business insights
- Identifying operational opportunities and business risks
- Communicating analytical findings through executive reporting
- Delivering end-to-end analytics solutions under tight project timelines

## 📬 Contact

**Email**

Awaleiabdi@outlook.com

**LinkedIn**

https://www.linkedin.com/in/awale-abdi
