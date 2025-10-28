# Toy Store KPI Report

##  Overview
In this project, I worked as a Data Analyst for a toy store chain with multiple locations across Mexico. The goal was to build an interactive Power BI dashboard that enables leadership to monitor key performance indicators (KPIs) which includes revenue, profit, and order volume. I also wanted to identify any trends based on factors like store location, product category, and seasonality.


---

##  Objectives
1. **Data Connection & Profiling:**  
   Imported multiple CSV files into Power BI and explored the datasets using the table view to understand structure, quality, and completeness.  

2. **Data Modeling:**  
   Identified relationships between fact and dimension tables to create a clean relational model for analysis.  

3. **Dashboard Development:**  
   Designed and built an interactive dashboard highlighting KPIs such as Total Orders, Total Revenue, and Total Profit.
---

##  Dataset Description 

**Description:**  
The dataset consists of **4 tables**: `calender`, `products`, `sales`, and `stores`.

| Table | Key Fields | Description |
|--------|-------------|-------------|
| **calender** | Date, Start of Month, Start of Week | Date dimension for time-based calculations and trends. |
| **products** | Product_ID, Product_Category, Product_Cost, Product_Price | Product details including categories and pricing. |
| **sales** | Sale_ID, Product_ID, Store_ID, Cost, Price, Date, Units, Total Orders, Total Profit, Total Revnue | Main fact table containing transactional sales data. |
| **stores** | Store Location, Store_ID | Store-level information used for geographic and location-based analysis. |

###  Data Preparation
- Defined **DAX measures** for key metrics: Total Orders, Total Revenue, and Total Profit.  
- Created **calendar-based fields** (Start of Month, Start of Week) to support time intelligence in Power BI visuals.  
- Cleaned and transformed data to ensure relationships were properly established between all tables.




---

##  Tools & Technologies
| Category | Tools / Platforms |
|-----------|------------------|
| **Languages** | DAX |
| **Visualization & Analysis** | Power BI |
| **Data Source** | CSV Files |

---

## Insights & Recommendations

### Key Insights

- **Revenue Trends:** The company's revenue showcases strong seasonality with revenue peaking around late 2022 and early 2023 which is most likely a result of the holiday period.
- **Category Performance:**  
  - **Toys** and **Arts & Crafts** lead sales volume, indicating strong demand for family and creative entertainment products.  
  - **Electronics** contribute the least to total orders, suggesting potential underperformance or higher pricing sensitivity.
- **Profitability Pattern:** While revenue fluctuates monthly, profits tend to align closely with revenue peaks, indicating stable cost margins.
- **Location Insights:**  
  - **Downtown** stores generate the highest revenue, followed by Commercial, Residential, and finally Airport locations.  
  - Downtown’s dominance suggests strong foot traffic and broader customer reach, while Airport locations most likely suffer due to a low amount of shopper volume  

  ### Recommendations
- **Inventory Optimization:** Increase inventory for Toys and Arts & Crafts before high-demand periods to capitalize on seasonal peaks.  
- **Promotional Focus:** Launch targeted discounts or bundles for Electronics and Sports & Outdoors to stimulate sales in slower-moving categories.  
- **Seasonal Strategy:** Prepare marketing campaigns in Q4 and Q1 to leverage consistent holiday and new-year sales growth.

---

## Dashboard Preview

<img width="1327" height="734" alt="Toy Store Dashboard" src="https://github.com/user-attachments/assets/130bf18c-1bd5-4aa0-b546-9d9415d696a2" />

---

## Conclusion
This Power BI dashboard successfully delivers a clear view of the toy store chain’s key metrics, highlighting trends across time, product categories, and locations. It also empowers leadership to make decisions regarding inventory management, marketing focus, and regional strategy.

