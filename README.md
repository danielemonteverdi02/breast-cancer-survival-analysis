# Breast Cancer Survival Analysis

## 📊 Project Overview

This project analyzes breast cancer patient survival using statistical methods and interactive dashboards.

The goal is to identify key factors affecting survival and to present insights through both:

* a **Power BI dashboard**
* a **statistical analysis in R**

---

## 🎯 Objectives

* Analyze survival patterns of breast cancer patients
* Identify significant predictors of survival
* Compare different statistical approaches (Kaplan-Meier, Cox model)
* Build an interactive dashboard for data exploration

---

## 📁 Dataset

The dataset is based on the **SEER (Surveillance, Epidemiology, and End Results)** program.

It includes:

* Demographic variables (age, ethnicity, marital status)
* Clinical variables (tumor size, stage, lymph nodes)
* Biomarkers (estrogen, progesterone)
* Survival time and event indicator

---

## 🧪 Methods

### Survival Analysis

* Kaplan-Meier estimator
* Log-rank test

### Regression Models

* Cox proportional hazards model
* Multivariate Cox regression
* Stratified Cox model
* Time-varying effects

### Feature Engineering

* LODDS (log-odds of positive lymph nodes)

---

## 📈 Key Findings

* Lymph node involvement (LODDS) is one of the strongest predictors of survival
* Hormonal receptors (estrogen, progesterone) significantly affect prognosis
* The proportional hazards assumption is not always satisfied
* Time-varying effects improve model interpretation

---

## 📊 Dashboard

The Power BI dashboard provides:

* Interactive filtering (e.g., estrogen status)
* Survival rate comparisons
* Patient distribution analysis

---

## 🛠 Tools & Technologies

* R (survival, survminer, tidyverse)
* Power BI

---

## 📌 Notes

This project was developed as a self-learning exercise to improve:

* data analysis skills
* survival modeling
* data visualization with Power BI
