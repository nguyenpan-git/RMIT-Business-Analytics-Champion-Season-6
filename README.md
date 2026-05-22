# OEE Optimization & Root Cause Analysis - Colgate-Palmolive 🏭

## Project Overview
This repository contains the solution for the **RMIT Business Analytics Champion Season 6 (Top 30)** by Team *THE TORTURED ANALYST DEPARTMENT*. The project analyzes production and maintenance data to identify key Overall Equipment Effectiveness (OEE) loss drivers, quantify business impact, and propose data-driven maintenance strategies for Colgate-Palmolive.

## Key Highlights
* **Large-scale Data Analysis:** Processed and synthesized a complex dataset of over 168,000 production logs (MES) and 194 maintenance orders (CMMS) to evaluate the Overall Equipment Effectiveness (OEE) for Colgate-Palmolive's production lines.
* **Root Cause Analysis:** Applied statistical testing (Chi-square, Cramér's V) and built Error-Product frequency matrices to isolate impact factors. Successfully proved that production errors stemmed from equipment wear and material characteristics (high Cramér's V) rather than human factors (Cramér's V ~ 0.03).
* **Business Impact Quantification:** Pinpointed hidden operational bottlenecks, isolating 21,196 hours of unplanned downtime and discovering 1,161 hours of untracked "No-Production" runtime. Clarified the root causes leading to a 19.8% loss in effective capacity (equivalent to 7.2 million units).
* **AI & Analytics Strategy:** Designed a deployment roadmap for machine learning models and real-time monitoring (Anomaly Detection & Predictive Maintenance) to resolve physical bottlenecks, aiming to recover 10% of the OEE.

## Repository Structure
* `Datasets/`: Contains both the raw and cleaned MES/CMMS datasets used for analysis.
* `Notebooks/`: Notebooks containing data preprocessing, Exploratory Data Analysis (EDA), and statistical testing implementations.
* `[RBAC 2025] CASE STUDY ROUND 2.pdf`: The original case study prompt and business requirements.
* `THE TORTURED ANALYST DEPARTMENT_Round 2_RBAC 2025.pdf`: The final presentation deck detailing the methodology, insights, and recommendations.

* ## External Assets
Due to GitHub's file size limitations, the datasets file are hosted securely on Google Drive.

* 🔗 **[Data Folder (Google Drive)](https://drive.google.com/drive/folders/1HeXNG2jq1WGtF9jUcVM4A3XVEHTevQoE?usp=sharing)**: Contains the original masked CSV datasets.
