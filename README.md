# 🚆 **UK-Train-Ride Analysis**

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-Database-green?logo=mysql)](https://www.mysql.com/)
[![Power BI](https://img.shields.io/badge/PowerBI-Business%20Intelligence-yellow?logo=microsoft-power-bi)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Excel-Data%20Analysis-brightgreen?logo=microsoft-excel)](https://www.microsoft.com/excel)
[![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-black?logo=github)](https://github.com/)

---

## **📌 Table of Contents**

* [Project Overview](#project-overview)
* [Objectives](#objectives)
* [Scope](#scope)
* [Project Plan](#project-plan)
* [Task Assignment & Roles](#task-assignment--roles)
* [Risk Assessment & Mitigation Plan](#risk-assessment--mitigation-plan)
* [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
* [Technology Stack](#technology-stack)
* [Database Design](#database-design)
* [Expected Deliverables](#expected-deliverables)
* [Final Outcome](#final-outcome)
* [Project Team](#project-team)
* [Instructor](#instructor)
* [Project Files](#project-files)
* [License](#license)

---

## **Project Overview**

This project analyzes historical UK train ride data to uncover ridership patterns, peak travel times, busiest routes, and revenue trends. Using **Excel, SQL, Python, and Power BI**, the project delivers interactive dashboards, predictive models, and actionable insights for operational and strategic planning.

---

## **Objectives**

* Analyze ridership patterns by time, route, and passenger type
* Identify peak hours and busiest routes
* Forecast ridership and revenue trends
* Develop interactive Power BI dashboards
* Provide actionable recommendations based on KPIs

---

## **Scope**

* Historical ridership and revenue data
* Temporal trends: daily, weekly, monthly
* Analysis across routes, stations, and passenger classes

---

## **Project Plan**

| Phase                              | Tasks                                                                                           | Duration | Milestone                |
| ---------------------------------- | ----------------------------------------------------------------------------------------------- | -------- | ------------------------ |
| 1 – Data Collection                | Gather historical ridership, revenue, route, and schedule data                                  | Week 1   | Raw dataset collected    |
| 2 – Data Cleaning & Transformation | Handle missing values, duplicates, standardize formats, merge tables                            | Week 2   | Cleaned dataset ready    |
| 3 – Data Modeling                  | Build relationships between ridership, revenue, routes, and date tables; create calculated KPIs | Week 3   | Data model ready         |
| 4 – Dashboard Development          | Design interactive Power BI dashboards                                                          | Week 4   | First dashboard version  |
| 5 – Review & Refinement            | Validate data, optimize visuals, enhance interactivity                                          | Week 5   | Final polished dashboard |
| 6 – Presentation & Documentation   | Prepare documentation, slides, and present findings                                             | Week 6   | Project completed        |

---

## **Task Assignment & Roles**

| Function                           | Responsibilities                                | Tools                        | Members                            |
| ---------------------------------- | ----------------------------------------------- | ---------------------------- | ---------------------------------- |
| Data Engineering / Preparation     | Clean data, build pipelines, structure datasets | SQL, Python, Excel           | Mohamed Amin, Mohamed Gado         |
| Data Analysis                      | Explore data, identify KPIs, detect trends      | Python, SQL, Excel, Power BI | Zainab Hedaya, Shimaa Mohamed      |
| Data Visualization / BI            | Build dashboards, visual storytelling           | Power BI                     | Kariem Elghandor, Reham Elsaid     |
| Documentation / Project Management | Track deliverables, prepare reports             | —                            | Mohamed Amin (Lead), Zainab Hedaya |

---

## **Risk Assessment & Mitigation Plan**

| Risk                           | Impact              | Mitigation                                 |
| ------------------------------ | ------------------- | ------------------------------------------ |
| Missing ridership/revenue data | Inaccurate insights | Verify with sources; validate completeness |
| Poor data quality              | Skewed KPIs         | Thorough cleaning & preprocessing          |
| Data integration issues        | Wrong calculations  | Standardize IDs, validate joins            |
| Modeling errors                | Misleading insights | Test models, peer review                   |
| Power BI performance issues    | Slow dashboards     | Optimize data model, reduce visuals        |
| Time constraints               | Delays              | Weekly milestones, track progress          |
| Stakeholder misalignment       | Rework              | Share prototypes early, confirm KPIs       |

---

## **Key Performance Indicators (KPIs)**

* Total Ridership (Daily/Weekly/Monthly)
* Revenue per Route & Passenger Class
* Peak Hour Ridership
* Ridership Trend (WoW/MoM)
* Route Utilization Rate
* Forecast Accuracy (MAE, RMSE)

---

## **Technology Stack**

| Tool         | Usage                                                   |
| ------------ | ------------------------------------------------------- |
| **Excel**    | Raw data collection, pivot tables, preliminary analysis |
| **SQL**      | Data extraction, joins, aggregations                    |
| **Python**   | Data cleaning, preprocessing, modeling, visualization   |
| **Power BI** | Dashboards, KPIs, interactive reports                   |
| **GitHub**   | Version control, project collaboration                  |

---

## **Database Design**

**Fact Table:** Fact_Ridership

* Columns: Ridership, revenue, route_id, date_id, passenger_class_id

**Dimension Tables:**

* Dim_Route — Route details
* Dim_Station — Station info
* Dim_Date — Date/time attributes
* Dim_Passenger_Class — Passenger type
* Dim_Revenue_Category — Revenue breakdown

**Schema:** Star schema linking Fact_Ridership to all dimension tables.

---

## **Expected Deliverables**

* Clean and validated ridership dataset
* Star-schema data model in Power BI
* Interactive dashboards with KPIs & forecasts
* Project documentation and presentation slides

---

## **Final Outcome**

A **comprehensive Power BI dashboard** providing actionable insights into UK train ridership patterns, revenue trends, and forecasts to support **data-driven operational and strategic decisions**.

---

## **Project Team**

| Name             | Role                            |
| ---------------- | ------------------------------- |
| Mohamed Amin     | Data Engineering / Project Lead |
| Mohamed Gado     | Data Engineering                |
| Zainab Hedaya    | Data Analysis                   |
| Shimaa Mohamed   | Data Analysis                   |
| Kariem Elghandor | Visualization / BI              |
| Reham Elsaid     | Visualization / BI              |

---

## **Instructor**

[Instructor Name]

---

## **Project Files**

All datasets, Power BI dashboards, Python scripts, and documentation are included in this repository.

---

## **License**

This project is licensed under the **MIT License** – free to use, modify, and share with proper attribution.

---
