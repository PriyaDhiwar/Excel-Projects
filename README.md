# Ecommerce Sales Analysis Excel Dashboard

**Data Cleaning & Transformation**

•	Checked & removed any null values in the dataset

•	Formatted the data into table (ctrl + T) for data refresh in future for updating the dashboard for any new data entries

*Pivot Table – used to summarize or aggregate the data

**Data Analysis using various measures and dimensions**

**1.	Sales & Profit Analysis**

-Bar Chart

•	Under pivot table fields selected the order date under rows & aggregate values for sum and profit.
![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/88608abc-d2e6-4fef-9334-34ae2a273bb6)
 
•	Formatted the cell numbers into correct data type 

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/3c1b1de9-9650-4c90-a3cf-3ef541180b24) 
![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/d4fbb165-02f2-4c19-b3f6-893361ee21e6)

•	Under Pivot Chart Tab used combo chart for dual axis chart to display trends of the profit against the yearly sales. 

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/42117479-f2d3-4c28-aceb-dfb6cd8afe50)

 
**2.	Category wise Profit Analysis**

-Waterfall Chart

•	Using pivot table fields selected the category and profit to insert waterfall chart

•	Formatted the pivot formula & values on the chart as the waterfall chart does not display when used pivot table. Set Grand total as total value for comparison.

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/ef53c62b-9dd3-4891-a987-1f5cc601fa75)

 

**4. Category wise Share % **

-Doughnut Chart

•	Inserted doughnut chart from pivot chart tab with respective data field values

•	Formatted Chart size and padding

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/99b182a9-a2a3-4d97-81b2-a3de6ff09f02)
 

**6.	Sales By Sate**

-Map Chart

•	Inserted map chart from pivot chart tab with respective data field values but map chart is unable to take data in data of pivot table so we need to separately create the data using formula for dynamic dashboard so that whenever the dashboard gets refreshed when data is updated or refreshed too.

•	Formula used: =GETPIVOTDATA("Sales",$A$3,"State",A4)

•	Formatted the number and removed chart buttons.

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/f2c1bc7f-f06f-4ce8-833c-74f583393c4a)

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/6d9e2df1-8280-49a8-a0e0-e7f5fe8d49a9)

**8.	Top 5 Sub-category Sales**

-Bar Chart

•	Inserted the values & chart under pivot chart tab and used the bar chart to showcase Top 5 sub -category sales. 

•	Right clicked and sorted the values > top 5 items 

•	Formatted the chart & data labels

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/62a1a772-d246-4d65-a7f5-c251ca564f8d)

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/ba0284e0-4171-4322-ae5f-70856ac67a32)

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/be83f748-9797-4c92-8230-4277577c8fcb)
 
**KPI**

•	KPI measures used Total Sales, profit, qty, order count, profit margin %

•	Created sparkline for the KPI measures using pivot table 

NOTE: sparkline can be inserted directly but the it will not appear clearly instead used the line chart and deleted all the data labels from it.

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/8c083420-b349-48a5-97c2-1600afeff621)

•	Profit Margin % measure created using formula total profit/ total Sales by inserting calculated field under pivot chart analyze tab 

•	Created sparkline for profit margin %

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/4d0aa623-3c21-4763-a94c-36f4183a944a)

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/33d9b222-1774-4547-a6b5-404496d0f68a)

•	KPI total numbers formula & data formatted to showcase on dashboard respectively

•	Customized cell format: currency- $0.00, "K"; count of nos- "#" 0 ; percentage- %

NOTE: minimum use of pivot tables increases the dashboard performance

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/78f648bd-68f7-4203-8c75-70ad2387ae6e)

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/1b41931c-3721-43e2-aee8-bed222bc00fc)

**KPI YOY Indicators** 

•	Used pivot table to create new data tables for KPI YOY indicators using measure values total sales, profit, order count, qty, profit margin

•	YOY formula used to analyze YOY growth percentage of sales as comparison to previous sales value

•	YOY Formula: =(GETPIVOTDATA("Sum of Sales",$A$3,"Year",2014)/GETPIVOTDATA("Sum of Sales",$A$3,"Year",2013))-1

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/2c20f6a8-5dbe-495e-b79d-f72e9c340a6f)


•	To show the value in conditional format for positive values as per YOY sales growth in green and negative as red

•	Customized cell format: [Green]▲0.00%;[Red] ▼0.00%

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/24b24152-a65d-4ab4-bda7-c81f3e29fdab)

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/a46ecdb2-3bb6-43ac-862c-f1380762d1ef)



**Dashboard Page Layout**

•	Downloaded textured background from google > selected page layout tab > background > insert background > Go to view tab > unchecked gridlines & headings 

•	Inserted Shapes accordingly to use for charts background & texts

•	Formatted all the charts as per required & used slicer by connecting all the pivot tables for effective functionality.

![image](https://github.com/PriyaDhiwar/Excel-Projects/assets/47880258/bc87a05b-583d-4656-8229-c6e73ea6929d)

**Conclusion**

In conclusion, the E-commerce Dashboard Report provides a comprehensive analysis of Year-over-Year (YOY) growth and Key Performance Indicators (KPIs). The report emphasizes the importance of tracking essential metrics outlined in the E-commerce Metrics + KPIs article, ensuring a strategic approach to business scaling.
In essence, this E-commerce Dashboard Report stands as a strategic resource, allowing businesses to analyze YOY growth, monitor KPIs, and make informed decisions for continued success.
