This project involves analyzing Amazon sales data to extract meaningful insights and trends. Below is a summary of the steps taken:

1. Data Cleaning

Standardizing Text Data: Ensured consistency by capitalizing or titling text columns like Region, Country, Item Type, and Sales Channel.
Handling Date Formats: Converted Order Date and Ship Date columns to datetime format.
Handling Missing and Inconsistent Values: Addressed issues in numerical columns for data integrity.

2. Outlier Detection and Handling

Outliers Identification: Used the Interquartile Range (IQR) method to detect outliers.
Outliers Handling: Replaced outliers with upper or lower bounds.

3. Key Metrics Calculation

Total Revenue, Cost, and Profit: Calculated these metrics to evaluate sales performance.
Most Sold Item: Identified the item with the highest total units sold.
Most Profitable Item: Determined the item with the maximum profit.

4. Visualization

Yearly Trends: Plotted units sold per item type each year to identify trends.
Frequent Itemsets: Applied the Apriori algorithm and visualized support values.
Profit Analysis: Created bar plots to visualize total profit for each item type and highlighted the most profitable item.

5. Frequent Itemsets Analysis

Apriori Algorithm: Discovered frequent itemsets with a minimum support threshold.
Visualization: Plotted support values to understand itemset frequency.

This analysis provides insights into sales performance, profitability, and trends over the years, aiding strategic decision-making
