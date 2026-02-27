# 🎓 Techmentee 702: College Placement Management Portal (Data Architecture & Analytics)

## 📌 Project Overview
The **College Placement Management Portal** is a comprehensive, role-based platform designed to bridge the gap between students, recruiters, and college placement cells (Admins). 

This repository documents the **data engineering, database architecture, and analytical pipelines** that power the platform. The goal of this project is to transition a fragmented campus hiring process into a centralized, data-driven ecosystem, enabling real-time tracking of student applications, recruiter interactions, and placement metrics.

## 🎯 My Role: Lead Data Analyst
In this project, I am responsible for:
* Defining business logic and key performance indicators (KPIs).
* Designing the relational database schema (Entity-Relationship modeling).
* Implementing application state-tracking logic.
* Designing the ETL (Extract, Transform, Load) pipelines to feed the Admin Analytics Dashboard.

---

## 📂 Repository Structure & Weekly Reports
This repository is structured sequentially to show the lifecycle of the data architecture from conception to execution. 

### 📄 [Week 1: Scope & Business Requirements](./TM702_Wk1_Scope_Strategy.pdf)
* **Focus:** Stakeholder mapping and workflow definitions.
* **Highlights:** Defined the core user personas (Student, Recruiter, Admin), mapped the On-Campus and Off-Campus workflows, and established the primary analytical KPIs (Placement Efficiency, Salary Benchmarks, Pipeline Drop-off).

### 📄 [Week 2: Data Modeling & System Architecture](./TM702_Wk2_Architecture_Modeling.pdf)
* **Focus:** Relational database design and state management.
* **Highlights:** Created the core Entity-Relationship (ER) schema. Implemented a strict State Machine for tracking the `Application_Status` (Applied -> Shortlisted -> Interview -> Offered/Rejected) to accurately measure "Time-to-Hire" and funnel drop-offs.

### 📄 [Week 3: Analytics Pipeline & Preprocessing](./TM702_Wk3_Analytics_Workflow.pdf)
* **Focus:** Data transformation and dashboard readiness.
* **Highlights:** Designed the data preprocessing rules (CGPA normalization, salary standardization, handling nulls) and engineered features like `Skill_Gap_Index` and `Placement_Status_Binary` to feed the final Module 8 Analytics Dashboard.

---

## ⚙️ Core Analytical Features (Module 8)
The data architecture designed in this repository supports the following real-time dashboard metrics:
1. **Placement Percentage by Department:** Tracking the success rate of eligible students.
2. **Financial Metrics:** Calculating Highest, Average, and Median CTC.
3. **Company-wise Selection Rates:** Analyzing which recruiters hire the most candidates.
4. **Unplaced Student Tracking:** Automated flagging of students needing follow-up or interview prep.

---

## 🚀 Next Steps (Upcoming)
* **Week 4:** Deployment of the SQL/Python scripts for the ETL pipeline and User Acceptance Testing (UAT) for the dashboard visualizations.

> *Note: The files linked above contain the detailed technical reports for each phase of the project.*
