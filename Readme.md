### ☕ COFFEE SALES ANALYTICS DASHBOARD

————————————————————————————————————————————————————————————
### 1. Project Overview

This repository contains a comprehensive interactive Coffee Sales Dashboard developed using Power BI Desktop. The business objective of this project is to analyze transactional retail sales data to extract actionable operational insights regarding revenue, order volumes, profitability margins, customer behaviors, and geographic performance. By tracking historical performance across multiple years (2021–2023), this business intelligence tool empowers retail managers and stakeholders to make data-driven inventory, marketing, and pricing decisions.

### 2. Key Performance Indicators (KPIs)

The dashboard high-level metric cards monitor overall performance at a glance:

•	Total Transactions: 9,971 individual retail transactions recorded across the dataset.

•	Total Revenue: $46.37K in aggregate gross sales revenue generated across all periods.

•	Total Quantity Sold: 14K total units of coffee, beverages, items, and desserts purchased.

•	Total Net Profit: $16.23K accumulated net profits, reflecting highly robust operational retail margins.

### 3. Dashboard Structural Breakdown & Deep Dive

Transaction ID by Weekday (Trend Line Chart)
Traces the flow of transaction counts through the days of the week. Friday acts as the peak operational period with approximately 1.5K transactions, while all remaining days (Saturday through Monday) demonstrate remarkably consistent, stable baseline demand hovering at roughly 1.4K transactions per day.

Revenue & Sum of Profit Margin by Month (Combined Bar Chart)
Illustrates seasonal distribution of gross sales vs. net profit margins. January leads as the highest revenue-generating month, followed by a minor dip and subsequent secondary surge in May, before entering a slight, progressive tail-off towards the late winter months (November, April, September, and February).

Revenue By Year (Donut Chart Breakout)
Breaks down total financial contributions over time. Market share is evenly spread across the years, showcasing organic stability: 2022 leads with 33.96% ($15.75K), followed closely by 2023 at 33.15% ($15.37K), and 2021 at 32.89% ($15.25K).

Total Revenue by Product Category (Horizontal Bar Chart)
Ranks core commercial revenue channels. Desserts represent the highest-grossing category ($7.2K), closely contested by Sandwiches ($6.8K), Tea Beverages ($6.7K), Coffee Beverages ($6.5K), Specialty Drinks ($6.5K), Snacks ($6.4K), and Cold Drinks ($6.3K).

Transaction ID by Month (Volume Histogram)
Evaluates absolute traffic patterns. May (909 orders) and July (865 orders) represent high-volume consumer traffic hubs, contrasting with February (744 orders) which acts as the seasonal cyclical low points.
Revenue By City (Geographic Market Share Donut Chart)
Provides multi-regional insights. Chicago represents the largest metropolitan footprint contributing 24.16% ($11.21K) of total revenue, closely shadowed by Los Angeles at 23.26% ($10.79K), New York at 22.48% ($10.43K), and remaining market value distributed among Austin and Seattle.

### 4. Interactivity & Slicers

The top navigation panel incorporates dedicated global slicers allowing dynamically filtered reporting perspectives:

•	City Slicer: Filters the entire report structure down to specific metropolitan footprints (Chicago, Los Angeles, New York, Austin, Seattle).
•	Month Slicer: Enables seasonal, monthly cross-sectional isolation to observe individual monthly trends.
•	Year Slicer: Isolates transactional data for years 2021, 2022, or 2023 to evaluate operational annual growth rates.

### 6. Steps to Deploy & Run Project Locally

1.  Clone this GitHub Repository to your local machine using git clone <your-repository-url>.

2.  Ensure you have the latest version of Power BI Desktop installed on your operating system.

3.  Locate the .pbix file within the project directory root folder and double-click to open it.

4.  If raw data source prompts appear, refresh or remap your local directory pathing pointing to the attached dataset file.

5.  Utilize the interactive charts, click elements to cross-filter, and change slicer parameters to see real-time updates.

### Dashboard Screenshot

![Dashboard Screenshot](Dashbord_Screenshot.png)       