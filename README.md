# E-Commerce-Logistics-Analytics

Project Overview:

This project analyses e-commerce shipping data using Microsoft Power BI to explore delivery performance and identify potential factors associated with shipment delays.
The objective is to demonstrate how data analytics can support logistics performance monitoring and supply chain decision-making.

Dataset:

Source: E-Commerce Shipping Data — Kaggle
Records: 10,999
Data type: Public e-commerce shipping dataset
The dataset includes shipment modes, warehouse blocks, product characteristics, customer information, and delivery status.

Tools & Skills:

Power BI Desktop: Interactive dashboards and KPI reporting
Power Query: Data profiling, cleaning, and transformation
DAX: Measures, calculated columns, and KPI calculations
Data Visualization: Bar charts, column charts, matrices, slicers, and tooltips
Data Analysis: Segmentation, comparative analysis, and business insights

Dashboard 1 - Logistics Performance Overview:

The first dashboard evaluates delivery performance across shipping modes and warehouse blocks.

Key KPIs:

Total Shipments: 10,999

Late Shipments: 6,563

Late Delivery Rate: 59.7%


Key Findings:

Out of 10,999 shipping records, the overall late delivery rate is 59.7%.
The delay rates for different modes of transport are pretty similar, ranging from 58.8% to 60.2%.
Among  Warehouses Block & Shipping Mode, flight shipment from Warehouse C has the highest delayed delivery rate at 62.4%, it's suggested to investigate further.


Dashboard 2 - Delivery Risk Analysis:

The second dashboard explores associations between delivery delays and product characteristics.

Key Findings:

High-importance products have the highest late delivery rate at 65.0%, compared with approximately 59% for other importance categories.
Delivery rates vary substantially across product weight groups. However, some high-delay groups contain very few records and should be interpreted cautiously.
Products in the 100-149 cost range show a late delivery rate of 65.5%, compared with 44.8% for the 300-349 range, suggesting a potential association between product cost and delivery performance. 

Business Recommendations:

Investigate high-delay shipment segments before prioritising operational improvements.
Monitor both delivery rates and shipment volumes to avoid misleading conclusions from small samples.
Examine product characteristics alongside logistics processes when assessing potential delivery risks.

Limitations:

This is an independent portfolio project based on a public dataset, not a real-world company engagement.
The findings are exploratory and do not establish causal relationships. The dataset also lacks detailed delivery timestamps, carrier performance measures, and shipping costs.

Project Files:

The repository will contain the Power BI report file (.pbix) and screenshots of both dashboards.

Author:
Siqi Jin
