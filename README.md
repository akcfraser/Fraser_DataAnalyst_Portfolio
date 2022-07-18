# Fraser_DataAnalyst_Portfolio
Data Analyst Portfolio 

# [Project 1: Sleep Study - Exercise and Sleep on Energy Levels][]
* Record qualitative and quantitative data in a Google Sheets spreadsheet and create a secondary sheet to include a legend outlining the format of each data type. 
* Clean data after collection and analyse the data to identify patterns and create solutions. 
* Once data analysis is complete, create a data visualisation using Tableau Public to easily share results in an easy-to-understand format. 
* Create a presentation using Google Slides to present the findings.

# [Project 2A: Importing and Data Cleaning in Excel - Sample](https://github.com/akcfraser/Fraser_DA_Portfolio/blob/main/Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.xlsx)
* Cleaning and importing another department's inventory data in Microsoft Excel. 
* Adjusted column widths, removed empty rows, used conditional formating to identify and remove duplicate records, fixed spelling errors, removed additional white spaces, and correctly merged and formatted department names. 

# [Project 2B: Pivot Tables and Basic Calculations in Excel - Sample](https://github.com/akcfraser/Fraser_DA_Portfolio/blob/main/Montgomery_Fleet_Equipment_Inventory_FA_PART_2_END.xlsx)
* Formatted the data as a table and calculated the following values: SUM, AVERAGE, MIN, MAX, COUNT.
* Created a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section. Secondly, I sorted the pivot table to sort the table in descending order by the sum of equipment count.
* Created two additional pivot tables to match the aforementioned pivot table. In the second pivot table, I added the Equipment Class field below the Department field so that the different vehicle types appear under each department with their respective counts. Secondly, I collapsed all fields except the Transportation field.
* In pivot table 3, I added the Equipment Class field above the Department field so that the different vehicle types appear first, with the different departments listed underneath each vehicle type with their respective counts. Secondly, I collapseed all fields except the CUV field. 

![](https://raw.githubusercontent.com/akcfraser/Fraser_DataAnalyst_Portfolio/main/images/PT%20-%20Department%20and%20Sum%20of%20Equipment.png)
![](https://raw.githubusercontent.com/akcfraser/Fraser_DataAnalyst_Portfolio/main/images/PT%20-%20Department%3AType%20and%20Sum%20of%20Equipment%20COUNT.png)
![](https://raw.githubusercontent.com/akcfraser/Fraser_DataAnalyst_Portfolio/main/images/PT%20-%20Equipment%20Class%20and%20Sum%20of%20Equipment.png)

# [Project 3A: Creating Charts in Excel](https://github.com/akcfraser/Fraser_DA_Portfolio/blob/main/CarSalesByModelEnd.xlsx)
* Created a "Quantity Sold by Dealer ID" bar chart.

![](https://raw.githubusercontent.com/akcfraser/Fraser_DataAnalyst_Portfolio/main/images/Screenshot%202022-07-08%20at%209.28.29%20am.png)

* Created a "Profit by Date and Model" line chart.

![](https://raw.githubusercontent.com/akcfraser/Fraser_DataAnalyst_Portfolio/main/images/Screenshot%202022-07-08%20at%209.28.41%20am.png)

* Created a "Profit by Year and Dealer ID" column chart.

![](https://raw.githubusercontent.com/akcfraser/Fraser_DataAnalyst_Portfolio/main/images/Screenshot%202022-07-08%20at%209.28.51%20am.png)

Created a "Profit of Hudson Models by Dealer ID" line chart. Additionally, I removed the horizontal gridlines from the chart, put the legend on the right side of the chart, and coloured the series outline in green. 

![](https://raw.githubusercontent.com/akcfraser/Fraser_DataAnalyst_Portfolio/main/images/Screenshot%202022-07-08%20at%209.29.01%20am.png)

# [Project 3B: Creating Visualisations with IBM Cognos](https://github.com/akcfraser/Fraser_DA_Portfolio/blob/main/Sales%20and%20Service%20Dashboards.pdf)
* Created a "Sales" dashboard to capture the following KPI metrics:
  * In Panel 1, show Profit formatted to 1 decimal place in millions of US dollars. 
  * In Panel 2, capture Quantity sold.
  * In Panel 3, capture Quantity sold by model as a bar chart.
  * In Panel 4, capture Average quantity sold.
  * In Panel 5, display 'Profit' by 'Dealer ID' as a column chart, sorted in ascending order.
  
![](https://raw.githubusercontent.com/akcfraser/Fraser_DataAnalyst_Portfolio/main/images/Sales%20Dashboard%20image.png)

* Created a "Services" dashboard to capture the following KPI metrics:
  * In Panel 1, capture the number of recalls per model of car as a column chart.
  * In Panel 2, capture the customer sentiment by comparing positive, neutral, and negative reviews as a treemap.
  * In Panel 3, capture the quantity of cars sold per month compared to the profit as a line and column chart.
  * In Panel 4, capture the number of recalls by model and affected system as a heat map. 
  
![](https://raw.githubusercontent.com/akcfraser/Fraser_DataAnalyst_Portfolio/main/images/Services%20Dashboard%20Image.png)

# [Project 4: Python for Data Science Project](https://github.com/akcfraser/Fraser_DA_Portfolio/blob/main/Python%20Data%20Science%20Project.ipynb)
* Extracted financial data such as historical share price and quarterly revenue reportings from various sources using Python libraries and webscraping on popular stocks. After data collection, I visualized the data in a dashboard to identify patterns or trends. 
  * The stocks worked with are Tesla, Amazon, AMD, and GameStop.
  * Software used: IBM Watson 

# [Project 5: SQL Queries - Sample](https://github.com/akcfraser/Fraser_DA_Portfolio/blob/main/DB0201EN-PeerAssign-v5.ipynb)
* Using Jupyter Notebooks, I composed and executed SQL queries to answer the following questions:
  * Find the total number of crimes recorded in the "crime" table.
  * List community areas with per capita income less than 11000.
  * List all case numbers for crimes involving minors?
  * List all kidnapping crimes involving a child?
  * What kind of crimes were recorded at schools?
  * List the average safety score for all types of schools.
  * List 5 community areas with highest % of households below poverty line.
  * Which community area (number) is most crime prone?
  * Use a sub-query to find the name of the community area with highest hardship index.
  * Use a sub-query to determine the Community Area Name with most number of crimes?
