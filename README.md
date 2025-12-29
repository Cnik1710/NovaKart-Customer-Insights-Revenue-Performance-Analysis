# FlexFit-Health--Activity-Wellness-Analysis
 ---
## 🎯 Objective
Analyze and interpret **Novakart’s customers, products & purchases data** to uncover actionable insights that drive **user engagement, product optimization, targeted marketing, inventory planning, and regional focus**.
### **Project Purpose:**
  * To analyze customer behavior, revenue, and profit trends for **NovaKart**, an e-commerce retail dataset.
  * To identify **high-performing customer segments, geographies, products and time periods**.
  * To convert raw transactional data into **actionable business insights**.
### **Key KPIs:**
  * **Total Customers:** 997
  * **Total Revenue:** 2.96M
  * **Total Profit:** 3.29M
  * **Average Profit Margin (%):** 80.42
### **Deliverables:**
  * Interactive **Power BI dashboard**
  * Exploratory & analytical **Python (Jupyter) notebook**
  * Insight-driven **business recommendations**
---

## 📘 Project Overview 
### **Context Highlights:**
  * The analysis helps NovaKart’s **marketing, R&D, and product teams** understand:
    * NovaKart operates across multiple **states and cities**
    * Customers purchase products from different **companies and categories**
    * Dataset captures **demographics, geography, revenue, profit, and time-based attributes**
    * Goal was to replicate **Power BI insights using Python** for analytical consistency
 ---
 
## 🗂️ Data Overview & Schema     
### **Data Source:**
  * **Source:** Simulated retail transactional dataset for customer, product & revenue analytics
  * **Data Type:** Structured transactional and customer-level sales data
  * **Time Period:** Multi-month transactional snapshot (aggregated for trend analysis)
### **Data Structure & Metrics:**
  * **Key Index Types:** Customer, Product & Purchase level records
  * **Total Rows:** Customers - ~1000
  * **Categories:** 
    * **Customer Details:** customer_id, full_name, gender, city, state
    * **Product Details:** product_id, product, company, product_qty
    * **Time Attributes:** purchase_date, month, day
    * **Financial Metrics:** revenue, profit, profit_margin
  * **Calculated Metrics:**
    * Revenue & profit contribution
    * Profit margin (%)
    * Customer & city-level aggregation KPIs
    * Time-based performance indicators (monthly & weekday trends)
 ---

## 💻 Tech Stack    
### **Tools:**
  * **Excel**
      * Data storage & preprocessing
  * **Python**
      * Pandas, NumPy, Matplotlib, Seaborn
  * **Jupyter Notebook**
      * Data cleaning, EDA & visual analysis      
  * **PowerQuery** 
      * ETL transformations
  * **PowerBI**
      * Visualization, DAX measures & dashboard design
      * DAX – Calculated measures and time intelligence
   * **PowerPoint**
      * Presentation and final dashboard snapshots
---
        
## 📈 Methodology & Analysis  
### **Prepare, Process & Analytical Approach:**
  * **Data Preparation & Cleaning:**
    * Removed invalid and "N/A" category values
    * Standardized categorical fields (Gender, City, State, Month)
    * Verified data consistency between Python & Power BI outputs
  * **Data Modeling & Integration:**
    * Combined customer, product, and transaction tables into a unified dataset
    * Established relationships for customer, geography, and time dimensions
  * **Feature Engineering:**
    * Created derived columns for month & weekday analysis
    * Computed profit margins and revenue contribution metrics
    * Aggregated KPIs at customer, city, state, and product levels
  * **Visualization Design:**
    * Built two interactive dashboards:
      * Customer & Location Insights
      * Product & Company Insights
    * Integrated interactive slicers for dynamic segmentation
    * Ensured consistent color schemes & labeling across visuals
  * **Validation & Formatting:**
    * Cross-validated Python visuals with Power BI outputs
    * Ensured sorting, ordering (months, cities), and KPI consistency
---
 
## ❓ Problem Statement     
Retail businesses generate large volumes of transactional data across customers, products, locations, and time, yet actionable insights are often difficult to extract without structured analysis.

This project analyzes customer-level sales data to understand purchasing behavior, geographic performance, and profitability drivers, enabling stakeholders to identify high-value customers, top-performing regions, and opportunities to improve revenue and profit margins.

### Key Questions:
  * Which customer segments generate the highest revenue and profit?
  * Which states and cities contribute most to business performance?
  * How does gender impact revenue and profit trends?
  * What are the top-performing products and companies?
  * Which months and weekdays drive maximum sales?
  * Where are profit margins the strongest geographically?
---

## 💡 Key Insights      
### **Top Findings:**
  * Male customers slightly outperform females in total revenue & profit.
  * Texas and California are **top revenue-generating states**.
  * Washington and El Paso lead in **customer concentration**.
  * A small group of customers contributes disproportionately to revenue.
  * Certain products and companies dominate overall sales.
  * Revenue peaks during specific months, showing **seasonal trends**.

### **Supporting Metrics:**
  * **Total Customers:** ~1000
  * **Total Revenue:** ~3.29M
  * **Total Profit:** ~2.96M
  * **Average Profit Margin:** ~80%
---
 
## 📍 Conclusion
### **Summary:** 
  * NovaKart’s performance is driven by **specific customer segments, cities, and products**.
  
  * Geographic and demographic analysis reveals **clear revenue concentration**.
  
  * Python and Power BI results are **aligned and consistent**.
  
  * Insights can guide **targeted marketing, inventory planning, and regional focus**.
---
 
## 🖥️ Dashboard Overview
### Engagement Overview
![image_alt](https://github.com/Cnik1710/NovaKart-Customer-Insights-Revenue-Performance-Analysis/blob/0fdb0d29c71a06316ba4fb7601985e544fc41316/07.%20NovaKart%20%E2%80%93%20Customer%20Insights%20%26%20Revenue%20Performance%20Analysis%20(1)%20Dashboard.png)

### Activity Performance
![image_alt](https://github.com/Cnik1710/NovaKart-Customer-Insights-Revenue-Performance-Analysis/blob/0fdb0d29c71a06316ba4fb7601985e544fc41316/08.%20NovaKart%20%E2%80%93%20Customer%20Insights%20%26%20Revenue%20Performance%20Analysis%20(2)%20Dashboard.png)

---
 
## ✅ Business Impact & Use Cases   
  * **Helps management identify high-value customers**. Enables leadership to recognize customers contributing the highest revenue and profit, supporting targeted retention, personalized offers, and loyalty initiatives.

  * **Enables region-wise strategy optimization**. Provides clear visibility into state- and city-level performance, helping decision-makers prioritize high-performing regions and improve strategies in underperforming locations.

  * **Supports product & vendor performance evaluation**. Assists in identifying top-selling and most profitable products and companies, enabling informed decisions around inventory planning, vendor partnerships, and portfolio optimization.

  * **Assists in seasonal demand forecasting**. Reveals month-wise and weekday-wise sales patterns, helping businesses anticipate demand fluctuations, plan promotions, and allocate resources effectively.

  * **Can be extended for pricing, discount & loyalty analysis**. The analytical framework can be scaled to evaluate pricing strategies, discount effectiveness, and customer loyalty programs for future business growth.
 ---
 
 ## 🙏 Acknowledgements & Contact 
 ### Project Analyst: Anik Chakraborty	
   📧 Email: anikc1710@gmail.com  
 ### Special Thanks To: 
 * Coding Ninjas – for project framework and guidance



