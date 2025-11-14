# Startup Business Performance Analysis

This project provides a comprehensive financial analysis of a startup's performance, focusing on revenue growth, profitability, and operational efficiency. It leverages a Jupyter Notebook for detailed data processing and initial exploration, complemented by an interactive Power BI dashboard for dynamic visualizations and deeper business insights.

## Project Components

### 1. Jupyter Notebook (`startup_revenue_analysis.ipynb`)

This notebook is the core of the analytical process. It covers:

*   **Data Loading & Cleaning:** Importing the raw financial data and preparing it for analysis by handling data types and ensuring consistency.
*   **Financial Metric Calculation:** Deriving key performance indicators (KPIs) such as Gross Margin, Operating Income, Net Profit, ROI, ROAS, and various cost percentages (COGS%, Opex%, Marketing%).
*   **Exploratory Data Analysis (EDA):** Visualizing trends in revenue, profitability margins over time, and year-over-year growth.
*   **Performance Breakdown:** Analyzing revenue and profit contributions by product and geographical region.
*   **Sensitivity Analysis:** Examining the impact of changes in marketing spend and other variables on overall profit, including a tornado chart for profit sensitivity.

### 2. Power BI Dashboard (`startup_performance_dashboard.pbix`)

The Power BI dashboard offers an interactive and visual summary of the key findings from the notebook. It allows users to explore:

*   **Overall Financial Trends:** Interactive charts showing revenue, profit, and margin trends.
*   **Product & Regional Performance:** Dynamic views to filter and compare performance across different products and regions.
*   **Key Performance Indicators (KPIs):** A snapshot of critical metrics like ROI and ROAS, providing actionable insights at a glance.
*   **What-If Scenarios:** (If included) Interactive elements to test different business assumptions.

## How to Use

### Jupyter Notebook
1.  **Open in Google Colab:** Click on the `startup_revenue_analysis.ipynb` file in your Google Drive and select 'Open with Google Colaboratory'.
2.  **Run Cells:** Execute the cells sequentially to reproduce the data processing, analysis, and visualizations.

### Power BI Dashboard
1.  **Download Power BI Desktop:** If you don't have it, download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2.  **Open Dashboard:** Open the `startup_performance_dashboard.pbix` file using Power BI Desktop.
3.  **Interact:** Explore the various pages and filters to gain dynamic insights into the startup's financial performance.

## Key Insights from the Analysis

*   **Positive Revenue Growth:** The company demonstrates a consistent upward trend in total revenue year-over-year.
*   **Fluctuating Profitability:** While gross and operating margins are strong, net profit margin shows variability, highlighting the importance of managing all expenses effectively.
*   **Top Performers (Products):** Product B and Product C are major revenue drivers, but Product D leads in net profit and ROI, suggesting superior efficiency.
*   **Top Performers (Regions):** West Africa and North Africa are the leading regions in both revenue and ROI.
*   **Marketing Sensitivity:** Increased marketing spend, without a proportional increase in profit, can dilute ROI. Optimized marketing strategies are crucial.
*   **Revenue as the Primary Profit Driver:** Revenue generation is the most impactful variable on overall profit, followed closely by COGS management.

## Technologies Used

*   **Python:** Pandas, Matplotlib, Seaborn, NumPy
*   **Power BI**
