# Online Sales Analysis in Excel



# Project Brief
A supermarket (An Online store) that sells all varieties of items in different categories, from Fashion to Home and Office supplies. They have the dataset of their shopping over 5 years, from 2015 to 2020. The CEO wants to see how the supermarket is faring according to key performance indicators. We have been assigned to identify the key areas within the business that need clarification and get them sorted out as soon as possible. We are to analyze the sales dataset develop visualizations and  a report

## Tasks
Perform analysis on the following:

* Total revenue by product category

* Revenue by Year

* Top 5 Product subcategories by revenue

* Product category by Total revenue, percentage of total revenue, total orders and percentage of total orders

* Customers' gender by revenue across the years

* Customers' gender by percentage

* Percentage of revenue by gender across age groups

* Which of the delivery channels have the biggest revenue by percentage?

* Reasons why customers return some of the items purchased?

* Which Zone has the highest revenue
  
![image](https://github.com/user-attachments/assets/610313bf-8fdf-47f9-8a91-55134a622265)

  

## Data Structure
The dataset was obtained from the supermarket's Data Entry officer. It contains 113,000 rows and 18 columns of sales records with fields like Order date, Order ID, Delivery date, Customer age, Gender, Delivery type, Product category, etc.

 ![Data structure Image](/https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Data%20structure.PNG "Raw Dataset))
*Picture of raw dataset

## KPIs
The Key Performance Indicators include: 
* Total Revenue
* Total Orders 
* Total Shipping Fee
* Total Number of Customers and 
* The Average Delivery Days of products
  
!

## Tool: Microsoft Excel
The analysis of the dataset was done on Microsoft Excel using PivotTable.

# Data preparation and cleaning
* Copy and paste the data into another sheet.
* Checked for duplicate orders using Highlight Cells Rules in the Conditional Formatting feature on the OrderID column and CustomerID Column.
* Check for completeness and uniformity of the data items using the filter feature.
* A new column was created: Year, derived from  the OrderDate column.
  ![Year](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/64861c69-26fc-4ade-a350-4c18b3b9791a)

* To find the average delivery days, a new column was created by subtracting the OrderDate from the DeliveryDate. On the PivotTable, we summarized the value field by 'Average' to get the average days of delivery.

  ![Delivery Day](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/0e6968c4-52a7-40a2-b275-018576d41d61)
  
  ![Average Delivery Days](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/b7d01699-cfb3-40d4-b701-8e7a2e443246)

* To find the total sales, a new column was created using the product function on the Unit price and Quantity ordered column.
  ![Total sales](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/ce309bb8-57ef-431f-8e59-d6b06fb32bc7)

* A new table ‘Age Group’ was created in a new sheet
  ![Age_Group Table](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/5e7701b3-622c-42b6-939c-f1c90a5223ef)

* To get the corresponding age group the Vlookup function was used.
![Age-Group](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/19e292e9-4444-4f48-b4b3-8e8df44fe08d)


# Analysis
 * KPIs
   ![KPI 1](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/assets/133680175/89d74aa2-9fc8-4327-832f-1f6dfbe8aa75))
   
* Total revenue by product category
     ![Total revenue by product category](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Rvenue%20by%20product%20category.JPG))
* Revenue by Year
 ![Revenue by Year](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Revenue%20by%20Year.JPG))

* Customers' gender by revenue across the years
  ![Customers' gender by revenue across the years](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Revenue%20by%20Gender%20by%20Year.JPG))
  
* Customers' gender by percentage
  ![Customers' gender by percentage](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Gender%20by%20Percentage.JPG))
  
* Which of the delivery channels have the biggest revenue by percentage?
  ![Revenue by Delivery Channel](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Revenue%20by%20Delivery%20Channel.JPG))
  
* Percentage of revenue by gender across age groups
  ![%Revenue by Gender across Age groups](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/%25Revenue%20by%20Gender%20across%20Age%20groups.JPG))
  
* Top 5 Product subcategories by revenue
 ![Top 5 Product subcategories by revenue](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Top%205%20Sub%20Category.JPG))
  
* Product category by Total revenue, percentage of total revenue, total orders and percentage of total orders
  ![Revenue & Orders](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Rvenue_Order.JPG))
  
* Reasons why customers return some of the items purchased
  ![Reasons for Returned Items](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Retuned%20Items.JPG))
  
* Product category by Total revenue across Zones
  ![Revenue across Zones](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Revenue%20by%20zone.JPG))
  

# Dashboard
![Sales Dashboard I](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Sales%20Dashboard%20I.JPG))

![Sales Dashboard II](https://github.com/Ms-khadijatOparemi/ONLINE-SALES-ANALYSIS-WITH-EXCEL/blob/main/Sales%20Dashboard%20II.JPG))


# Insights
1. The mobile gadgets (phones and tablets) and Electronics product  categories are more than twice the revenue from the other products.
   
2. The revenue grew by 43% in the year 2020.
   
3. Mobile phones had the highest sales under the phones and tablets category.
   
4.  Digital Cameras had the largest sales by revenue with a sum of GHC 25,989,575 which represents 24.3% of the total revenue.
   
5.  While phones and tablets, and electronics categories drive more in total revenue, Fashion and, Health and Beauty are great for cash flow with the  individual order quantity surpassing that of Mobile tablet, and electronics categories combined

6.  Out of the total customers of 11300- 58,287 (51.58%) are male while 54,713 (48.42%) are female.

7.   The highest percentage of revenue (50.3%) came from products bought by males and females between the ages 17–34.

8.   The highest percentage of the sales by delivery was through shipment from abroad followed closely by standard delivery.

9.   Most of the customers returned products because they were either defective or missing items/parts.

10.   Zone 3 had the highest sales by revenue followed by Zone 1 at GHC 46,172,529.95 and GHC  27,074,121.20 respectively.

![image](https://github.com/user-attachments/assets/87683265-315d-4a12-94a9-e093c2f18a75)

![image](https://github.com/user-attachments/assets/0ef92056-64b0-427b-8c0b-6124bcdd239a)


# Recommendation
1. The top reason why items were returned is because they were defective, hence the need to properly keep them in store and ensure that they are in good in transit up until delivery to the customer.

2.  The express delivery channel is the least patronized; this could be a result of the cost of deliver.

3. The Fashion, Health and Beauty Categories should be given high priority in stocking as they are fast-moving goods which are important for cashflow.










