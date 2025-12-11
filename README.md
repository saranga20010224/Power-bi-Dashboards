# Apparel Sales & Production Dashboard

##  Project Overview
This Power BI project provides a comprehensive analysis of sales and production data for an apparel manufacturing company. It transforms raw Excel data into interactive insights, allowing stakeholders to track revenue, monitor production efficiency, and analyze customer trends across different regions and plants.

##  Data set used
- <a href="https://github.com/saranga20010224/Power-bi-Dashboards/blob/main/Apparel%20company%20data.xlsx">Data set</a>

##  Dashboard Interaction
- <a href="https://github.com/saranga20010224/Power-bi-Dashboards/blob/main/Sales%20dashboard.pbix">View Dashboard</a>

##  Dashboard
<img width="1422" height="849" alt="Dashboard" src="https://github.com/user-attachments/assets/09465544-b3ad-47f9-805f-fc2a498906e6" />
<img width="1426" height="849" alt="Details" src="https://github.com/user-attachments/assets/5c77d546-34e6-406b-804b-ff61221a5b9b" />

##  Questions (KPIs)
This dashboard allows users to answer critical business questions and track Key Performance Indicators (KPIs), including:

* **Financial Performance:** * What is the **Total Sales Revenue** and **Gross Profit** generated?
    * Which **SBU (Strategic Business Unit)** is most profitable?
* **Order & Product Analysis:**
    * What is the total **Order Quantity** by Product Category (e.g., T-Shirts, Sets) and Gender?
    * Which **Styles** are the top performers?
* **Operational Efficiency:**
    * What is the average **Production Lead Time** per order?
    * How many **Total Production Hours** were consumed across different plants?
    * What is the efficiency (**EPM**) per order?
* **Market & Customer Insights:**
    * Who are the top **Customers** by revenue?
    * Which **Destinations** (Countries/Regions) have the highest demand?

##  Process
The development process involved the following steps:

1.  **Data Extraction:** * Imported raw sales and production data from Excel.
2.  **Data Transformation:**
    * Used Power Query to clean data, ensuring correct data types for fields like `Garment Delivery Date` and `Order Confirmed Date`.
    * Standardized categorical fields for filters (Destination, Plant Name, Gender).
3.  **Data Modeling & Calculations:**
    * Created DAX Measures to calculate total values for `Order Qty`, `Total Sales`, and `Gross Profit`.
    * Established time-intelligence calculations to track performance by `Sales Month`.
4.  **Dashboard Design:**
    * Designed an interactive layout with slicers for **Plant Name**, **Month**, and **Customer**.
    * Implemented visuals such as Bar Charts for category comparison, Line Charts for monthly trends, and Card visuals for headline KPIs.

##  Result
The final deliverable is a dynamic dashboard that empowers the apparel company to:
* **Visualize production vs. sales performance** at a glance.
* **Identify bottlenecks** by analyzing production lead times and minutes consumed per garment.
* **Maximize profitability** by focusing on high-margin customers and top-performing product categories.
