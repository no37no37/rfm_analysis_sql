# RFM Analysis of Sales Data in SQL
In this project, a sales dataset was explored, and customer segmentation analysis was conducted using SQL and Tableau. The analysis provided insights into various aspects of the sales data, such as sales by product line, sales by year, sales by deal size, the best month for sales per year, and product line sales in the best month. Additionally, RFM (Recency, Frequency, Monetary) analysis was applied to segment customers based on their past purchase behavior.

# Resources Needed
The project required the following resources:

a. Data: A sales dataset was utilized, with the link provided in the project description.

b. Tableau: Tableau Public was installed to facilitate visualization and dashboard creation.

c. SQL: SQL Server 2019 was used to analyze the dataset.

d. Importing Data and Inspecting Imported Data

The CSV file was downloaded from the GitHub repository and imported into SQL Server using the database engine's import task. The imported data was examined to understand its structure and contents. Distinct searches were performed on various data points, including order number, ordered price, sales order date, and status.

# Analysis

1. Sales by Product Line
The sales data was grouped by product line, and aggregate functions were computed to determine the product that generated the highest revenue.

2. Sales by Year
The sales data was analyzed by year to identify the year with the highest sales. The investigation also aimed to determine if lower sales in a specific year were due to the company operating for only a partial year.

3. Sales by Deal Size
The sales data was examined based on different deal sizes to identify the deal size that generated the most revenue.

4. Best Month for Sales per Year
The best sales month for each year was determined by comparing the revenue generated in different months. This analysis provided insights into the most successful month for sales.

5. What Product Line Sells Most in Best Month
By considering the best sales month, the product line with the highest sales was identified. Furthermore, an analysis of the best-selling product line across different years was conducted.

# RFM Explanation
The concept of RFM (Recency, Frequency, Monetary) analysis was explained, highlighting its utilization of past purchase behavior to segment customers into categories such as high value, low value, or lost customers.

# Who is the Best Customer
* RFM values were calculated for each customer based on their recency, frequency, and monetary value to identify the best customer. 
* Customers were then grouped into four buckets based on their RFM values, and categorized as lost, loyal, or new customers.

# What Product Codes Sell Together
* Subqueries and XML path analysis were employed to determine which products were frequently sold together. 
* The product codes of orders with multiple items were analyzed to identify patterns of products sold together.

# [Tableau Visualization]([https://www.example.com](https://public.tableau.com/app/profile/leon.jose/viz/RFMAnalysisSalesDashboard1/RFMAnalysisDashboard1))
* Multiple worksheets were created to depict different aspects of the data, including sales distribution, deal size distribution, sales by year, revenue by country, and sales by product line. 
* A comprehensive dashboard was developed by combining these worksheets and customizing their appearance. 
