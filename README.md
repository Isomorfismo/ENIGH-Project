# 📊 Salary Income Prediction in Mexican Households - ENIGH

This project aims to predict salary-based income in Mexican households using data from the National Survey of Household Income and Expenditure (ENIGH). A statistical regression approach is employed to estimate income based on sociodemographic and labor-related variables. The analysis seeks to generate useful insights for public policy design and socioeconomic research.

---

## ❗ Problem Statement

In Mexico, income inequality remains one of the major challenges to inclusive economic growth. Salary-based income, as a key component of household income, varies widely depending on education, occupation, location, and other sociodemographic factors. Despite ongoing social and economic policies, disparities persist and limit access to decent work and economic opportunities.

Understanding and predicting income levels can help:
- Identify vulnerable population groups.
- Support evidence-based public policy.
- Promote fair and inclusive labor practices.

---

## 🎯 Objectives

- Build a predictive model to estimate household salary income using ENIGH data.
- Analyze key sociodemographic variables that influence income distribution.
- Generate actionable insights aligned with the UN Sustainable Development Goals (SDGs).
- Contribute to the design of policies focused on reducing income inequality.

---

## 🌍 Sustainable Development Goals (SDGs)

This project aligns with the following **United Nations SDGs**:

- **SDG 1:** No Poverty  
- **SDG 8:** Decent Work and Economic Growth  
- **SDG 10:** Reduced Inequalities  

It aims to provide data-driven evidence to design better labor and income policies and promote equitable access to economic growth.

---


## 🧠 Technologies & Tools

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab
- Data visualization libraries
- ENIGH microdata

---

## 🔍 Project Structure


![](img/Interface.png)


## 📉 Income Inequality in Mexico

According to OECD and INEGI data:
- The **Gini coefficient** in Mexico is among the highest in the OECD (approx. 0.45–0.48).
- The **top 10%** of households earn more than **30 times** what the bottom 10% earn.
- Informal labor and unequal access to education significantly impact wage distribution.

These factors make it essential to model and understand income determinants to propose targeted interventions.

---

## 📊 Exploratory Data Analysis (EDA)

Key steps included:
- Cleaning and preprocessing ENIGH microdata.
- Generating visualizations by region, gender, occupation, and education.
- Detecting outliers and normalizing salary distributions.
- Correlation matrix to evaluate variable influence.

Findings:
- Education level shows a strong positive correlation with income.
- Rural zones report significantly lower incomes.
- Gender disparities persist, with females earning less on average.

---

## 🤖 Predictive Model

We implemented a regression-based model to estimate household salary income:

- **Models Used:**
  - Linear Regression
  - Polynomial Regression
  - (Optional) Decision Tree Regressor, Random Forest
  
- **Target variable:** `household_salary_income`
- **Features:** education level, occupation, age, gender, region, number of employed members, etc.

The dataset was split into training and test sets using `train_test_split` with `random_state=0`.

Performance Metrics:
- MAE, MSE, R² Score
- Visualization of predicted vs. actual values

---

## 📈 Results

- **Linear Regression R² Score:** 0.67 (training) / 0.64 (test)  
- **Polynomial Regression improved prediction for higher-income households.**
- Key predictors: education, urban/rural classification, number of employed members, and type of occupation.

These results can help identify structural factors driving inequality and inform proactive policies.

---

## ✅ Model Benefits

- Enables **early identification** of low-income households.
- Assists policymakers in **targeting resources and social programs**.
- Supports **research in labor economics and inequality**.
- Can be **extended** to include other income types (e.g., transfers, self-employment).

---

## 📌 Project Summary

- **Data source:** ENIGH (INEGI, Mexico)  
- **Problem type:** Regression  
- **Algorithms used:** Linear Regression, Polynomial Regression, and other optional models  
- **Key variables:** Education, occupation, age, region, gender, number of employed household members, etc.  
- **Objective:** Estimate household salary income in Mexico  
- **Application:** Economic analysis, public policy design, inequality reduction (aligned with SDGs 1, 8, and 10)

---
## 📌 Conclusions

This project demonstrates that salary-based income can be reasonably predicted using sociodemographic and labor variables. The findings highlight persistent inequality factors in Mexico, such as education gaps and labor informality. Predictive modeling can serve as a tool for decision-making in public policy, supporting more targeted and equitable economic strategies.

---


### Collaborators
* Piña Del Valle José
* Arias Morales Yahir
* [@Isomorfismo](https://github.com/Isomorfismo)
* Rivera García Axel Maximiliano
