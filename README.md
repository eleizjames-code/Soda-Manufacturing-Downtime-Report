# Soda-Manufacturing-Downtime-Report
This dashboard analyzes downtime causes and their impact on line efficiency and production losses in a soda manufacturing setup.

<p align="center">
  <img src="https://github.com/eleizjames-code/Soda-Manufacturing-Downtime-Report/blob/main/Soda%20Manufacturing%20Downtime%20Dashboard%20(PNG).png.png?raw=true" alt="Tastescape Restaurant Sales Dashboard" width="80%">
</p>
<p align="center"><b>Figure 1:</b> Soda Manufacturing Downtime Report</p>

## Dataset Used
<a href = "https://github.com/eleizjames-code/Soda-Manufacturing-Downtime-Report/raw/refs/heads/main/Manufacturing_Line_Productivity.xlsx"> 📂Manufacturing_Line_Productivity </a>

## Project File
<a href = "https://github.com/eleizjames-code/Soda-Manufacturing-Downtime-Report/raw/refs/heads/main/Soda%20Manufacturing%20Downtime%20Report.pbix"> 📎Soda Manufacturing Downtime Report </a>

##  Objectives
1. Identify major causes of production downtime.
2. Understand how downtime impacts line efficiency and operator performance.
3. Determine why production targets (sodas) were missed.
4. Recommend improvements to enhance operational efficiency.

## Process
1. **Extract**– Sourced data from an Excel workbook.
2. **Transform**– Cleaned and merged using Power Query.
3. **Load** – Loaded the transformed data into Power BI.
4. **Data Modeling** – Built relationships and created DAX measures (e.g., Line Efficiency, Missed Sodas).
5. **Visualization** – Designed an interactive dashboard to highlight key production insights.

## Insights
- 56% of downtime is caused by operator-related issues; 44% from machine-related problems.
- Top causes:
  - Machine Adjustment – 332 mins
  - Machine Failure – 254 mins
  - Inventory Shortage – 225 mins
  - Batch Change – 160 mins
- Charlie has the most downtime but also the highest operator efficiency (67%).
- Mac has the lowest downtime but also the lowest efficiency (61%), indicating other factors affect performance.
- Line efficiency is inversely related to total downtime—e.g., efficiency dips when downtime spikes (e.g., Aug 30 & Sept 2).
- Product CO-600 contributed to the most missed sodas (8 of 21 total misses).

## Conclusion
Downtime is primarily driven by operator-related adjustments and batch changes. However, machine failures and inventory shortages remain significant contributors. While some operators handle downtime efficiently, there's no direct correlation between low downtime and high performance. The CO-600 line stands out as the major bottleneck.

## Recommendations
1. Reduce machine adjustment time by optimizing SOPs and retraining operators.
2. Address inventory and batch change planning to prevent stoppages.
3. Investigate why Mac’s efficiency is low despite fewer downtimes—look into workflow or task distribution.
4. Focus maintenance on CO-600, the highest source of soda losses.
5. Monitor line efficiency daily and schedule preventive maintenance ahead of expected peak downtimes.
