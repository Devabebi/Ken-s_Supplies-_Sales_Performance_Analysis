# Ken-s_Supplies_Sales_Performance_Analysis
Ken’s Supplies struggled to understand year-over-year sales performance across product subcategories, which made it difficult to optimize inventory, pricing, and future product investments. To address this, I conducted a comprehensive analysis using Tableau, focusing on key business metrics such as sales revenue, profit, and quantity  sold. 

![office-supplies](https://github.com/user-attachments/assets/1ccfa646-f53b-4017-8137-9ecd7e7e4bc9)

🔒 Disclaimer
All datasets and reports used in this portfolio are entirely fictitious and contain no proprietary, confidential, or sensitive information from any company, institution, or individual. The information presented is dummy data created solely to demonstrate my capability in using Tableau for advanced analytics within the real estate industry.

## Table of Content
- [Business Overview](#business-overview)
- [Problem Statement](#problem-statement)
- [Project Rationale](#project-rationale)
- [Aim of the Project](#aim-of-the-project)
- [Data Description](#data-description)
- [Modelling](#modelling)
- [Visual Insight](#visual-vnsight)
- [Analysis](#analysis)
- [Dashboard Insight](#dashboard-insight)
- [Recommendations](#recommendations)


## Business Overview
<img width="1723" height="1986" alt="image" src="https://github.com/user-attachments/assets/aa5350c8-cf66-4564-b92e-cb63bce13153" />

Ken’s Supplies is a leading provider of office supplies, furniture, and technology products, offering a wide variety of subcategories like accessories, appliances, binders, copiers, and more. Our goal is to ensure that businesses have access to high quality products that enhance productivity and create functional work environments . With a commitment to meeting customer needs, we aim to provide reliable products across multiple industries.
In a rapidly evolving market, Ken’s Supplies is leveraging data analytics to optimize product offerings and ensure customer satisfaction. By using insights from sales data , we’re driving innovation and enhancing product availability to remain competitive in today’s dynamic business environment.


## Problem Statement
Ken’s Supplies aims to improve its understanding of sales performance across product subcategories, focusing on metrics such as sales revenue, profit, and quantity sold . The current challenge lies in identifying year over year trends in these metrics and analyzing how different product subcategories contribute to overall performance. Without a clear view of the sales trends and profit margins by subcategory, it’s difficult to make informed decisions regarding inventory management, pricing strategies, and future product investments.

## Project Rationale
<img width="1192" height="1369" alt="image" src="https://github.com/user-attachments/assets/d200ce85-e3c4-4127-9dfd-10a2344c0238" />

To stay competitive in today’s market, Ken’s Supplies must have a thorough understanding of year over year sales performance and product trends. By analyzing key metrics like sales revenue, profit, and quantity sold across various product subcategories, we can identify growth opportunities and address underperforming areas.


## Aim of the Project

- **1** Provide an overview of year over year sales performance, focusing on sales revenue, profit, and quantity.

- **2** Analyze sales trends, identifying top performing and underperforming areas.

- **3** Improve profitability and sales growth by understanding key performance metrics across product subcategories.

- **4** Visualize sales metrics and trends using Tableau to present actionable insights to decision makers.


## Data Description

Ken’s Supplies relies on a comprehensive data model to track and analyze sales, profit, and quantity sold across various product subcategories. 
The main table, Orders , serves as the central dataset containing critical fields such as Order ID, Sales, Profit, Quantity, and Customer Information. This table is enriched with data from other sub tables to provide deeper insights into customer demographics, product details, and location based trends.

## Modelling
<img width="1245" height="677" alt="Screenshot 2025-10-24 164852" src="https://github.com/user-attachments/assets/e9561a0f-7c1d-4d79-afca-203351a350b3" />

- **1.Main Table:** Orders
**Fields:** Row ID, Order ID, Ship Date, Ship Mode, Customer ID, Segment, Postal Code, Product ID, Sales, Quantity, Discount, Profit.

- **2.Sub tables:**
**Customers:** Links customer name and ID.
**Location:** Adds postal code, city, state, region, and country.
**Products:** Includes product ID, category, subcategory, and product name.

By combining these tables in a data model, I can perform comprehensive analyses to better understand sales performance at both the product and customer levels.


## Visual Insight

- **KPI**
- **Bar Charts**
- **Line Charts**

  
## Analysis
- **KPIs**
This visualization presents key performance indicators (KPIs) for Total Sales, Total Profit, and Total Quantity at Ken's Supplies, along with a comparison of their monthly sales trends to the previous year (PY). In 2022, Total Sales reached $609K, reflecting a 29.5% increase over the previous year. Total Profit for 2022 was $81.8K, a 32.7% improvement compared to the prior year, while the total quantity sold was 9.8K, marking a 23.3% growth year-over-year. These KPIs highlight strong overall business performance and growth in 2022.

<img width="1084" height="253" alt="Screenshot 2025-10-24 170424" src="https://github.com/user-attachments/assets/12a04fb5-0260-4d9b-a590-897f2cd0e93a" />

- **Bar Charts**

This bar chart compares sales and profits by category at Ken's Supplies to the previous year (PY), highlighting variations in subcategory performance. It reveals that while some subcategories saw improvements in both sales and profits, others experienced significant declines. The black bars represent profit, while the yellow bars indicate losses. Notably, supplies showed the largest loss at -$7K compared to the previous year, followed by tables, bookcases, and labels, indicating areas of concern for further analysis and potential strategic adjustments.

<img width="535" height="404" alt="Screenshot 2025-10-24 170647" src="https://github.com/user-attachments/assets/979cef5b-1766-4e90-83d7-cbbddc7c4022" />

- **Line Charts**
  
This trend chart visualises the weekly sales and profit trends for the current year (CY), along with the respective average sales and profit values. It highlights periods where current sales and profits exceed or fall below their respective averages. The black line indicates weeks where sales and profits are above the average, while the yellow line represents weeks where they fall below. This visualisation provides a clear comparison of performance against the average, offering insights into fluctuations and helping identify periods of higher or lower profitability.

<img width="540" height="407" alt="Screenshot 2025-10-24 171305" src="https://github.com/user-attachments/assets/9e006fff-8a54-4075-a87d-957d6d3d6065" />


## Dashboard Insight
The dashboard provides a comprehensive analysis of sales performance over a one-year period, from 2021 to 2022. It incorporates interactive parameters that allow users to filter and view performance data for a specific year, enabling focused analysis and comparison of sales trends across different time frames.

<img width="1226" height="702" alt="Screenshot 2025-10-24 171604" src="https://github.com/user-attachments/assets/c20a0bb9-9057-4366-8336-c541f0272348" />


## Recommendations
Based on my analysis, here are some recommendations to help stakeholders at Ken’s Supplies enhance sales performance in the coming year:

**Focus on underperforming categories** by addressing subcategories such as tables, machines, and bookcases that have shown notable losses. Investigate potential causes such as pricing, product quality, or fluctuations in demand, and take corrective action to improve profitability.

**Leverage high-performing subcategories** by capitalising on those that have demonstrated strong growth in sales and profit. Increase stock levels, introduce targeted promotions, or expand marketing activity to stimulate further growth in these areas.

**Optimise pricing strategy** by reviewing pricing structures for both high- and low-performing products. Use insights from weekly sales trends and average performance to set competitive prices that maximise profit without compromising sales volume.

**Use sales trend data to optimise stock management**, ensuring that high-demand products are well-stocked while reducing inventory for underperforming items to avoid surplus stock.

**Implement targeted marketing campaigns** focusing on product subcategories that have shown consistent growth or steady demand throughout the year, directing efforts towards the customer segments most responsive to these products.

**Offer product bundles** that combine high-margin items with lower-performing products to encourage multiple purchases, thereby improving overall sales performance across a broader product range.

**Utilise customer segmentation insights** to personalise offers and promotions. Tailor product mixes, pricing, and discounts to the preferences of specific customer segments to increase engagement and sales.

**Leverage cross-selling and upselling strategies** by promoting complementary products within high-demand categories, increasing the total transaction value per customer.


## Thank you
Reach out for more info!
<img width="1584" height="396" alt="Python SQL R MachineLearning MySQL DataAnalysis DataVisualization Statistics BigDataAnalysis Pandas NumPy CloudComputing AWS Azure Tableau CommunicationSkills ProblemSolving BusinessIntelligence PostgreSQL" src="https://github.com/user-attachments/assets/17cf4c31-ca6e-4ce6-9df4-d99065de351e" />
