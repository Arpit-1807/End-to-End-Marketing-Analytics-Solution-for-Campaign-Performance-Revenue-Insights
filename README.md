# Marketing Performance Analytics Dashboard

## Project Overview

- Business problem
- Objective
- Why marketing analytics matters
- What insights dashboard provides

This project focuses on analyzing marketing campaign performance and sales conversion efficiency using Power BI. The dashboard enables stakeholders to track spend, ROAS, ROI, conversions, CTR, CPC, and audience behavior to optimize marketing budget allocation and campaign effectiveness.

## Business Problem

Marketing teams often struggle with:

- Inefficient campaign spend allocation
- Low visibility into ROI/ROAS
- Poor regional performance tracking
- Difficulty identifying high-performing campaigns

This dashboard solves these challenges through centralized KPI monitoring and interactive performance analysis.

## Tools & Technologies Used
- Power BI
- Power Query
- DAX
- Data Modeling
- SQL Concepts
- Data Visualization
- Marketing Analytics

## Dataset Information
Mention:

- Campaign dataset
- Shopify sales dataset
- Raw data quality issues

Datasets Included:
1. Campaign Marketing Data
2. Shopify Sales Data

Data Quality Issues Handled:
- Duplicate records
- Missing values
- Incorrect CTR calculations
- Mixed text formatting
- Inconsistent date formats
- Outlier spend values

## Data Cleaning & Transformation
- Removed duplicate rows
- Standardized date formats
- Recalculated CTR, CPC, CPM, ROI
- Normalized platform/channel names
- Handled missing spend/click values
- Created validation flags for incorrect CTR

## Data Model
Star Schema:

Fact Table:
- fact_sales

Dimension Tables:
- dim_campaigns
- dim_date

Mention:
- One-to-many relationships
- Date intelligence support

## DAX Measures
| Measure          | Purpose                   |
| ---------------- | ------------------------- |
| Total Spend      | Campaign spend tracking   |
| Total Sales      | Revenue analysis          |
| ROI %            | Profitability measurement |
| ROAS             | Ad efficiency             |
| CTR %            | Click engagement          |
| CPC              | Cost efficiency           |
| MoM Spend Change | Trend analysis            |

## Dashboard Pages
Page 1 — Executive Summary
- KPI cards
- Spend vs Conversion trend
- Top campaigns
- MoM analysis

Page 2 — Channel Breakdown
- Platform comparison
- Region analysis
- Channel spend distribution

Page 3 — Audience & Conversion Insights
- Audience conversion analysis
- Spend vs ROI scatter analysis
- Geo performance mapping

## Key Business Insights

- Brand B generated highest spend contribution
- India showed highest conversions with lowest CPC
- Certain campaigns achieved exceptionally high ROAS
- Regional performance varied significantly across markets

## Features Implemented
- Cross-page slicers
- Drill-through navigation
- Interactive filtering
- Executive KPI reporting
- Geo-spatial analysis
- Dynamic DAX calculations

## Dashboard Images Section
### Executive Dashboard
<img width="2989" height="1675" alt="Execuitve_Summary_Page" src="https://github.com/user-attachments/assets/c0a54496-ff9a-4c85-8883-c00ace91469b" />

### Channel Analysis
<img width="2983" height="1679" alt="Channel_Breakdown_Page" src="https://github.com/user-attachments/assets/7677fbc0-7dfd-483c-8a88-18bca9470638" />

### Audience Insights
<img width="2990" height="1678" alt="Audience_Conversion_Page" src="https://github.com/user-attachments/assets/58b2cf0c-bdbb-4f4b-bbda-d8ccc421fa87" />

### Data Model
<img width="3768" height="1759" alt="Data Model Screenshot" src="https://github.com/user-attachments/assets/f5187d72-5442-4bf4-9748-ee62580a96f2" />

## Business Impact

This dashboard helps marketing teams improve campaign decision-making, optimize advertising spend, monitor conversion performance, and identify high-value growth opportunities through data-driven insights.

## Future Improvements
- Real-time API integration
- Predictive marketing analytics
- Customer segmentation
- A/B testing analytics
- Automated anomaly detection

















