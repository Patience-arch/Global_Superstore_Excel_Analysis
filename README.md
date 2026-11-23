Global Superstore Sales Analysis Using Excel

I cleaned 51,290 rows of retail data in Microsoft Excel and built an interactive dashboard to track sales, profit, and shipping turnaround time across global regions.

Key Metrics (Overall):
1. Total Sales: 12,642,502
2. Total Profit: 1,467,457
3. Avg. Shipping Time: 4 Days

What I Did:

Data Cleaning (Working Sheet): 
1. Kept the raw dataset untouched on its own tab.
2. Standardized inconsistent date formats across all 51,290 rows.
3. Dropped unnecessary columns.
4. Calculated order shipping time (Days) using =DAYS(ShipDate, OrderDate) with zero formula errors.

Data Analysis (Pivot Table): 

Built Pivot Tables to break down sales, profit and shipping days by region, country, product category, and shipping mode.


Data Visualization (Dashboard):

Created live KPI cards, regional comparison charts (Category Quantity, Avg. Profit, and Count of Sales by Ship Mode) and interactive Slicers linked to all tables and charts via Report Connections.

What I Learned:

The trickiest parts of this project were fixing mixed date formats so the DAYS() formula calculated cleanly across every row, and making sure every Slicer was linked through Report Connections so the KPI cards and charts updated together when filtering by region.

Key Findings
1. Product category performance: Office supplies recorded particularly high sales quantities across several regions with a noticeable peak in the     Central region.
2. Regional profitability: Technology recorded strong average profit figures in several regions, although profitability varied across product         categories and geographical markets.
3. Regional sales Distribution: The central region displayed a particularly prominent peak in the count of sales indicating differences in sales      activity across regions.
4. Interactive analysis: Dynamic regional slicers allow users to explore sales quantities, average profit and sales counts across different             geographical markets.

How to Use:
Download the .xlsx file and open it in Microsoft Excel.
Open the Dashboard tab and click any Region on the Slicer to filter all KPIs and charts live.
