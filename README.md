
# Sales-Product



## Problem Statement

In this project, I investigated the root cause of a noticeable revenue drop during 2017 and 2018 by analyzing key business KPIs including:

Revenue

Profit

Cost

Quantity Sold

Number of Orders


The goal was to understand whether the revenue decline was due to reduced sales volume, high costs, low pricing, or changes in product performance.

🔍 Key Insights & Approach:

Built dynamic visuals to track:

Revenue Over Time

Revenue by Region, Channel, Promotion, and Category

YoY Revenue Comparison to identify specific years or months with a drop


Created conditional color formatting to highlight revenue drop zones (in red)

Used Drill-Through Analysis to go from overall decline → region → country → channel → product level, enabling detailed investigation into where exactly the drop happened

Applied Tooltips to instantly show the percentage distribution of Revenue, Profit, and Cost, plus the top-selling product and months with highest and lowest revenue


🎯 Impact: This analysis allowed the business to distinguish between harmful and acceptable revenue drops (e.g., low revenue but high profit or low cost is still a positive scenario). It also supported making strategic decisions about pricing, promotion, and product focus for future improvement


Actions & Business Recommendations

For products that didn’t perform well in sales, I considered bundling them with high-performing promotional products to increase their exposure and drive sales. I conducted a product analysis to determine whether pricing was a barrier — for example, whether the product was priced too high compared to its perceived value.

I also evaluated the sales team's approach, questioning whether ineffective communication with customers might have contributed to the poor performance. Additionally, I analyzed stock levels and timing, checking whether the product was available in sufficient quantity during the peak months of demand.

Finally, I examined potential issues with marketing efforts, such as lack of visibility or improper targeting, which could also explain the low sales figures.


### Steps followed 

- Step 1 : Load data into Power BI Desktop From dataset is a Excel file.

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

![Image](https://github.com/user-attachments/assets/50dc85cd-ef72-48ea-95d9-434a7b7bddcd)

- Step 3 : Also Check Data Valid by use Captlize Each Word & Trim, detect Data type".
![Image](https://github.com/user-attachments/assets/36d93b68-7fef-4ccf-8c1b-dc50edaaffc3)

- Step 4 :  Merge Queries to denormalize Data".

![Image](https://github.com/user-attachments/assets/2fa0fb43-5a27-42eb-ad3e-6f0dc644e335)


- Step 5 : load data into data model make star schema model to help us in calculation


Create Data Model 

![Image](https://github.com/user-attachments/assets/6446cf0f-585f-48a8-a785-333f71008a4e)

- Step 6 : make Caluclation by DAX .

![Image](https://github.com/user-attachments/assets/239d7e54-7a5c-48b9-bec1-bc345de85ff9)

- Step 7 : Build Revenue Dashboard 
Create Four Card (Revenue,Profit,Cost,Quantity,Orders)

 insights
 
Revenue Over time

Revenue By Product Category

Revenue By  Region

Revenue By Promotion

Revenue By Channel



![Image](https://github.com/user-attachments/assets/f087d5b3-83fd-43b9-a302-6557d14f99e0)


Provide year-over-year

![Image](https://github.com/user-attachments/assets/1c3eac32-ba6d-440d-be4b-0cd8eac70e6e)
. 
- Step 8 : Visual filters (Slicers) were added for Four fields named "Year","Product Category" ,"Region" ,"Manufacturer".

![Image](https://github.com/user-attachments/assets/4d4e1a22-64fd-4de9-ad80-60b3ff593ecc)



- Step 9 :  Root Cause analysis 

Through root cause analysis, we identify specific problems across various dimensions such as region, country, city, channel, and product. This analysis helps us pinpoint the weak points and understand the underlying reasons behind them.

For example, in a particular country, the drop in sales during a certain quarter may be due to seasonal products that do not sell well during that period. Therefore, we propose replacing these products with others that are more in demand during that time to improve sales performance.

![Image](https://github.com/user-attachments/assets/1c8e5a98-38c3-4ca0-8b90-665296dc105d)


           
- Step 10 : use Tooltips to provids details

Through the tooltip, we can see the percentage of sales relative to the total sales, the percentage of profit relative to the total profit, and the percentage of cost relative to the total cost.

It also shows monthly sales performance, which helps us identify the months with the highest sales. This insight allows us to reduce costs, ensure product availability, and create targeted promotions during peak sales periods.

![Image](https://github.com/user-attachments/assets/f042a4da-4099-462c-a94f-2655476aef2b)
