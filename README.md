# **BlueMart Project Story (Executive Narrative)**

---

## **Company Overview**

**BlueMart Retail LLC** is a mid-sized UAE-based omnichannel retailer operating **12+ physical stores** across major emirates — **Dubai, Abu Dhabi, and Sharjah** — alongside a growing e-commerce presence through its **website, mobile app, and marketplaces (Amazon.ae, Noon)**.  
Established in **2018**, BlueMart’s mission is to integrate its physical and digital sales channels, optimize inventory performance, and leverage **advanced analytics** to enhance **profitability** and **customer engagement**.

---

## **Business Challenge**

BlueMart faces typical omni-channel retail complexities, including:

- Maintaining **optimal stock levels** across stores and central warehouses.  
- **Forecasting demand** during **seasonal peaks** (Ramadan, Eid, Dubai Shopping Festival, Black Friday, UAE National Day).  
- Balancing **gross margin** while executing **promotional campaigns**.  
- Understanding **customer purchase behavior** across channels.  
- Managing **e-commerce order fulfillment**, **channel-wise performance tracking**, and **customer segmentation** for loyalty optimization.  

These challenges create a need for a unified analytics framework to drive decision-making and operational efficiency.

---

## **Project Goal**

Build a **KPI-driven analytics framework** to:

1. Provide **holistic visibility** into sales, inventory, and promotions across all channels.  
2. **Forecast SKU-level demand** and optimize safety stock to reduce stockouts and overstock.  
3. Identify **high-value customers** and **preferred channels** for targeted marketing.  
4. Enable management to make **data-driven decisions** that improve revenue, gross margin, and efficiency.

---

## **Approach**

1. **Data Simulation:**  
   Generate a **synthetic yet realistic UAE retail dataset** covering **Jan 2018 – Sep 2025**, including:
   - Daily transactions  
   - SKU and store details  
   - Inventory movements  
   - Promotions  
   - Customer behaviors  

2. **Exploratory Data Analysis:**  
   Uncover patterns in **sales trends**, **seasonality**, and **channel performance**.

3. **Forecasting Models:**  
   Build **XGBoost** and **LightGBM** models to predict demand and optimize inventory planning.

4. **Dashboard Development:**  
   Create a **Streamlit dashboard prototype** to visualize executive KPIs and actionable insights.

5. **Insight Derivation:**  
   Generate recommendations for **merchandising**, **marketing**, and **supply chain** optimization.

---

## **High-Level KPI Mapping**

| **KPI** | **Description** | **Data Source / Calculation** | **Dashboard Placement** |
|----------|----------------|-------------------------------|--------------------------|
| **Total Revenue** | Overall sales across all channels | `Transaction table: qty × price` | Executive summary + sales trends by channel |
| **Gross Margin % (GM%)** | Profitability measure | `(Revenue – COGS) / Revenue × 100` | Revenue vs. cost analysis by SKU, store, channel |
| **Sales by Channel** | Revenue contribution per channel | Transaction channel attribute | Channel performance comparison charts |
| **Inventory Turnover** | Efficiency of stock movement | `COGS / Avg Inventory` | Heatmap by SKU & store; highlight slow movers |
| **Stockout Rate / Fill Rate** | % of demand met without stockouts | Inventory + transaction data | Alerts / KPI cards for warehouse & stores |
| **Average Basket Value (ABV)** | Avg transaction value per customer | `Revenue / #Transactions` | Trend line & channel comparison |
| **Sell-through %** | % of stocked items sold | `Units sold / Units received × 100` | SKU-level dashboards for merchandisers |
| **Forecast Accuracy (MAPE)** | Model accuracy for demand prediction | Compare predicted vs. actual sales | Model evaluation + KPI card for planning team |

---

## **Dashboard Structure Recommendations**

### **1. Executive Overview**
- Total Revenue, GM%, and sales by channel  
- Stockout / Fill rate alerts  
- Average Basket Value (ABV) trend visualization  

### **2. Channel Insights**
- E-commerce vs. Store performance  
- Marketplace (Amazon.ae, Noon) contribution  
- Click & Collect performance analytics  

### **3. Inventory & Supply Chain**
- Inventory turnover, sell-through, safety stock tracking  
- Supplier lead time visualization and efficiency metrics  

### **4. SKU & Category Performance**
- Top-selling vs. slow-moving SKUs  
- Seasonal demand spikes  
- Promotion-driven uplift and margin impact  

### **5. Forecast & Planning**
- ML-based demand forecasts with historical trends  
- Forecast Accuracy (MAPE) metric  
- Replenishment recommendations based on predictive insights  

### **6. Customer Insights (Derived from Analysis)**
- Customer cohorts and loyalty segmentation  
- Channel preference patterns  
- Repeat purchase and retention trends  

---

**Deliverable:**  
A unified **AI-augmented analytics system** showcasing BlueMart’s transformation from data-rich to **insight-driven**, enabling smarter, faster, and more profitable decisions across its retail ecosystem.
