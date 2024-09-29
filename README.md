# Power-BI-Project-Report-on-Business-Insights-360-for-AtliQ-Technologies-Hardware
Welcome to the Business Insights 360 project repository. This project demonstrates comprehensive data analysis and visualization using Power BI. It covers various aspects of data handling, from extraction and transformation to visualization and reporting, leveraging the robust capabilities of Power BI.
## Company’s Background
AtliQ Hardware is a company that has grown vastly in recent years and opened businesses all over the globe. It sells computers and computer accessories through three mediums/channels:

*Retailers*
*Direct*
*Distributors*

While they grew substantially in the last few years, they also had some bitter experiences in Latin America. They tried establishing their presence there but faced huge losses because all decisions were based on some surveys, intuitions, and some basic Excel based Data Analysis. They were using Excel for analysis but now the company got big so they switched over to PowerBI and wanted to bring lot of transparency in the data and make accurate decisions. Their competitors are growing and making use of data analysis on a large scale and they too want to leverage the power of data analysis. Therefore, AtliQ Hardware had no other option but to build its analytics team for data-driven insights and decisions in the future to survive better in the industry.
## Project Objective
AltiQ Hardware, a global leader in computers and accessories, faced unexpected losses after opening a store in America. These setbacks were identified to be caused due to reliance on outdated methods such as Excel for data analysis. To address this issue, the company's leadership recognized the need for a transformative approach to leveraging data for informed decision-making. With competitors boasting robust analytics teams, AltiQ Hardware recognizes the urgent need to develop its analytics capabilities using Power BI to thrive in the industry.

To outshine competitors, they've adopted Power BI for analytics with 1.8 million transaction records from Excel, CSV, and MySQL. The Power BI Dashboard includes:

**Home Page**: Central navigation for Dashboard.
**Finance**: Enhances financial planning.
**Sales**: Boosts revenue and market share.
**Marketing**: Elevates brand visibility.
**Supply Chain**: Optimizes inventory management.
**Executive**: Provides top management overview.
**Info**: Provides an overview and guidance on how to navigate and use the Power BI Dashboard effectively.
**Support**: Offers resources and assistance for troubleshooting, FAQs, and help with dashboard functionalities.
## Tech Stacks
*Power BI Desktop*
*SQL*
*DAX language*
*Power Query*
*Excel*
*DAX Studio (for optimizing the report)*
## About the Dataset
Understanding available data is crucial before performing analysis. Ensure a good understanding of the available data before jumping into the analysis.

**Dimension Table**
Contains static data like details of customers and products:

**1. dim_customer**: 27 distinct markets (e.g., India, USA, Spain), 75 distinct customers throughout the market, 2 types of platforms (Brick & Mortar - Physical/offline store, E-commerce - Online Store), and three channels (Retailer, Direct, Distributors).
**2. dim_market**: 27 distinct markets, 7 sub-zones, 4 regions (APAC, EU, NA, LATAM).
**3. dim_product**: Divisions (P & A, Peripherals, Accessories, PC, Notebook, Desktop, N & S, Networking, Storage), 14 different categories, and different variants available for the same product.

**Fact Table**
Contains data about transactions:

**1. fact_forecast_monthly**: Used to forecast customer needs in advance, aiming for higher customer satisfaction and reduced storage costs. The table is denormalized by the data engineering team for analytical work, with all dates of the month replaced by the start date of the month.
**2. fact_sales_monthly**: Similar to the fact_forecast_monthly table but with sold quantity instead of forecast value.

**Other Tables**
**1. freight_cost**: Details of travel and other costs for each market with the fiscal year.
**2. gross_price**: Details of gross prices with product code.
**3. manufacturing_cost**: Details of manufacturing costs with product code and year.
**4. pre_invoice_deductions**: Details of pre-invoice deductions percentage for each customer with year.
**5. post_invoice_deductions**: Post-invoice deductions and other deductions details.
## Data Modelling and Relationships
Data modeling is the process of structuring and organizing data to create relationships, and establish a framework for effective data analysis and reporting. It ensures data accuracy, facilitates complex calculations, and enhances data integration, providing a solid foundation for informed decision-making and business intelligence.
In this project, we followed the **Snowflake** data modeling method.
## Task
As a Data Analyst generate insights through reports built considering different sections such as

Home Page
Finance view
Sales view
Marketing view
Supply Chain
Executive View
Info
Support
such that stakeholders can unlock insights and enable data-driven decision-making.
## Report Overview
**Home Page**
The Home view serves as the central hub, presenting users with convenient access to various specific views through dedicated buttons. Users can seamlessly navigate to their desired sections by clicking on the respective buttons.
![Home Page](https://github.com/user-attachments/assets/4b6a9136-5bc2-4a18-a77f-864a1df2a2f5)

**Finance View**
Get comprehensive Profit and Loss (P&L) statements effortlessly, tailoring analyses for specific customers, products, or countries, and aggregating data over flexible time periods.

**Sales View**
Examine your product(s) performance by scrutinizing critical metrics such as Net Sales and Gross Margin.

**Marketing View**
Analyze the performance of the customer(s) over key metrics like Net Sales, Gross Margin and view the same in profitability / Growth matrix.

**Supply Chain View**
Evaluate Forecast Accuracy, Net Error, and risk profiles for various entities such as products, segments, categorie s, and customers. Gain a comprehensive understanding of forecasting precision and associated risks for informed decision-making.

**Executive View**
A high-level executive dashboard that consolidates key insights from all dimensions of the business. Provide a centralized view to executives, offering comprehensive and strategic overviews across various facets of the organization.

**Stakeholder Request** 
Capture and address specific business needs from various stakeholders, ensuring relevant insights are delivered across finance, sales, marketing, and supply chain views. Enable informed decision-making by fulfilling their key data requirements and metrics.

This Power BI project has been an invaluable learning experience, enhancing my skills in transforming raw data into actionable insights. I aim to apply these learnings to enable AtliQ Hardware to make data-driven decisions, ultimately driving operational efficiency and fostering improved business performance across the organization.

### Thank You!
