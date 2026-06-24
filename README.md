# Cyclistic Bike-Share Analysis
### Google Data Analytics Certificate — Capstone Project

## Overview
This case study analyzes how annual members and casual riders use Cyclistic 
bikes differently, with the goal of informing a marketing strategy to convert 
casual riders into annual members.

This is the capstone project of the Google Data Analytics Certificate.

---

## Business Task
Identify the key differences in bike usage between casual riders and annual 
members to support marketing strategies aimed at converting casual riders 
into members, given that annual members generate significantly more revenue.

---

## Data Sources
- **Dataset:** Divvy Trip Data 2019 (Q1, Q2, Q3, Q4)
- **Provider:** Motivate International Inc.
- **License:** Public data, available at https://divvybikes.com/system-data
- **Format:** CSV files, one per quarter
- **Note:** No personally identifiable information is included in the dataset.

---

## Tools Used
- **Python** (Google Colab) — data cleaning, schema harmonization, 
  ride length calculation, CSV export
- **Tableau Public** — data visualization and dashboard creation

---

## Data Cleaning & Processing
- Loaded 4 quarterly CSV files with different column schemas
- Renamed Q2 2019 columns to match Q1/Q3/Q4 schema
- Standardized `member_casual` values 
  (Subscriber → member, Customer → casual)
- Converted timestamps to datetime format
- Calculated `ride_length` in seconds
- Added date columns (day, month, year, day_of_week)
- Removed rides with negative duration and quality-control entries

---

## Key Findings
1. **Members ride 3x more often**, especially on weekdays → commuting pattern
2. **Casual riders take trips 4x longer** in duration (~57 min vs ~14 min) 
   → leisure pattern
3. **Casual riders are most active on weekends** (Saturday and Sunday)

---

## Visualizations
📊 [View Tableau Public Dashboard](https://public.tableau.com/views/CyclisticBike-ShareAnalysis_17822976617940/Dashboard1?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Recommendations
**1. Weekend membership campaign**
Target casual riders on weekends with promotions highlighting the value of 
membership for leisure rides. Since casual riders are most active on Saturdays 
and Sundays, in-app or station-based messaging on those days would reach them 
at peak engagement.

**2. Promote commuting benefits to casual riders**
Highlight time and cost savings of membership for daily commuters. Data shows 
members take short, frequent trips on weekdays — marketing could show casual 
riders how a membership pays off if they shift from leisure to regular use.

**3. Offer a trial or flexible membership**
Since casual riders already use Cyclistic, a lower-commitment option (weekend 
pass or seasonal membership) could be a stepping stone toward full annual 
membership.

---

## Author
Carmen Rosa — Google Data Analytics Certificate, 2026
