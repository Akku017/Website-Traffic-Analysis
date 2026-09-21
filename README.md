# Website Traffic & Engagement Analytics Dashboard

**Interactive Business Intelligence Dashboard built with Microsoft Power BI**

An interactive website analytics dashboard designed to provide an executive-level view of **website traffic, user engagement, channel performance, events and hourly traffic patterns**. The project combines Python/Pandas data preparation with Power BI reporting to turn raw website traffic data into a clear, interactive analytical experience. 

## Project Objective

The objective of this project is to transform raw website traffic data into an interactive Power BI dashboard that enables users to monitor key website KPIs, compare acquisition channels, analyze engagement patterns and understand traffic behavior across different hours and dates.

The dashboard provides both a **high-level executive overview** and a **detailed channel and time performance analysis** through interactive filters and visualizations.

## Dataset Used

- <a href="https://github.com/Akku017/Website-Traffic-Analysis/blob/main/Website-traffic-data-uncleaned.csv">Raw Website Traffic Dataset</a>
- <a href="https://github.com/Akku017/Website-Traffic-Analysis/blob/main/Website-traffic-data-cleaned.csv">Cleaned Website Traffic Dataset</a>



##  Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Power BI** | Dashboard development and visualization |
| **DAX** | KPI and analytical measure calculations |
| **Power Query** | Data loading and transformation |
| **Python** | Data preparation and validation |
| **Pandas** | Data cleaning and transformation |
| **Jupyter Notebook** | Data-cleaning workflow |
| **CSV** | Source and cleaned datasets |


## Key KPIs

| KPI | Value |
|---|---:|
| **Total Users** | **133.44K** |
| **Total Sessions** | **162.90K** |
| **Total Engaged Sessions** | **90.13K** |
| **Engagement Rate** | **55.33%** |
| **Total Events** | **770.91K** |

## Questions / Analysis Areas

- What is the total number of users and sessions?
- How many sessions were engaged?
- What is the overall engagement rate?
- Which channel generates the highest session volume?
- Which channels have higher engagement rates?
- How do users and sessions change over time?
- What are the busiest hours for website sessions?
- How does engagement rate vary by hour?
- How do traffic contribution and engagement differ across channels?
- How does website activity change between different dates and hours?




## Project Process

1. **Data Loading** — Loaded the raw website traffic CSV using Pandas.
2. **Header Correction** — Used the first data row as the header and removed the redundant row.
3. **Column Standardization** — Renamed the fields into clear analytical column names.
4. **Date Transformation** — Converted `DateHour` from `YYYYMMDDHH` format into a datetime field.
5. **Data Type Conversion** — Converted analytical fields to appropriate numeric data types.
6. **Feature Creation** — Extracted the `Hour` from `DateHour` for hourly analysis.
7. **Data Validation** — Reviewed dataset structure and descriptive statistics using Pandas.
8. **Power BI Development** — Built KPI cards, trend charts, channel comparisons, hourly analysis and interactive filters.
9. **Dashboard Design** — Applied a professional dark navy theme with consistent colors, spacing and visual hierarchy.

## Dashboard

<img width="1287" height="745" alt="1page" src="https://github.com/user-attachments/assets/c0241d70-acca-4b5f-8b9f-961e1735c2c2" />
<img width="1288" height="742" alt="2page" src="https://github.com/user-attachments/assets/ec8a8d4c-d9da-439f-8434-0f0e222e114a" />



