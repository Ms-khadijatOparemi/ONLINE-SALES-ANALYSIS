# Excel_Project- BLACK STARS ONLINE SALES ANALYSIS

https://drive.google.com/drive/u/0/folders/1OOyYEvqQ8i8BpSdPGQQjMEKvfrnmx6_t

# Project Brief
A supermarket (An Online store) that sells all varieties of items in different categories, from Fashion to Home and Office supplies. They have the dataset of their shopping over 5 years, from 2015 to 2020. The CEO wants to see how the supermarket is fairing by certain Key Performance Indicators. The manager has been assigned to identify the key areas within the business that need clarification and get them sorted out as soon as possible.
Our work as a Data Analyst is to analyze the sales dataset and develop results and visualization.

# Tasks
Perform analysis on the following:
* Total revenue by product category
* Revenue by Year
* Customers' gender by revenue across the years
* Customers' gender by percentage
* Which of the delivery channels have the biggest revenue by percentage?
* Percentage of revenue by gender across age groups
* Top 5 Product subcategories by revenue
* Product category by Total revenue, percentage of total revenue, total orders and percentage of total orders
* Reasons why customers return some of the items purchased
* Product category by Total revenue across

# Data Structure
The dataset was obtained from the Data Entry officer of the supermarket. The dataset contains 113,000 rows and 18 columns of records of sales with fields like Order date, Order ID, Delivery date, Customer age, Gender, Delivery type, Product category, etc.

 [Data structure](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/3f2a453d-633a-450c-b683-4bd4a2117b52)

# KPIs
The Key Performance Indicators include: 
* Total Revenue
* Total Orders 
* Total Shipping Fee
* Total Number of Customers and 
* The Average Delivery Days of products
  
![KPI 1](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/89d74aa2-9fc8-4327-832f-1f6dfbe8aa75)

# Tool: Microsoft Excel
The analysis of the dataset was done on Microsoft Excel using PivotTable.

# Data preparation and cleaning
* Copy and paste the data into another sheet.
* Checked for duplicate orders using Highlight Cells Rules in the Conditional Formatting feature on the OrderID column and CustomerID Column.
* Check for completeness and uniformity of the data items using the filter feature.
* A new column was created: Year, derived from  the OrderDate column.
  ![Year](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/64861c69-26fc-4ade-a350-4c18b3b9791a)

* To find the average delivery days, a new column was created by subtracting the OrderDate from the DeliveryDate. On the PivotTable, we summarized the value field by 'Average' to get the average days of delivery.

  [Delivery Day](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/0e6968c4-52a7-40a2-b275-018576d41d61)
  
  [Average Delivery Days](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/b7d01699-cfb3-40d4-b701-8e7a2e443246)

* To find the total sales, a new column was created using the product function on the Unit price and Quantity ordered column.
  [Total sales](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/ce309bb8-57ef-431f-8e59-d6b06fb32bc7)

* A new table ‘Age Group’ was created in a new sheet
  [Age_Group Table](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/5e7701b3-622c-42b6-939c-f1c90a5223ef)

* To get the corresponding age group the Vlookup function was used.
[Age-Group](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/19e292e9-4444-4f48-b4b3-8e8df44fe08d)


# Analysis
1. KPIs
[KPI 1](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/22b2bf8d-53ef-48f2-93ca-d050253df25d)

2. Sales Trend
[Sales Trend](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/60142a66-d467-4742-bf28-e178ad9255a7)

3. Revenue Contribution by Category

[Revenue contribution by category](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/4f7f2632-84d7-4191-bf23-9a01bbb5d9ac)

4. Sales by Gender
   
[Sales by gender](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/c1ac4b9f-3bfc-4beb-92c3-bea86d37883b)

6. Delivery Trend
[Delivery Trend](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/1239330d-3495-4af3-bdb3-821d3e8cd4e5)

# Dashboard


# Insights
1. The mobile gadgets (phones and tablets) and Electronics product categories are more than twice the revenue from the other products.
2. Most of the customers returned products because they were either defective or missing items/parts
3. The revenue grew by 43% in the year 2020.
4. Out of the total customers of 11300- 58,287 (52%) are male while 54,713 (48%) are female.
5. The highest percentage of the sales by delivery was through standard delivery as most customers preferred it
6. The highest percentage of revenue came from products bought by females between the ages 77 – 87
7. Mobile phones had the highest sales under the phones and tablets category.
8. Digital Cameras had the largest sales by revenue with a sum of 25,930,720 CHF which represents 24.3% of the total revenue.
9. Zone 3 had the highest sales by revenue.
10. The express delivery channel is the least patronized because it is the most expensive of the delivery channels.


# Recommendation
1. The topmost reason why items were returned is because they were defective, hence the need to properly keep them in store and ensure that they are in good condition before delivery.
2. Mobile phones and electronics should be the products of focus as they drive more sales and profit.









