Data-Analytics-Projects

This repository contains my Data Analytics projects built using Power BI, focused on business intelligence, risk modeling, pricing strategy, and performance optimization.

Project 1: E-commerce Pricing vs Satisfaction Exception Detection

File Name: Ecommerce_Exception_Detection_Project_1.pbix

Tool Used: Power BI

Overview

This dashboard detects structurally underperforming products using multi-criteria exception logic at the category level. Products are flagged when they simultaneously meet:

Price > Category Average

Rating < Category Average

Risk Score in Top 20%

Sales < Category Median

Key Insight

The flagged products represent structural inefficiencies — overpriced, low-rated, high-risk, and weak-selling items — requiring strategic intervention rather than temporary fixes.

Tools & Techniques Used

Power BI
DAX Measures
PERCENTILEX.INC
Median Benchmarking
Multi-Condition Exception Flag Logic
Dynamic Filter Context (ALL / ALLEXCEPT)

Business Application

Product Portfolio Optimization
Risk-Based Performance Monitoring
Strategic Repricing Decisions

--------

Project 2: Promotion Effectiveness Trend Analysis

File Name: promotion_effectiveness_trend_analysis.pbix

Tool Used: Power BI

Overview

This dashboard evaluates campaign impact by comparing discount behavior before and after the promotion launch date (Jan 31). It tracks:

Avg Baseline Discount

Avg Promotional Discount

Avg Promotional Lift

Key Insight

Promotional lift increased significantly post-launch while baseline discount remained stable, indicating real incremental campaign impact.

Tools & Techniques Used

Power BI
DAX Measures
Time-Series Trend Analysis
Data Modeling

Business Application

Campaign Performance Evaluation
Discount Strategy Optimization

--------

Project 3: Discount vs Rating Causation Analysis

File Name: discount_vs_rating_causation_analysis.pbix

Tool Used: Power BI

Overview

This dashboard analyzes whether discounts directly improve ratings or indirectly influence them through increased sales volume.

Metrics analyzed:

Avg Discount %

Avg Rating

Review Volume

Key Insight

Stronger correlation exists between discount and review volume than discount and rating. Ratings improve mainly due to increased sales (social proof effect), not direct quality improvement.

Tools & Techniques Used

Power BI
DAX Measures
Scatter Plot with Regression
Correlation Analysis

Business Application

Discount Effectiveness Strategy
Customer Perception Analysis

--------

Project 4: Product Financial Risk Analysis

File Name: Product_Financial_Risk_Analysis_project_4.pbix

Tool Used: Power BI

Overview

This dashboard evaluates financial risk by combining revenue, cost structure, margin performance, volatility, and risk score indicators.

Key Insight

Certain products generate revenue but carry high financial instability due to low margins, volatile sales, or elevated risk exposure.

Tools & Techniques Used

Power BI
Financial KPI Modeling
Risk Scoring
Category-Level Benchmarking
Interactive Dashboard Design

Business Application

Margin Optimization
Risk-Adjusted Profitability Analysis
Strategic Product Discontinuation

Project 5: Trust-Weighted Product Reliability Analysis

File Name: Trust_Weighted_Rating_Model.pbix

Tool Used: Power BI

Overview

This dashboard builds a Trust-Weighted Rating Model:

Rating × log(1 + Review Count) × (1 − Return Rate)

It compares:

Simple Average Rating

Review-Weighted Rating

Trust-Weighted Rating

Key Insight

Star ratings alone overstate reliability. Incorporating review confidence and return behavior provides a more realistic, risk-adjusted trust metric.

Tools & Techniques Used

Power BI
Logarithmic Scaling
Weighted Rating Modeling
Return Rate Adjustment
Comparative KPI Analysis

Business Application

Customer Trust Measurement
Product Reliability Benchmarking

--------

Project 6: Context-Aware Dynamic Price Banding Analysis

File Name: dynamic_price_banding.pbix

Tool Used: Power BI

Overview

This dashboard applies percentile-based dynamic segmentation using:

30th Percentile (P30)

70th Percentile (P70)

Price bands (Low, Medium, High) automatically adjust based on filter context such as Category, Brand, and Date.

Key Insight

Static price thresholds misclassify products across categories. Dynamic percentile-based segmentation ensures context-aware and fair benchmarking.

Tools & Techniques Used

Power BI
PERCENTILEX.INC
ALLSELECTED Logic
Dynamic Segmentation Modeling
Interactive Slicer Design

Business Application

Dynamic Pricing Strategy
Category Benchmarking
Revenue Distribution Analysis

--------
