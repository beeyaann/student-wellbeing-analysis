# Questionnaire Analysis on Student Physical & Mental Health

## 📋 Project Overview

This project was conducted as part of the **Statistical Inference & Data Analysis** course.
It aims to explore the relationship between **academic workload** and **student wellbeing** through quantitative analysis based on questionnaire data.

A total of **125 responses** were collected, and a **stratified random sampling** technique was applied to select 62 representative samples from different academic years.

## 🎯 Objectives

* To identify key factors influencing students’ physical and mental health.
* To measure the impact of academic and non-academic activities on wellbeing.
* To provide data-driven insights that can guide institutional support programs.

## 🧮 Methods

1. **Factor Analysis**

   * Kaiser-Meyer-Olkin (KMO) = **0.77**, indicating sampling adequacy.
   * Bartlett’s Test: **Significant (p < 0.05)**, confirming data suitability.
   * Extracted **3 main factors** after rotation using **Varimax**.

     * **Factor 1:** Physical and psychological health affected by academic pressure.
     * **Factor 2:** Balance between personal life and academic activities.
     * **Factor 3:** Psychological pressure from non-academic activities.
   * Total variance explained: **48.6%**.

2. **ANOVA & Post-hoc Tukey’s HSD**

   * Compared mean scores among **high**, **medium**, and **low** groups for each factor.
   * All three factors showed **significant differences (p < 0.05)** between groups, confirming the influence of academic and extracurricular pressures on student wellbeing.

## 📊 Key Insights

* **High academic pressure** significantly reduces both physical and mental health.
* **Students who maintain life balance** report higher satisfaction and lower stress levels.
* **Active involvement in organizations or extracurriculars** can increase psychological pressure if not managed well.
* Majority of respondents (**65.3%**) reported that academic activities have *no major negative impact*, while **12.1%** experienced *negative effects* on their health.

## 📈 Results Visualization

A Tableau dashboard was created to visualize the findings interactively.
🔗 **[https://public.tableau.com/app/profile/azalia.fitriana/viz/DashboardSurvei_17314179519590/Dashboard1?publish=yes]**

## 🧩 Tools & Technologies

* **Python** – Data preprocessing, Factor Analysis, ANOVA
* **Pandas, NumPy, SciPy, Statsmodels** – Statistical computation
* **Matplotlib, Seaborn** – Data visualization
* **Tableau** – Interactive dashboard
* **Excel/Google Sheets** – Initial data cleaning

## ✅ Conclusions

* The study successfully identified **three significant latent factors** affecting student wellbeing.
* Academic and non-academic pressures play a **statistically significant role** in shaping physical and psychological health.
* Data-driven interventions are recommended, such as:

  * Adjusting academic workload distribution.
  * Implementing time management workshops.
  * Providing mental health support and counseling programs.
