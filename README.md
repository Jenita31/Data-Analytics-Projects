Data-Analytics-Projects

This repository contains my Data Analytics projects created using Microsoft Excel and Power BI.
------

Project 1: E-commerce Pricing vs Satisfaction Exception Detection

File Name: ecommerce_project_1.xlsx
Tool Used: Microsoft Excel

Overview

This Excel-based analytical project identifies business underperforming products by applying multi-criteria exception detection logic. The analysis compares products at the category level and flags items that simultaneously meet the following conditions:

Price higher than category average

Rating lower than category average

Risk score in the top 20%

Sales below category median

The goal is to detect products that negatively impact overall business performance.

Key Insight

The identified products represent critical business failures because they are overpriced compared to competitors, have lower customer satisfaction, carry higher operational or quality risk, and generate weak sales performance. These combined factors indicate structural business inefficiencies rather than temporary fluctuations.

Skills Applied

Data Cleaning

VLOOKUP

Pivot Tables

Conditional Analysis

Category-Level Aggregation

Recommended Actions

Re-price products strategically

Improve product quality

Reduce operational or supply chain risk

Remove consistently underperforming products
------

Project 2: Promotion Effectiveness Trend Analysis

File Name: promotion_effectiveness_trend_analysis.pbix
Tool Used: Power BI

Overview

This Power BI dashboard evaluates the effectiveness of a promotional campaign by comparing discount behavior before and after the campaign launch. The analysis tracks:

Avg Baseline Discount

Avg Promotional Discount

Avg Promotional Lift

The promotion start date (Jan 31) is highlighted in the trend analysis to clearly show structural changes in discount behavior.

Key Insight

Promotional discounts and promotional lift increased significantly after the campaign launch, while baseline discount remained stable. This indicates that the campaign introduced real incremental discount activity rather than artificial price inflation before discounting.

Tools & Techniques Used

Power BI

DAX Measures

Time-Series Trend Analysis

Data Modeling
------

Project 3: Discount vs Rating Causation Analysis

File Name: discount_vs_rating_causation_analysis.pbix
Tool Used: Power BI

Overview

This Power BI dashboard analyzes whether higher discounts genuinely improve customer satisfaction or primarily increase sales volume. The study evaluates the relationship between:

Avg Discount Percentage

Avg Rating

Review Volume

Scatter plots with regression trend lines are used to identify correlation patterns and determine whether rating improvements are directly caused by discounts or indirectly influenced by increased sales activity.

Key Insight

Although discounts show a positive relationship with ratings, a stronger relationship exists between discount and review volume. Ratings tend to improve as review count increases, suggesting that higher ratings are more influenced by increased sales volume (social proof effect) rather than direct improvements in product quality.

Tools & Techniques Used

Power BI

DAX Measures

Scatter Plot & Regression Analysis

Data Modeling
------
Project 4: Product Financial Risk Analysis

File Name: Product_Financial_Risk_Analysis_project_4.pbix
Tool Used: Power BI

Overview

This Power BI dashboard analyzes product-level financial risk by combining revenue performance, cost structure, profit margins, and risk indicators into a unified analytical model.

The objective of this project is to identify products that expose the business to financial instability by evaluating:

Revenue Performance

Cost and Profit Margin

Risk Score Contribution

Sales Volatility

Category-Level Financial Comparison

The dashboard enables stakeholders to quickly detect high-risk, low-profit, or unstable products that may negatively impact overall financial health.

Key Insight

The analysis reveals that certain products generate revenue but carry disproportionately high financial risk due to low margins, unstable sales patterns, or elevated risk scores.

Some products appear profitable at surface level but show declining margin trends when analyzed over time. This highlights the importance of combining financial metrics with risk indicators rather than evaluating revenue alone.

The dashboard supports proactive decision-making by identifying products that require margin correction, cost optimization, or strategic discontinuation.

Tools & Techniques Used

Power BI

DAX Measures

Financial KPI Modeling

Risk Scoring Analysis

Category-Level Aggregation

Interactive Dashboard Design
------
