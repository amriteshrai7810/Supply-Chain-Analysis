# Supply Chain Analysis

To analyze Atliq Mart’s service level performance (OTIF, LIFR, VOFR) across cities and customers to identify factors contributing to customer contract non-renewals. This analysis will provide data-driven insights through trend tracking, target comparisons, and drill-down capabilities to drive service improvements.

## Datasets

• dim_customers: Contains customer details, including customer ID and city.

• dim_products: Stores product information such as product ID and category.

• dim_date: Provides date-related data for analysis.

• dim_target_orders: Includes OT and IF target metrics.

• fact_order_lines: Records order details, including delivery and shipped dates.

• fact_order_aggregate: Aggregates fact_order_lines data at the order level.

The data was modeled using a star schema, with fact tables capturing order details and dimension tables providing contextual information.

<h2> Model </h2>

![image](https://github.com/user-attachments/assets/c6a96b1e-5369-492d-afeb-b3ebdb4cd314)


<h2> Dashboard Overview </h2>
<b>Order:</b> Overview of total orders, OT, IF, and OTIF %, highlighting overall fulfillment performance.

![image](https://github.com/user-attachments/assets/ac1fb480-ec58-428e-93f5-232443c3e04d)

<b> Customer Split: </b> Tracks OT, IF, and OTIF % for each customer store, analyzing service performance.

![image](https://github.com/user-attachments/assets/f5045a27-ea5b-44ac-a299-dd9685f3b57a)

<b> Metrics Over Time:</b> Displays OT, IF, OTIF %, LIFR, and VOFR trends with drill-down options for detailed analysis.

![image](https://github.com/user-attachments/assets/8b143982-95f2-42c3-a174-0ee07f5bbebb)

<b> Order Lines: </b> Tracks LIFR and VOFR, showing the number of order lines filled and completed.

![image](https://github.com/user-attachments/assets/9dd4c35d-a267-4278-97e8-a105eefae7c1)

<b> Line Lead Analysis: </b> Highlights delayed products by food category and customer-wise lead time.

![image](https://github.com/user-attachments/assets/f96f0f3c-60a6-4cb9-9b41-e8ece8fa499b)

<h1>Insights</h1>

• Given the persistent low Line Fill Rate, delivery delays, and supply chain inefficiencies, there is a high risk that Lotus Mart, Cool Blue, and Acclaimed Store may choose not to renew their contracts.

1. OT, IF, and OTIF consistently miss targets on both daily and monthly levels, pointing to forecasting issues, inventory shortages, or procurement delays.

2. Lotus Mart, Cool Blue, and Acclaimed Store struggle with low Line Fill Rate (LIFR) and frequent delays due to poor inventory management and supply shortages.

<h1>Recommendations</h1>

 1. <b> Improve Logistics & Lead Time Management: </b> Optimize order processing, warehouse operations, and transportation planning to reduce delays. Implement real-time tracking and collaborate with reliable logistics partners for faster deliveries.

 2. <b> Optimize Inventory Management: </b> Improve demand forecasting and stock replenishment to reduce shortages and delays.

 3. <b> Diversify Supplier Base: </b> Onboard multiple vendors for critical items to mitigate supply risks, ensure consistent stock availability, and improve Line Fill Rate (LIFR).









