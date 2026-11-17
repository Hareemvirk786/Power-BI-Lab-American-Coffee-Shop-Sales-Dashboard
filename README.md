☕ American Coffee Shop Sales Dashboard
A Power BI portfolio project by Javed Khizer Mohammad. This one-page report uses coffee shop transactions to compare sales across cities, product categories, times of day, and months.
🖼️ Dashboard preview

📊 Dashboard highlights
KPI	Value shown
Total sales	$339.75
Total quantity	80 units
Average sales	$7 (rounded in the card)
Transaction count	48
Average unit price	$4.29


- Category mix: Beverages accounted for $233.50 (68.73%) of displayed sales. Food accounted for $106.25 (31.27%).
- Time of day: Morning had the highest sales in the daypart chart, followed by afternoon and evening.
- Monthly sales: The line chart shows lower sales in February than in January. The source file covers January 3 through February 19, 2026, so the chart compares partial months.
- City and product views: A horizontal bar chart compares sales by city, while a column chart compares units by product. City and category slicers let viewers explore subsets of the report.
🧹 Dataset and data quality
The raw CSV has 50 rows, 48 unique transaction IDs, and 16 columns. Fields include transaction date, store location, city, product, category, unit price, quantity, total sales, payment method, and daypart. The CSV contains repeated transaction IDs, missing values, inconsistent capitalization (for example, Beverage and beverage), and a second city field named City_Duplicate. The dashboard displays an Unknown label in its city and product charts.
📁 Project files
File	Purpose
[Power BI report](Lab-16_Power%20Bi_Final%20Dashboard_Javed%281%29.pbix)	Interactive report and data model
[Source CSV](American_Coffee_Shop_Messy_Dataset%20%281%29.csv)	Raw transaction data
[Dashboard screenshot](Screenshot%202026-11-17%20123431.png)	Preview for GitHub visitors


🚀 Open the report
1. Download the PBIX and CSV from the repository.
2. Open the PBIX in Power BI Desktop. Use the city and category slicers to explore the report.
3. If a refresh prompts for the original CSV path, open Transform data, select the CSV query, and update its Source step to point to your downloaded CSV. Apply the changes and refresh.
