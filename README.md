# Tableau_Retail_Performance_Analysis
This repository contains a comprehensive retail sales performance analysis project executed using Tableau. The primary goal of this project is to provide in-depth operational insights by examining key sales trends, profitability variations (LOD analysis), and geographic distribution.
## Applied Tableau Techniques (Advanced Analytical Skills)

The following advanced Tableau and analytical techniques were utilized to address core business questions:

1.  **Level of Detail (LOD) Expressions:** Calculating the variance between Sub-Category average sales and the global average sales (Variance Analysis).
2.  **Table Calculations:** Implementing a 3-Month Moving Average to smooth sales trends and identify underlying patterns.
3.  **Time Series Analysis:** Analyzing monthly sales trends to detect seasonality and overall momentum.
4.  **Spatial Visualizations:** Mapping sales volume and performance across geographic regions.
5.  **KPI Calculations:** Deriving critical business metrics such as Total Sales, Total Orders and Average Order Value.

 ## Dashboard View and Key Insights

The dashboard is structured into three main sections to enable quick and effective decision-making by business leaders:

### 1. Key Performance Indicators (KPIs)

These metrics provide a rapid overview of the current financial health, prominently displayed at the top of the dashboard.

<img width="793" height="106" alt="Screenshot 2025-12-11 at 18 05 38" src="https://github.com/user-attachments/assets/b92b9a55-df3b-4294-affa-298c56374abc" />


### 2. Trend and Variance Analysis

This section provides actionable operational insights.
| Monthly Sales Trend (Time Series) | Sub-Category Performance Variance (LOD) |
| :--- | :--- |
| **Visualization:** Monthly Sales Trend with 3-Month Moving Average | **Visualization:** Average Sales Variance Analysis (LOD) |
| **Insight:** Sales show a significant spike in the last quarter (Oct-Dec), but the moving average suggests the momentum might be slowing down, warranting further investigation. | **Insight:** **'Copiers'** and **'Machines'** sub-categories perform significantly above the global average, indicating successful product groups where investment should be focused. **'Fasteners'** perform worst. |
| <img width="813" height="590" alt="Screenshot 2025-12-11 at 18 14 01" src="https://github.com/user-attachments/assets/372c56c8-20f7-405e-9b18-43f396bef281" />** | **<img width="813" height="590" alt="Screenshot 2025-12-11 at 18 15 07" src="https://github.com/user-attachments/assets/4e37657c-854c-4870-b044-d4d1396befd8" />** |


### 3. Geographic Sales Distribution

Illustrates how sales volume and profitability are distributed across different regions.
## Final Dashboard Layout

The image below represents the complete, polished, and presentation-ready dashboard designed for executive review:
<img width="1440" height="774" alt="Screenshot 2025-12-11 at 18 09 28" src="https://github.com/user-attachments/assets/4ea34e7f-9902-4a83-8c86-ea1f4e01ae57" />

## Project Files

* **Retail_Sales_Performance_Analysis.twbx:** The main Tableau file, which includes all visualizations, calculated fields, and the embedded data source.
* **[Dataset Source: Sales Forecasting Data](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting):** The raw data file (train.csv) used for the analysis, ensuring reproducibility.
