\# Household Energy Consumption Analysis



\## 📌 Project Overview

This project analyzes household-level data (family size, income, appliances, electricity usage, gas usage, etc.) to understand energy consumption patterns.  

The goal was to explore \*\*how family size, income, and appliance count affect electricity/gas usage\*\*, and to identify \*\*per-person consumption, income-adjusted burden, seasonal variations, and top users\*\*.  



---



\## ⚡ Approach

1\. \*\*Data Preparation\*\*  

&nbsp;  - Collected and cleaned household dataset (250 rows).  

&nbsp;  - Added calculated fields (per-person usage).  



2\. \*\*Analysis\*\*  

&nbsp;  - Built Pivot Tables in Excel to explore relationships:  

&nbsp;    - Family Size vs. Electricity/Gas Usage  

&nbsp;    - Income vs. Usage  

&nbsp;    - Appliances vs. Usage  

&nbsp;    - Per-Person Consumption  

&nbsp;    - Seasonality by Month (via slicers)  

&nbsp;    - Top 10 households by usage  



3\. \*\*Visualization\*\*  

&nbsp;  - Used Pivot Charts and slicers for interactive filtering by month.  

&nbsp;  - Highlighted trends, anomalies, and efficiency insights.  



---



\## ▶️ How to Run

1\. Clone/download this repository.  

2\. Open the Excel file (`Household\_Energy\_Analysis.xlsx`).  

3\. Use the \*\*Pivot Table + Slicers\*\* to interact with data.  

---



\## ⚠️ Challenges Faced

\- Saving in the wrong format (`.csv`) removed pivots and slicers — had to rebuild everything in `.xlsx`.  

\- Ensuring calculated fields (per-person usage) showed up in pivots required manual adjustments.  

\- Some mid-sized families showed very high usage, which at first looked like errors but were actually appliance-driven anomalies.  



---



\## 📊 Dataset Used

\- \*\*Household Dataset (synthetic, 250 rows)\*\*  

&nbsp; Columns include:  

&nbsp; - Household\_ID  

&nbsp; - Family\_Size  

&nbsp; - Monthly\_Income  

&nbsp; - Electricity\_Usage (kWh)  

&nbsp; - Gas\_Usage  

&nbsp; - Appliances\_Count  

&nbsp; - Month  



---



\## 📑 Reports

Key findings summarized:  

\- Larger families use more energy overall, but per-person usage is often lower.  

\- Richer households consume more, but income-adjusted burden falls more heavily on lower-income households.  

\- More appliances = more electricity, but inefficiency matters.  

\- Seasonal peaks are critical in driving energy demand.  

\- Top users are not always the richest → affordability risks exist.  



---



