# User Behavior and Profitability Analysis

## Project Description

This project is focused on analyzing user behavior and subscription profitability based on user activity on a website. The core objective is to explore how subscription types, geographic location, and engagement affect business metrics such as revenue and conversion.

I completed using Google Sheets to integrate multiple CSV datasets, create pivot tables, perform lookups, and build an interactive dashboard.

🔗 [View Google Sheets Dashboard](https://docs.google.com/spreadsheets/d/11UKq6v0_gw0A1gVFDF5w_P-ysDkBrIXOUQfdT_1iB8w/edit?usp=sharing)

---

## Table of Contents
1. [Project Description](#project-description)
2. [Data Overview](#-data-overview)
3. [Tools and Technologies](#-tools-and-technologies)
4. [Data Analysis Workflow](#-data-analysis-workflow)
5. [Key Findings](#key-findings)
6. [Contacts](#-contacts)

---

## Data Overview

The project uses three CSV files:

- `Users.csv` — User info (country, subscription type)
- `Subscriptions.csv` — Monthly fees per plan
- `Activity.csv` — Time spent, pageviews, conversions

### Key Fields:
- `User_ID`, `User_Name`: User identification  
- `Country`: User location  
- `Subscription_Type`: Subscription plan (Free, Basic, Premium)  
- `Monthly_Fee`: Price of subscription  
- `Pages_Viewed`, `Time_Spent_Minutes`: Engagement metrics  
- `Conversion`: Whether the user made a purchase  

### Data downloaded:  
From task-provided local files (CSV)

---

## Tools and Technologies

- **Google Sheets**: Data preparation, pivot tables, dashboarding  
- **VLOOKUP & Calculated Fields**: For data enrichment and analysis  
- **Slicers, Conditional Formatting**: For interactivity and UI  
- **Charts**: Pie charts and bar plots  
- **Formulas**: `SEQUENCE`, `IF`, `COUNTIFS`, `SUMIFS`, `AVERAGEIFS`

---

## Data Analysis Workflow

1. **Data Integration**  
   - Loaded 3 CSVs into separate sheets: Users, Subscriptions, Activity  
   - Used `VLOOKUP` to enrich user and activity data with monthly fees

2. **Behavior Analysis**  
   - Created multiple pivot tables to analyze:
     - Average session time by country and subscription
     - Revenue distribution by subscription type and country
     - Conversion rate by plan

3. **User Segmentation & Ranking**  
   - Identified top 5 most active users by pageviews using custom row index

4. **Dashboard Creation**  
   - Built an interactive dashboard:
     - Filters: by country and monthly fee
     - Summary cards: Total Revenue, Avg. Session Time, Total Users
     - Charts: Revenue distribution across countries
     - Pivot Tables: Subscription revenue, time spent

---

## Key Findings

### Insights:
- 🇩🇪 **Germany**, 🇦🇺 **Australia**, and 🇮🇳 **India** generate the highest revenue:  
  $26,310, $23,680, and $21,990 respectively.
- 🇬🇧 **UK** shows the lowest revenue among large markets ($19,100),  
  which may indicate lower user engagement or a higher share of free-tier users.
- **Premium** subscriptions bring the highest revenue ($102,180),  
  while **Basic** subscriptions contribute significantly less ($31,080).
- Average time spent on site is nearly the same (~500 min) across all subscription tiers,  
  suggesting similar engagement levels regardless of plan.
- Minor differences across countries may be influenced by cultural habits or market-specific content.

### Recommendations:
- Increase share of Premium users — introduce targeted upsell offers for Free & Basic tiers.
- Improve monetization strategies in low-performing markets (e.g., UK) via tailored campaigns.
- Analyze UX/UI & content quality to maximize user engagement time.
- Implement personalized recommendations and features for Premium users to boost retention.


---

## Contacts

For any questions or feedback, feel free to contact me:
- **Name**: Yana Grytsiyenko
- **Email**: [yanakoziuchenko@gmail.com](mailto:yanakoziuchenko@gmail.com)
- **GitHub**: [github.com/YanaGrytsiyenko](https://github.com/YanaGrytsiyenko)
- **LinkedIn**: [linkedin.com/in/yanakoziuchenko/](https://www.linkedin.com/in/yanakoziuchenko/)

