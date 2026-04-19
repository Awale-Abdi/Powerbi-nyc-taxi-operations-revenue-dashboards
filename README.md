<h1 align="center">NYC Taxi Operations & Revenue Intelligence Dashboard – Power BI Report on Demand, Monetization & Data Quality</h1>

This solo-developed **Power BI dashboard** analyzes ~**47 million NYC taxi trips** to uncover patterns in **demand, revenue generation, operational efficiency, and data quality**. The project was built using a **structured, reproducible workflow** that can be executed within **1–2 days**, demonstrating strong command over **data modeling, ETL processes, and executive-level dashboard design**.

The solution integrates **Amazon S3 (Parquet storage)** with Power BI, applies a **star-schema data model**, and delivers **three interactive dashboards** designed for executive decision-making. The final output includes a **full executive report**, highlighting key insights, limitations, and actionable business recommendations.


## 🎯 Objective

To design an end-to-end business intelligence solution that answers:

- How are **trip demand and revenue evolving over time**?
- Is performance driven by **volume or monetization efficiency**?
- Where do **operational inefficiencies** exist across time and geography?
- What **data quality issues** limit visibility and decision-making?

---

## 📁 Project Scope

- **Timeline**: Built using a streamlined workflow (reproducible in 1–2 days)  
- **Dataset**: NYC Yellow Taxi data (~47M records, multi-month Parquet files)  
- **Storage**: Amazon S3 (connected to Power BI)  
- **Modeling**:
  - Designed a **star schema** with:
    - 1 Fact Table (`FactTrips`)
    - Dimension tables: Date, Payment Type, Rate Code, Zone Lookup
  - Created a dynamic **calendar table** using DAX
- **Data Transformation (Power Query)**:
  - Combined 12 monthly datasets
  - Extracted key fields:
    - Pickup Date, Pickup Hour, Trip Duration
  - Cleaned and standardized:
    - Data types, null values, categorical mappings
- **DAX Measures**:
  - Total Trips
  - Total Revenue
  - Revenue per Trip
  - Avg Trip Distance
  - Avg Trip Duration
  - Tip %
  - Built formatted KPI measures for executive readability

---

## 📁 Project Structure

- `dashboard/`  
  - `NYC_Taxi_Operations.pbix` – full Power BI dashboard file with model and visuals  

- `assets/`  
  - Dashboard screenshots (Executive Overview, Operations Analysis, Trends)  

- `report/`  
  - `NYC_Taxi_Executive_Report.pdf` – full executive report with insights and recommendations  

- `data-notes/`  
  - Data dictionary and transformation notes  

---

## 🧠 Key Findings from Dashboard Narratives

### **Dashboard 1 – Executive Overview**
- Revenue closely tracks trip volume, indicating reliance on **demand-driven performance**  
- Activity drops predictably between **1 AM – 7 AM**, confirming expected usage patterns  
- Manhattan dominates trips and revenue, indicating **geographic concentration risk**  
- ~25% of payment data is “Unknown,” highlighting **data quality limitations**  

---

### **Dashboard 2 – Operations & Revenue Analysis**
- Demand and revenue align strongly by hour, suggesting **effective resource allocation**  
- **Queens shows higher efficiency**, generating more revenue per trip at lower distances  
- **Brooklyn and the Bronx appear less efficient**, requiring longer trips for similar returns  
- A large share of trips fall under **Unknown/N/A locations**, indicating missing geographic data  
- Payment data gaps are concentrated outside Manhattan and Queens, suggesting **inconsistent data capture**  

---

### **Dashboard 3 – Performance Trends**
- Revenue fluctuates more than trips (~$90M–$135M vs. 3.5M–4.6M), indicating **pricing/trip mix impact**  
- Revenue rebounds faster than demand after dips, suggesting **higher-value trips during recovery**  
- Late-year spike in revenue per trip (~$26 → $31) points to **pricing or trip composition changes**  
- Mid-year plateau suggests **diminishing marginal revenue per trip**  
- Overall upward trend is strong but masked by volatility  

---

## 📊 Tools & Techniques Used

- 📈 **Power BI** – Dashboard design, modeling, and visualization  
- 🧼 **Power Query Editor** – ETL, data transformation, feature engineering  
- 🧩 **DAX** – KPI creation, measures, and calculated columns  
- 🔗 **Star Schema Modeling** – Fact + dimension-based semantic model  
- ☁️ **Amazon S3** – Data storage and access (Parquet format)  

---

## 🧠 Recommendations Summary

- Improve **pricing consistency** to reduce revenue volatility  
- Optimize operations during **peak demand hours (5–8 PM)**  
- Replicate high-efficiency patterns observed in **Queens**  
- Reduce reliance on Manhattan by identifying growth opportunities elsewhere  
- Address **data quality gaps** by improving payment and location tracking systems  
- Implement **borough-specific strategies** based on operational differences  

---

## 🧠 What This Project Demonstrates

- End-to-end BI pipeline (data ingestion → modeling → insights)  
- Strong understanding of **data modeling and relationships**  
- Ability to translate data into **clear business insights and recommendations**  
- Awareness of **data limitations and quality issues**  
- Clean, executive-level dashboard design and storytelling  

---

## 📝 Contact Me

- **Email**: Awaleiabdi@outlook.com  
- **LinkedIn**: [linkedin.com/in/awale-abdi](https://www.linkedin.com/in/awale-abdi)
