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
**Page 1 - Website Traffic & Engagement Analytics** <br/>

<img width="1287" height="745" alt="1page" src="https://github.com/user-attachments/assets/c0241d70-acca-4b5f-8b9f-961e1735c2c2" />

**Page 2 - Channel & Time Performance Analysis** <br/>


<img width="1288" height="742" alt="2page" src="https://github.com/user-attachments/assets/ec8a8d4c-d9da-439f-8434-0f0e222e114a" />

##  Key Insights

- The website recorded **133.44K users**, **162.90K sessions** and **90.13K engaged sessions** during the analyzed period.
- The overall engagement rate was **55.33%**.
- The dataset recorded **770,911 events**, displayed as approximately **771K** in the dashboard.
- **Organic Social** generated the highest session volume with **60,627 sessions**.
- **Direct** generated **37,203 sessions**, while **Organic Search** generated **33,372 sessions**.
- **Referral** generated **30,990 sessions**.
- Channel engagement rates were approximately **77.30% for Organic Video**, **66.64% for Referral**, **58.21% for Organic Search**, **53.93% for Organic Social**, **46.35% for Direct**, **33.33% for Email** and **0.72% for Unassigned**.
- Hourly session volume was highest at **7 PM with 9,129 sessions** and lowest at **5 AM with 2,598 sessions**.
- Hourly engagement rate was highest at approximately **11 AM (59.75%)** in the aggregated hourly view.

## Final Conclusion

The Website Traffic & Engagement Analytics Dashboard provides a consolidated view of website performance across **users, sessions, engaged sessions, engagement rate, events, acquisition channels, dates and hours**. The analysis shows clear differences in traffic contribution and engagement across channels, while the hourly analysis highlights substantial variation in website activity throughout the day.

By combining **Python/Pandas data cleaning, structured data preparation, Power BI visualization and interactive filtering**, this project demonstrates an end-to-end data analytics workflow for converting raw website traffic data into an executive-friendly business intelligence dashboard.

