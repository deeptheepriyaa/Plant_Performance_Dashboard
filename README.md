# Plant_Performance_Dashboard
Power BI dashboard for analyzing plant performance metrics using Excel data — includes downtime trends, YoY comparisons, and interactive KPIs.
## 📁 Files Included

- `Plant_DTS.xls`: The raw data file used as the source for the Power BI dashboard. This Excel workbook includes time-series data related to various metrics such as production, downtime, and efficiency.

- `PowerBI_PerformanceReport.pbix`: A Power BI report file that visualizes key performance indicators (KPIs), trends, and comparisons over time to aid in operational decision-making.

## 📊 Power BI Report Features

The Power BI dashboard includes:
- **Production Overview**: Total output, efficiency over time, and comparison across departments or shifts.
- **Downtime Analysis**: Trends and reasons for downtime events.
- **Year-over-Year Performance (PYTD)**: Using time intelligence (e.g., `SAMEPERIODLASTYEAR`) to track year-to-date performance against prior years.
- **Filters & Slicers**: Interactive slicers for selecting date ranges, equipment, and other categorical fields.
## 🛠 Technologies Used

- **Microsoft Excel**: Data preprocessing and organization.
- **Power BI Desktop**: Data modeling, DAX calculations, and interactive visualizations.
- **DAX Measures**: Includes custom time intelligence calculations such as `PYTD_Sales`.
