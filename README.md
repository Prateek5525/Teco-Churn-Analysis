# Teco Customer Churn Analysis

[Exploratory Data Analysis Project]

This repository contains an analysis of customer churn patterns for Teco, a telecommunications company. The goal of this project is to identify key factors influencing customer churn and provide actionable insights to improve customer retention strategies. This analysis focuses on variables like payment methods, contract types, tenure, and demographic attributes.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Insights](#data-insights)
- [Dashboard](#dashboard)
- [Key Findings and Recommendations](#key-findings-and-recommendations)
- [Installation and Setup](#installation-and-setup)
- [License](#license)

## Project Overview

**Objective**: This project investigates customer churn at Teco. By analyzing various customer characteristics, this project aims to highlight factors that increase churn risk and recommend retention strategies.

The project consists of:
1. Data preprocessing and analysis.
2. A Jupyter Notebook (`TCA.ipynb`) with code for visualization and analysis.
3. A PDF dashboard summarizing findings with visualizations.
4. Recommendations for reducing customer churn.

## Data Insights

The main insights from the analysis are as follows:

1. **Contract Type**: 
   - Month-to-month contracts have a churn rate of 42%, significantly higher than yearly (11%) and two-year contracts (3%).

2. **Payment Method**:
   - Electronic check users have a high churn rate at 45%, while other methods like credit card, bank transfer, and mailed check range between 15-18%.

3. **Customer Tenure**:
   - Churn is highest (50%) among customers with less than a year of tenure, dropping to 35% for 1-3 years, and 15% for those beyond three years.

4. **Internet Service Type**:
   - Fiber Optic service users show a 30% churn rate, compared to DSL users at 20%.

5. **Demographics**:
   - Senior citizens (aged 65+) have a churn rate of 41%, while non-senior customers have a churn rate of 26%.

## Dashboard

A comprehensive PDF dashboard is included, which visualizes these insights and provides a summary of actionable recommendations. The dashboard includes:

- **Churn Rate by Contract Type**
- **Churn Rate by Payment Method**
- **Churn Rate by Customer Tenure**
- **Churn Rate by Internet Service Type**
- **Churn Rate by Age Group**

## Key Findings and Recommendations

**Key Findings:**
-Customers on month-to-month contracts and using electronic checks exhibit higher churn rates.
-New customers (with less than a year of tenure) have the highest churn risk.
-Fiber Optic service users are more likely to churn than DSL users.
-Senior citizens have a higher churn rate than younger customers.

**Recommendations:**
-Promote Long-Term Contracts: Offer incentives to encourage customers to opt for longer contracts.
-Address Payment Method Concerns: Encourage customers to switch from electronic checks to more secure options.
-Customer Engagement in Early Tenure: Focus on improving customer experience within the first year.
-Targeted Programs for Senior Citizens: Implement loyalty programs for senior customers to improve retention.

## Installation and Setup

1. **Clone this repository**:
   ```bash
   git clone https://github.com/Prateek5525/Teco-Customer-Churn-Analysis.git
   cd Teco-Customer-Churn-Analysis
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook TCA.ipynb

## License   
**This project is licensed under the MIT License.**
---
