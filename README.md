## Dashboard
![Walmart_MainDashboard](https://github.com/user-attachments/assets/7d01d1a0-e79e-46af-b733-ce3fd6ef7b24)
## Tooltips Under Sales by Category and Promotion Type
![Sales by Category and Promotion Type (Tooltips)](https://github.com/user-attachments/assets/6b8438ef-099f-4d8a-836f-8418c80ba515)
## Dril Through for Detail Insight Product or Location
![Drill ThroughPage_ProductName or City](https://github.com/user-attachments/assets/25278adb-431c-41d3-9321-f712e8daec58)
# Walmart Inventory Optimization Project

## 1. Project Overview

**Objective**: Walmart aims to enhance inventory management by implementing real-time demand forecasting, minimizing stockouts, and optimizing inventory levels across stores. This data-driven approach focuses on customer demand forecasting, external factors like weather, and promotional impact.

## Problem Definition

Walmart needs a data-driven inventory optimization solution that minimizes both stockouts and overstocking by forecasting demand based on past sales data. The goal is to develop a scalable approach that adjusts inventory levels dynamically using real-time insights from the analysis.

---

## Key Questions for Stakeholders

### Inventory Managers:
- **How can we improve inventory accuracy and ensure that stock levels match demand?**
- **What factors are contributing to stockouts, and how can we address them?**

### Store Managers:
- **How can we allocate inventory more efficiently across stores based on local demand patterns?**
- **How do promotions and weather influence sales at different store locations?**

### Marketing and Promotions Team:
- **What is the return on investment (ROI) for promotions, and how do they affect demand?**

---

## Stakeholder Involvement

### Internal Stakeholders:
- **Inventory Managers**: Will use the demand forecasting insights to ensure optimal stock levels across stores.
- **Store Managers**: Responsible for managing in-store inventory based on demand.
- **Marketing Team**: Understands how promotions impact sales and tailors campaigns accordingly.

### External Stakeholders:
- **Customers**: Their purchasing behavior directly influences demand forecasts.
- **Suppliers**: Will receive more accurate forecasts to ensure timely and sufficient product delivery.

---

## Metric Development

### Stockout Rate
- **Definition**: Number of stockouts as a percentage of total sales.
  
### Forecast Accuracy
- **Definition**: Difference between forecasted demand and actual demand.

### Sales Uplift from Promotions
- **Definition**: Percentage increase in sales during promotions.

### Weather Impact on Sales
- **Definition**: Sales variance in different weather conditions.

### Customer Loyalty and Purchasing Patterns
- **Definition**: Impact of loyalty tier on purchasing behavior.

---

**Data Sources**: The dataset includes:
- **Sales Transactions**: Transaction-level data capturing product, location, and date information.
- **Customer Data**: Information on customer behavior and loyalty.
- **Promotions**: Types and impacts of promotional activities.
- **Weather Conditions**: Weather data correlated with transaction dates.
- **Inventory Indicators**: Details on stockouts and forecasted demand.

**Methodology**: The project follows an Agile methodology, structured into four sprints:
1. **Sprint 1**: Data Collection and Cleaning
2. **Sprint 2**: Exploratory Data Analysis and Initial Forecast
3. **Sprint 3**: Refining Insights and Forecasts
4. **Sprint 4**: Presentation of Insights and Recommendations

---

## 2. Data Preparation and Key Measures

### Data Cleaning
- **Steps Taken**: Ensured data quality by handling missing values, standardizing date formats, and ensuring consistent data types across columns.

### Measures and Calculations
### Here's an explanation for each measure and DAX calculation in the context of Walmart Inventory Optimization project.**[https://drive.google.com/file/d/1HJm3IsfkLvNiHFRL_C4_I8oqZGksaErF/view?usp=sharing]**

#### Repeat Customer Identification (`Is Repeat Customer`)
- **Purpose**: Track customer loyalty by identifying repeat customers.
- **Impact on Walmart**: Allows Walmart to personalize offers, improve retention, and optimize customer loyalty resources.

#### Average Order Value (`AverageOrderValue`)
- **Purpose**: Measures revenue per transaction for pricing strategy and promotional impact analysis.
- **Impact**: Higher average order values indicate effective promotions or high-value items, guiding Walmart’s pricing and upselling strategies.

#### Stockout Rate by Store
- **Purpose**: Tracks frequency of stockouts per store, crucial for inventory planning.
- **Impact**: Identifies high stockout areas, enabling Walmart to adjust stock levels dynamically and reduce lost sales.

#### Promotion Sales Difference
- **Purpose**: Quantifies the revenue impact of promotions by comparing sales with and without them.
- **Impact**: Helps Walmart evaluate promotional effectiveness, supporting optimization in future campaigns.

#### Revenue Before and From Promotions
- **Purpose**: Splits revenue data to assess the financial impact of promotional activities.
- **Impact**: Informs Walmart’s return on investment (ROI) for various promotions, helping the Marketing and Promotions team optimize strategy.

#### Forecast Accuracy
- **Purpose**: Measures alignment between forecasted and actual demand, refining demand predictions.
- **Impact**: Improves Walmart’s ability to predict demand accurately, reducing the risk of stockouts or overstocking.

#### Holiday and Non-Holiday Sales
- **Purpose**: Separates sales by holiday and non-holiday periods for peak demand analysis.
- **Impact**: Optimizes stock levels and promotional efforts during holidays to prevent stockouts and maximize sales.

---

## 3. Visualizations and Their Purpose

### Total Revenue and Sales Volume Visualization
- **Reason**: Provides a top-level overview of Walmart’s financial performance and demand.
- **Impact**: Assists management in understanding revenue trends over time for budgeting and forecasting.

### Sales by Category and Promotion Type
- **Reason**: Breaks down sales by product category and promotion type, highlighting high-impact areas.
- **Impact**: Guides Walmart in identifying effective promotions and high-performing categories for future decisions.

### Stockout Rate by State and Product
- **Reason**: Tracks stockouts across locations and product types to identify frequent shortages.
- **Impact**: Supports regional inventory planning and product-specific stocking strategies.

### Sales by Weather Conditions
- **Reason**: Displays sales variations by weather, linking external conditions to purchasing behavior.
- **Impact**: Enables Walmart to forecast demand based on weather, optimizing inventory for external conditions.

### Sales and Count of Repeat Customers by Promotion Type
- **Reason**: Analyzes promotional influence on both sales and customer loyalty.
- **Impact**: Helps assess promotions that encourage repeat purchases, guiding loyalty investments.

### Peak Selling Time Visualization
- **Reason**: Identifies hours with the highest transaction volumes, useful for operational planning.
- **Impact**: Walmart can adjust staffing and stock replenishment during peak hours to boost customer satisfaction.

### Sales by Customer Gender and Age Group
- **Reason**: Segments sales data by demographics for targeted marketing.
- **Impact**: Informs Walmart on demographic preferences, enabling optimized marketing and stock strategies.

### Promotion Percentage Visualization
- **Reason**: Highlights the proportion of promotional transactions, helping gauge promotional reach.
- **Impact**: Allows Walmart to refine promotional strategies based on customer engagement.

### Sales Forecast Accuracy Over Time
- **Reason**: Plots forecast accuracy trends to assess prediction effectiveness.
- **Impact**: Refines Walmart’s forecasting model, leading to better inventory management.

### Sales by Payment Method
- **Reason**: This visualization breaks down sales by payment methods (e.g., credit card, debit card, cash, digital wallet), showing customer preferences for each method.
- **Impact**: Helps Walmart understand customer payment preferences, allowing for improved payment options and policies to enhance the customer experience. For instance, if digital wallets are highly used, Walmart might invest in promotions targeting mobile payments or introduce new payment options for convenience.

### Holiday & Non-Holiday Sales
- **Reason**: Separates total sales for holiday and non-holiday periods to capture seasonal demand patterns and analyze spikes during holidays.
- **Impact**: Enables Walmart to prepare for increased holiday demand, preventing stockouts and optimizing promotional activities. By identifying holiday-driven sales growth, Walmart can strategize inventory management and staffing to maximize sales during these periods.

### Top Performing Stores
- **Reason**: Identifies the stores generating the highest sales volume, providing insights into the locations with the strongest performance.
- **Impact**: Allows Walmart to understand the factors contributing to each store’s success and replicate strategies across lower-performing locations. By focusing on top-performing stores, Walmart can drive regional marketing campaigns and invest in high-demand inventory to further enhance revenue.

### Table Visual of Product Name, Total Sales, Revenue Before Promotion, Revenue From Promotion, Promotion Sales Difference
- **Reason**: Displays a detailed breakdown of sales metrics by product, including:
  - **Total Sales**: Overall revenue generated per product.
  - **Revenue Before Promotion**: Revenue without any applied promotions.
  - **Revenue From Promotion**: Revenue generated with applied promotions.
  - **Promotion Sales Difference**: Difference in revenue due to promotions, helping to evaluate promotion effectiveness per product.
- **Impact**: This table provides a comprehensive view of each product's sales performance, allowing Walmart to assess the impact of promotions. Understanding which products benefit most from promotions helps Walmart optimize promotional investments, prioritize inventory, and maximize sales revenue across product lines.


---

## 4. Conclusion and Recommendations

### Overall Impact on Walmart
These measures and visuals provide Walmart with actionable insights, including inventory optimization, demand forecasting improvements, and enhanced customer engagement.

### Recommendations
1. **Implement High-ROI Promotions**: Target high-demand categories for optimized promotional investment.
2. **Location-Specific Inventory Allocation**: Dynamically allocate inventory based on stockout data, peak selling times, and demand forecasts.
3. **Incorporate Weather-Based Demand Insights**: Adjust inventory levels to meet seasonal and weather-related demand patterns.
4. **Enhance Loyalty Programs for Repeat Customers**: Use insights from demographic and loyalty data to tailor promotions for key customer segments.
5. **Optimize Staffing and Stock for Peak Hours**: Schedule staffing and stock replenishment to align with peak selling hours for enhanced customer service.
