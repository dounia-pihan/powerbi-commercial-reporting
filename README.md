# 📊 Power BI Sales Performance Report *(enterprise project)*

End-to-end **Power BI reporting solution** for sales, replacing a manual Excel/PivotTable workflow with an **automated, industrialized, and centralized system**.  
This repository showcases the technical architecture and anonymized report screenshots. 

---

![Python](https://img.shields.io/badge/SQL-Data%20Queries-blue)
![Power Query](https://img.shields.io/badge/ETL-Power%20Query-green)
![DAX](https://img.shields.io/badge/DAX-%20Measures-orange)
![Model](https://img.shields.io/badge/Model-Star%20Schema-lightgrey)
![Security](https://img.shields.io/badge/RLS-Row%20Level%20Security-red)
![UX](https://img.shields.io/badge/UX-Optimized%20Design-purple)
![App](https://img.shields.io/badge/Deployment-Power%20BI%20App-brightgreen)
![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-yellow)


---

## ⚠️ **Note**  
This repository contains **documentation and anonymized report screenshots**.  
No real company data is included: all screenshots are anonymized and connected to local Excel files instead of the production database.


---

## Context & Objectives
- **Before**:  
  - Sales data consolidated manually by **two employees** across **two separate networks**.  
  - Lengthy and repetitive monthly processing in Excel/PivotTables.  
  - Distribution via email or SharePoint → fragmented and limited visibility for sales directors and field reps.  

- **After** *(what I have done)*:  
  - Design and development of **two twin Power BI reports**, one for each network, built on the same model → **scalability and consistency**.  
  - Creation of a **dedicated Power BI App** centralizing this report and other dashboards → a **single access point** for the entire sales force.  
  - Outcome: strong adoption, report used **daily** by the entire sales organization.
    
---

## Technical Achievements
- **ETL & Data Modeling**  
  - SQL connections (via MyReport).
  - Data cleaning, normalization, and structuring with **Power Query**.  
  - Implementation of a **star schema model** (Sales Fact ↔ Product, Customer, Region, Date dimensions).  

- **DAX & KPI Design**  
  - Development of a comprehensive set of DAX measures convering:  
    - **Financial indicators**: Total Sales, YTD Sales, MTD Sales, etc.  
    - **Operational indicators**: Total/YTD/MTD Volumes, weights, shares, etc.  
    - **Comparative indicators**: Year-over-Year growth, monthly and cumulative growth, etc.  
  - **Clean, ergonomic design**: smooth navigation, clear visual hierarchy, emphasis on key KPIs.  

- **Security & Governance**  
  - **Row Level Security (RLS)**:  
    - Directors → full access.  
    - Sales reps → restricted to their region and neighboring regions.  
  - Delivery of technical documentation and user guide to support industrialization.  

- **UX & Distribution**  
  - Roll-out of **two identical reports** for two separate data networks → consistency and industrialization.  
  - Integration into a **Power BI App** for centralized distribution and governance.  
  - Enhanced user experience: bookmarks, drillthrough, tooltips, and UX tailored for field usage.

---

## 🎯 Business Impact
- **Productivity**: eliminated manual monthly processing.  
- **360° Sales View**: analysis by product, client, region, and period.  
- **Decision Support**: evolution and variance KPIs used to identify priority clients/products and guide field sales actions.  
- **Adoption**: integrated into daily workflows, widely used by the entire sales force.

---

## Preview
*(only anonymized screenshots are shared)*

---

## Tech Stack
- **Power BI Desktop** – development of the data model, DAX measures, and report design.  
- **Power BI Service** – cloud deployment, scheduled refresh, workspace and access management.  
- **Power Query (M)** – data cleaning, normalization, and structuring.  
- **SQL (MyReport)** – filtered queries for optimized data retrieval.  
- **DAX** – financial, operational, and comparative KPIs.   
- **Power BI App** – centralized distribution and governance of reports.

---

## Documentation
-


---

## License

Creative Commons Attribution 4.0 International License (CC-BY 4.0).

---

## Credits
Project delivered in a professional context by **PIHAN Dounia – Data Analyst**.  
Supervised by the BI manager and validated by business stakeholders.  

---

## Links


