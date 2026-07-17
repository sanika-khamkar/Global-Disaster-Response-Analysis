# 📘 Data Dictionary

This document describes the columns used in the **Global Disaster Response Analysis (2018–2024)** dataset.

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| Event_ID | Text | Unique identifier for each disaster event. |
| Event_Date | Date | Date on which the disaster occurred. |
| Year | Whole Number | Year extracted from the event date. |
| Country | Text | Country where the disaster occurred. |
| Region | Text | Geographic region of the affected country. |
| Disaster_Type | Text | Category of disaster (Flood, Earthquake, Cyclone, Wildfire, etc.). |
| Severity_Score | Decimal Number | Numerical score indicating disaster severity. |
| Casualties | Whole Number | Total number of affected people (deaths and injuries). |
| Economic_Loss_USD | Decimal Number | Estimated economic loss in US Dollars. |
| Aid_Amount_USD | Decimal Number | Total disaster relief aid provided in US Dollars. |
| Response_Time_Hours | Decimal Number | Time taken by emergency responders (in hours). |
| Recovery_Days | Whole Number | Number of days required for recovery after the disaster. |
| Response_Efficiency_Score | Decimal Number | Score representing the effectiveness of the disaster response. |

---

## Data Preparation

Before creating the dashboard:

- Converted **Event_Date** to Date format.
- Checked and handled missing values.
- Verified numeric columns for correct data types.
- Created a **Year** column for time-based analysis.
- Standardized country and disaster type names.
- Removed duplicate records where applicable.

---

## Purpose

This dataset is used to analyze:

- Disaster frequency
- Casualties
- Economic impact
- Aid distribution
- Emergency response performance
- Recovery trends
- Forecasting and decision-making
