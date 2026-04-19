<h1 align="center">NYC Taxi Operations & Revenue Intelligence Dashboard – Power BI Report on Demand, Monetization & Data Quality</h1>

This solo-developed **Power BI analytics project** analyzes ~**49 million records** to uncover patterns in **demand, revenue generation, operational efficiency, and data quality**.

I **built the entire poject in a single day** to validate that I could **rapidly execute a full business intelligence pipeline** from raw data ingestion to executive-level reporting in a real-world setting.

The final project integrates **Amazon S3 (Parquet storage)** with Power BI, applies a **star-schema data model**, and delivers **three interactive dashboards** designed for executive decision-making. The final output includes a **full executive report** highlighting key insights, limitations, and actionable business recommendations.

## 🎯 Objective

To design an end-to-end business intelligence solution that answers:

- How are **trip demand and revenue evolving over time**?
- Is performance driven by **volume or monetization efficiency**?
- Where do **operational inefficiencies** exist across time and geography?
- What **data quality issues** limit visibility and decision-making?

## 📁 Project Scope

- **Execution Approach**:
  - Rapidly done from start of a work day until the end to demonstrate a firm command of Data Analytics & Business Reporting utilizing Power BI
- **Dataset**: NYC Yellow Taxi data (~49M records, 12 months of Parquet files)  
- **Storage**: Amazon S3 (connected to Power BI)  

- **Modeling**:
  - Designed a **star schema** with:
    - 1 Fact Table (`FactTrips`)
    - Dimension tables: Date, Payment Type, Rate Code, Zone Lookup  
  - Created a dynamic **calendar table** using DAX  

- **Data Transformation (Power Query)**:
  - Combined 12 monthly datasets  
  - Engineered key fields:
    - Pickup Date, Pickup Hour, Trip Duration  
  - Cleaned and standardized:
    - Data types, null values, categorical mappings  

- **DAX Measures**:
  - Total Trips  
  - Total Revenue  
  - Avg Revenue per Trip  
  - Avg Trip Distance  
  - Avg Trip Duration  
  - Tip %  
  - KPI formatting for executive readability  

## 📁 Project Structure

- `Datasets`  
  -  Link to parquet datasets

- `Ouputs/`
  - `NYC_Taxi_Operations.pbix` – full Power BI dashboard file 
  - `NYC_Taxi_Executive_Report.pdf` – full executive report
  - Dashboard screenshots (Executive Overview, Operations Analysis, Trends) 

## 🧠 Key Findings from Dashboard Narratives

### **Dashboard 1 – Executive Overview**
- Revenue closely tracks trip volume, indicating **demand-driven performance**  
- Activity declines predictably between **1 AM – 7 AM**  
- Manhattan dominates trips and revenue, indicating **geographic concentration risk**  
- ~25% of payment data is “Unknown,” highlighting **data quality limitations**  

### **Dashboard 2 – Operations & Revenue Analysis**
- Demand and revenue align by hour, suggesting **generally effective resource allocation**  
- **Queens shows higher efficiency**, generating more revenue per trip at lower distances  
- **Brooklyn and the Bronx appear less efficient**, requiring longer trips for similar returns  
- Significant volume attributed to **Unknown/N/A locations**, indicating missing geographic data  
- Payment data gaps are concentrated outside core boroughs, suggesting **inconsistent data capture**  

### **Dashboard 3 – Performance Trends**
- Revenue fluctuates more than trips (~$90M–$135M vs. 3.5M–4.6M), indicating **pricing/trip mix effects**  
- Revenue rebounds faster than demand after dips, suggesting **higher-value trips during recovery**  
- Late-year spike in revenue per trip (~$26 → $31) points to **pricing or trip composition shifts**  
- Mid-year plateau suggests **diminishing marginal revenue per trip**  
- Overall upward trend is strong but masked by **monthly volatility**  

## 📊 Tools & Techniques Used

- 📈 **Power BI** – Dashboard design and modeling  
- 🧼 **Power Query Editor** – ETL and feature engineering  
- 🧩 **DAX** – KPI creation and calculations  
- 🔗 **Star Schema Modeling** – Fact + dimension-based structure  
- ☁️ **Amazon S3** – Data storage

## 🧠 Recommendations Summary

- Improve **pricing consistency** to reduce revenue volatility  
- Optimize operations during **peak demand hours (5–8 PM)**  
- Replicate high-efficiency patterns observed in **Queens**  
- Reduce reliance on Manhattan by identifying growth opportunities elsewhere  
- Address **data quality gaps** in payment and location tracking  
- Implement **borough-specific strategies** based on operational differences  

## 🧠 What This Project Demonstrates

- Ability to execute a **full end-to-end BI pipeline independently**  
- Strong understanding of **data modeling and analytics workflows**  
- Capability to translate data into **clear business insights and decisions**  
- Awareness of **data limitations and real-world constraints**  
- Ability to **reproduce complex workflows efficiently under time constraints**  

## 📝 Contact Me

- **Email**: Awaleiabdi@outlook.com  
- **LinkedIn**: [linkedin.com/in/awale-abdi](https://www.linkedin.com/in/awale-abdi)
