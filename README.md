# 🏥 TruBridge Healthcare Data Analytics | Externship Capstone

![Python](https://img.shields.io/badge/Python-3873A9?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

An end-to-end healthcare data analytics evaluation examining public health indicators and Social Determinants of Health (SDOH) across **2,300+ U.S. counties**. This project evaluates the impact of household food insecurity on chronic disease prevalence (specifically adult diabetes) to inform population health strategies for **TruBridge**.

---

## 📌 Executive Summary

Healthcare leadership and clinical providers require data-driven strategies to identify vulnerable populations and address health disparities before they result in acute clinical outcomes. 

This project synthesizes national CDC health outcome data and USDA economic/food security metrics across 2,300 non-overlapping U.S. counties. By applying Ordinary Least Squares (OLS) regression and quantile risk tiering, the analysis quantifies the extent to which food insecurity drives regional diabetes prevalence and outlines **3 actionable clinical interventions** for TruBridge leadership.

---

## 📊 Key Findings

* **Strong Linear Correlation:** Identified a clear positive linear relationship between county-level household food insecurity rates and adult diabetes prevalence.
* **Variance Explanation:** OLS regression modeling demonstrated that household food insecurity accounts for **59.6% ($R^2 = 0.5964$)** of the geographic variance in adult diabetes rates across the analyzed counties.
* **Risk Tier Disparities:** Quantile risk stratification revealed a significant **4.36 percentage point gap** in adult diabetes prevalence between the lowest-risk and highest-risk county cohorts.
* **Geographic Hotspots:** High-burden chronic disease corridors were heavily concentrated across Southeastern U.S. states (including state-level averages such as Mississippi at 17.2% and West Virginia at 17.0%).

---

## 💻 Interactive Web Dashboard & Deliverables

> 🔗 **[View Interactive Dashboard & Project Site](https://sridhar-trubridge-analytics-project.netlify.app/)**

---

## 📁 Project Structure

```text
├── index.html          # Web presentation dashboard & interactive site
├── README.md           # Project documentation
├── dashboard-images/   # High-resolution chart assets and visualizations
└── project 5/          # Analysis scripts, data models, and notebooks
