# Telecom-Customer-Churn-Analysis-in-Power-BI

## Overview
Customer churn refers to the percentage of customers who discontinue their services within a specific period. In the telecommunications industry, customer churn is a significant business concern because losing existing customers can reduce revenue, increase customer acquisition costs, and affect long-term business growth.

This project explores customer churn patterns using Microsoft Power BI to identify customer segments associated with higher attrition and investigate the factors that may influence customer retention. By transforming customer data into interactive visualizations and performance indicators, the project demonstrates how data analytics can help businesses understand customer behavior, identify potential retention risks, and make more informed decisions.

### The Business Problem
How can a telecommunications company use customer data to better understand churn patterns and develop targeted strategies to improve customer retention?

### Project Objectives
- Measure customer churn and establish key performance indicators.
- Identify customer segments with comparatively higher churn rates.
- Investigate the relationship between customer churn and billing-related factors.
- Build an interactive dashboard to communicate findings effectively.
- Translate analytical observations into practical business recommendations.

## Table of Contents
- [Overview](#overview)
- [Methodology](#methodology)
- [Business Insights](#business-insights)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

## Methodology
The project followed a structured data analytics workflow, from data preparation to visualization and business recommendations. 

### Phase 1: Data Preparation
The first step involved examining the customer dataset to understand its structure, available variables, and suitability for churn analysis.
The dataset included customer-related attributes such as tenure, contract type, monthly charges, total charges, demographic information, and churn status. These variables were used to explore differences between customers who remained with the company and those who discontinued their services.

Power Query was used to prepare the dataset for analysis.
- Reviewed the dataset structure and relevant customer attributes.
- Checked data types, missing values, and inconsistent classifications.
- Used Power Query to transform and organize data.
- Grouped relevant categories, including contract types and customer age ranges, where appropriate.

### Phase 2: KPI Development
DAX measures were created to calculate key performance indicators for monitoring customer churn.

The primary KPIs included:

- Total Customers: The number of distinct customers in the dataset.
- Number of Churned Customers: The number of customers classified as churned.
- Churn Rate: The proportion of customers who churned relative to the total customer population.

The churn rate was calculated using the following formula:
```
Churn Rate = 
[Number of Churned Customers]/[Number of Customers]
```

### Phase 3: Exploratory Data Analysis
Exploratory data analysis was conducted to identify patterns and potential factors associated with customer churn.
The analysis focused on the following dimensions:

| Analytical Dimension | Business Question |
|----------------------|-------------------|
| Contract Type | Do customers on month-to-month contracts have higher churn rates? |
| Contract Category | Are newer customers more likely to leave? |
| Monthly Charges | Does churn vary across different billing levels? |
| Customer Demographics | Are there differences in churn across customer groups? |
| Subscription | Does churn vary according to the services customers use? |

Charts and visual comparisons were used to make the results easier to interpret and to identify customer segments that may require further investigation.

### Phase 4: Dashboard Development
An interactive Power BI dashboard was developed to present the analysis in a clear and accessible format.

The Power BI dashboard incorporated KPI cards, donut charts, bar charts, and customer segmentation visuals to communicate the results.

The dashboard was designed to help users:

- Monitor overall churn performance.
- Compare customer segments.
- Explore patterns across contracts and customer characteristics.
- Interpret the data to support retention planning.

## Business Insights
The following are the primary analytical questions investigated in the project. 








## Recommendations
Based on the analytical dimensions explored in this project, the following recommendations can be considered. 

### 1. Strengthen Retention Strategies for Month-to-Month Customers
If the analysis confirms that month-to-month customers have higher churn rates than customers on longer-term contracts, the business should investigate why these customers are more likely to leave.

Potential initiatives include offering transparent annual-plan incentives, loyalty benefits, or flexible packages that provide additional value without placing excessive pressure on customers to commit to longer contracts.

Use segment-level churn rates to identify customer groups that may require additional engagement, support, or retention incentives.

### 2. Improve the Early Customer Experience
If customers with shorter tenure show higher churn rates, the business should prioritize onboarding and early engagement.

Recommended initiatives include providing clear setup guidance, proactive customer support, early satisfaction surveys, and follow-up communications to identify issues before customers decide to leave.

Monitoring retention during the initial stages of the customer relationship may help the business detect problems earlier and intervene more effectively.

### 3. Review Pricing and Billing Experience
If higher churn is observed among customers with relatively high monthly charges, the company should investigate whether pricing, perceived value, unexpected fees, or unsuitable service packages contribute to dissatisfaction.

Possible actions include reviewing pricing transparency, offering suitable package alternatives, and communicating the benefits associated with different plans.

However, higher monthly charges should not automatically be interpreted as the cause of churn. Further investigation is necessary to distinguish pricing concerns from other customer characteristics.

### 4. Monitor Churn Performance Continuously
The Power BI dashboard should be used as part of an ongoing monitoring process rather than as a one-time reporting tool.

The business should track customer churn, segment-level churn rates, and retention outcomes over time. Regular reviews can help stakeholders identify changes in customer behavior and assess whether retention initiatives are producing measurable improvements.

If regularly updated data is available, scheduled refreshes and consistent reporting periods can help ensure that decision-makers work with relevant information.

## Limitations



