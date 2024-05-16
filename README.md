# Sales Dashboard

### Dashboard Link : https://public.tableau.com/views/SalesWorkBook_16932521457770/SalesDashboard_1

**The Objective of the Sales Dashboard:**

The objective of the report is to analyze and present comprehensive and interactive insights into sales, profit, revenue, orders details, profit margin, and various comparisons by different categories. It aims to provide a clear understanding of key performance indicators and trends using Tableau.

**1. Scope of the Project**

To generate the three different categories in single dashboard view by using different visuals.
Categories are,

•	Sales Details
•	ShipMode Details
•	Customers Details

To displays the sales details by using different visuals, 
•	KPI cards & Sales Channels - No. of Orders
•	Profit by Country based on Sales Channel 
•	Sales % & No. of Orders of Priority Status
•	Yearly Revenue Trend
•	Sales by Products 
•	Sales by Country & No. of Products

To display the ShipMode details by using different visuals,	
•	ProfitRatio by ShipMode	
•	Total Sales & Region by ShipMode	
•	No. of Orders by ShipMode	
•	Profit % by ShipMode	
•	Sales % by ShipMode/No. of Customer
•	Yearly 	Sales/Profit by ShipMode

To display the Customer details by using different visuals,
•	Sales by Top 10 Customer	
•	Order Details 

**2. The report objectives can be summarized as follows**
1) Gather Data - Load data into Tableau Desktop Public, dataset is a Excel file.
2) Create Data Model - Design and create a data model that represents the relationships between different tables in data. This step is crucial for accurate analysis and visualization.
3) Develop Reports - Use the Tableau Public application to create reports based on the data model. Add visualizations such as charts, tables to represent the data effectively. Apply filters, slicers, and drill-through functionalities to allow users to interact with the data. The visuals summarized as below,

**KPI Cards & Sales Channels - No. of Orders :**
Included Total Cost, Total Profit, Total Sales, Total Revenue, Total Orders, Total Products and Avg. WightingDays, as a single sheet card visuals. And Created the Sales channel wise order count as a visual. Color shows details about Sales Channel.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/caa7cf1f-3e09-407e-a809-12d585729440)

**Profit by Country based on Sales Channel :**
Created Sum of Total Profit for each Country. Color shows details about Sales Channel. The marks are labeled by sum of Total Profit.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/0737bb7d-3fe9-4db1-921e-fda94eb28f6a)
 
**Sales % & No. of Orders of Priority Status :**
Created % of Total Units Sold, Order Priority_Status and count of Order ID. Color shows details about Order Priority_Status. The marks are labeled by % of Total Units Sold, Order Priority_Status and count of Order ID.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/7ef4b807-a4e6-4d8a-bb3f-ea5c1361dc1a)

**Yearly Revenue Trend :**
Created the trend of sum of Total Revenue for Order Date Year & Perform the drill down.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/465e408a-1c60-43cf-a94f-26838caaef10)
 
**Sales by Products :**
Created the % of Total Units Sold for each Products. Color shows % of sum of Total Units Sold. The marks are labeled by % of Total Units Sold.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/53bec755-4d88-4e34-a4c8-0e169f14797e)

**Sales by Country/No. of Products :** 
Created the trends of Total Sales and count of Products for Country. Color shows details about Total Sales and count of Products. The marks are labeled by Total Sales & No. of Products.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/fc2ae450-0b87-4c07-8add-4f598d3c341c)

**ProfitRatio by ShipMode :**
Created the trend of % of Total Profit Ratio for Order Date Year. Color shows details about Ship Mode. The marks are labeled by % of Total Profit Ratio.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/79dcfcae-f045-4050-99c2-cb204c0fcc0b)

**Sales/Region by ShipMode :**
Created Sum of Units Sold for each Ship Mode. Color shows details about Region. The marks are labeled by sum of Units Sold.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/98b3e9d1-dca0-4176-a10d-2b7d39d3385f)
 
**No. of Orders by ShipMode :**
Created Count of Order ID for each Ship Mode. Color shows details about Ship Mode.

 ![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/6bb771fd-5f97-4379-b9ae-02a0b8b11d90)

**Profit % by ShipMode :**
Created % of Total Profit for each Ship Mode. Color shows based on % of Total profit. The marks are labeled by Ship Mode, and % of Total Profit.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/668ec866-50a8-4e6a-bdcd-51ecd3ec7154)
 
**Sales % by ShipMode/No. of Customer :** 
Created Sum of Units Sold. Color shows details about Ship Mode. Size shows % of sum of Total Units Sold. The marks are labeled by Ship Mode, % of Total Units Sold and count of Customer ID.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/45c06488-738c-42e8-ba15-3b20031cde8b)

**Yearly Sales/Profit by ShipMode :** 
**1) Yearly Total Sales by ShipMode :**
Sum of Dynamic Measure as a Total Sales for each Order Date Year broken down by Ship Mode. Highlighted the Avg line & Max point. 

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/0126a4d0-f217-45f5-be34-3a620ffa498b)
 
**2) Yearly Total Profit by ShipMode:**
Sum of Dynamic Measure as a Total Profit for each Order Date Year broken down by Ship Mode. Highlighted the Avg line & Max point.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/08b7d0bb-6485-41a8-9711-f1b541f927a9)

**Sales by Top 10 Customers :**
Sum of Units Sold and Customer Name. Color shows sum of Units Sold. Size shows sum of Units Sold. The marks are labeled by sum of Units Sold and Customer Name.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/b4321df7-8043-407d-8203-e769337e95b1)

**Order Details :**
Sum of WightingDays broken down by "Wighting Days" vs. Order ID, Customer Name, Region, Country, Order Priority_Status, Sales Channel, Ship Mode, Item Type, Avg. Sales per Order and Avg. Revenue per Order. Color shows sum of WightingDays.

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/8caca4b0-0f65-4164-bd03-9cfa6f6dceef)

**3. Impacts:** 
•	The Sales Dashboard more reliable and gives you more convenient access to sales insights.
•	The Dashboard is more interactive and its ability to drill down for the visuals which have Yearwise data and overall to interact with the granular details of data.
•	The data is filtered on Region, Product Type, Year, Ship Mode.
• With the help of reset filter, The data is reset to its default view.
•	A dashboard helps to identify the opportunities to make changes and increase revenue. 
•	A dashboard allows you to quickly identify who your best customers are, where your challenges lie, and what changes might be needed to drive sales.
•	It can also help with forecasting future revenue.

**Snapshot of Sales Dashboard (Tableau Desktop Public)**

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/bf2d31d3-b21d-4b6a-a51c-9b9046776587)

![image](https://github.com/yoga9/Tableau_Sales-Dashboard/assets/80407876/de71ca77-233b-422c-97e7-9a85a954abd8)




