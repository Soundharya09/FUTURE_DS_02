# Instagram Ads Performance Tracking Dashboard – Power BI Project
## Description
The Instagram Ads Performance Tracking Dashboard is an advanced digital marketing analytics project built using Microsoft Power BI. This project simulates a real-world marketing analysis task where social media ad performance is evaluated using metrics such as impressions, clicks, conversions, CTR, CPA, and demographic performance.

The goal of this project is to help marketing teams answer key business questions, including:

Q1. Which age groups and genders respond best to ads?

Q2. Which campaigns produce the highest conversions and lowest CPA?

Q3. When do ads perform best — weekdays, weekends, or specific dates?

Q4. How can we optimize future Instagram ad spending?

## Objectives
This project aims to:
- Analyze ad performance across demographic and campaign segments.
- Identify trends in impressions, clicks, conversions, and spend.
- Understand customer behavior by age group, gender, and time patterns.
- Build an interactive dashboard to support decision-making for marketing teams.
- Present insights using storytelling, visual analytics, and Power BI techniques.

## Dataset
- The project is based on simulated or exported data from Instagram Ads Manager.
- Dataset Includes:
    - Date, Campaign ID, Age Group, Gender
    - Impressions, Clicks, Conversions, Approved Conversions
    - Total Spent, CTR (%), CR (%), Approved CR (%)
    - Weekday/Weekend, Day of Week

## Dashboard Overview
The Power BI report comprises two interactive pages, each offering different analytical perspectives.
### Page 1 – Campaign Performance Summary

Purpose:

To provide an at-a-glance overview of overall campaign performance.

Key Visuals & Insights:
- KPI Cards:
    - Impressions: 79M
    - Total Clicks: 11.67K
    - Total Spent: 19.62K
    - Total Conversions: 1645
    - Approved Conversions: 585
    - Avg CTR: 0.015%
    - Avg CR: 30.45%
    - Avg CPA: $9.32
- Impressions & Clicks by Age Group and Gender
    - Ages 30–34 drive the highest impressions and clicks.
- Campaign ID Performance (Donut Charts)
    - Campaign 9777 accounts for the majority of clicks and impressions.
- Conversion Trend Over Time
    - Conversions gradually decline across the date range.
- Approved Conversions by Campaign
    - Campaign 916 leads with 66.42% approved conversions.

### Page 2 – Deep Demographic & Temporal Analysis

Purpose:

To explore how different customer segments and days affect ad engagement.

Key Visuals & Insights:
- Total Spent by Age Group & Gender
    - Highest spending among the 30–39 age categories.
- Average CR% by Age Group & Gender
    - Females show slightly higher conversion rates in most categories.
- Approved CR% by Age Group
    - Strongest performance comes from 35–39 and 40–44 demographics.
- Impressions Distribution by Day of Week
    - Wednesday leads with 22.2% of weekly impressions.
- Approved Conversions (Weekday vs Weekend)
    - 74.7% occur on weekdays, making weekdays the stronger conversion period.
- Campaign Distribution Across Age Segments
    - Younger audiences have wider campaign coverage.

## Analytical Process
1. Data Cleaning
- Removed duplicates and nulls
- Fixed incorrect age group labels
- Standardized variable naming

2. Data Modeling
- Created measures for:
   - CTR, CR, Approved CR
   - CPA, Total Conversions, Approved Conversions
   - Built relationships between demographic, campaign, and time tables

3. Power BI Visualizations
- Slicers for Gender, Age, Campaign ID, Date
- Bar charts for demographics
- Donut charts for campaign segmentation
- KPI cards for quick performance summaries
- Line charts for time-based behaviors

4. Insight Generation
- Identified top-performing demographics
- Highlighted best and worst campaigns
- Evaluated spending efficiency (CPA)
- Examined weekday vs weekend performance shifts

## Outcome
This dashboard helps marketing teams:
- Optimize ad spend by focusing on high-performing age groups
- Improve campaign structure using conversion and CTR data
- Identify the best posting days for maximum engagement
- Track ROI and conversion efficiency in real-time
- Make data-driven decisions for future Instagram ad strategies
