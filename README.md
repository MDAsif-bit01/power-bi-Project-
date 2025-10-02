# 📊 Power BI Dashboard – Sales & Profit Analysis

This dashboard provides a detailed view of business performance, including:

### 🔑 Key Metrics
- **Profit**: 16.89M  
- **Gross Sales**: 127.93M  
- **Discounts**: 9.21M  
- **COGS**: 101.83M  

### 📈 Profit & Sales Trend
- Monthly comparison of profit vs. sale price.

### 🌍 Geographical Distribution
- Profit by country (**North America & Europe highlighted**).

### 🛒 Product Analysis
- **Sales by Product**: Pie chart showing equal distribution among 6 products.  
- **Profit by Product**: Waterfall chart highlighting contributions from *Paseo, VTT, Amarilla, Velo, Montana, and Carretera*.
   
![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%201.jpg)

# Superstore Tasks
- Create a KPI card to display the total sales and use a slicer to filter the results by region. Additionally, visualize sales trends over time with a line chart segmented by region.

![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%202_page-0001.jpg)

- Write a DAX measure to calculate the profit margin as Profit Margin = SUM(Profit) / SUM(Sales) and display the result using a column chart by product category.

![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%202_page-0002.jpg)

- Create bins for sales values in ranges like 0–100, 100–500, 500–1000, and 1000+ and use a bar chart to show the number of orders in each bin.

![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%202_page-0003.jpg) 

- Group customers into categories based on their total profit: High Profit (greater than 1000), Medium Profit (0 to 1000), and Low/Negative Profit (0 or less). Show a visual comparing the number of customers in each group.

![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%202_page-0004.jpg) 

- Create a calculated column to find the number of days between the order date and the ship date using DATEDIFF(Order Date, Ship Date, DAY) and show the average days to ship by ship mode in a column chart and KPI card.

![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%202_page-0005.jpg) 

- Join the Returns table with the Orders table on Order ID. Create a measure for return rate using COUNT(Returns[Order ID]) / DISTINCTCOUNT(Orders[Order ID]) and display return rates by region.

![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%202_page-0006.jpg) 

- Add a Top N slicer to allow users to dynamically select the number of top customers based on total sales, and display the result in a bar chart.

![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%202_page-0007.jpg) 

- Create a manual grouping of states into 'High Revenue States' (top 5 by sales) and 'Remaining States', then compare total profit and average shipping cost between these two groups.

![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%202_page-0008.jpg) 

- Develop a DAX measure to calculate year-over-year sales growth using SAMEPERIODLASTYEAR(Order Date) and visualize it with a KPI and a year-wise line chart.

![dashborad](https://github.com/MDAsif-bit01/power-bi-Project-/blob/main/image/power%20bi%202_page-0009.jpg) 







