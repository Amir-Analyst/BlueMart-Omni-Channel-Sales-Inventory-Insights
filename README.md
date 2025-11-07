BlueMart Project

Company Overview:
BlueMart Retail LLC is a mid-sized UAE-based omnichannel retailer operating 12+ physical stores across major emirates (Dubai, Abu Dhabi, Sharjah) and a growing e-commerce presence via its website, mobile app, and marketplaces such as Amazon.ae and Noon. Established in 2018, BlueMart aims to integrate physical and digital sales channels, optimize inventory, and leverage advanced analytics to drive profitability and customer engagement.

Business Challenge:
BlueMart faces common omni-channel retail challenges: maintaining optimal stock levels across stores and warehouses, forecasting demand with seasonal spikes (Ramadan, Eid, Dubai Shopping Festival, Black Friday, National Day), maximizing gross margin while running promotions, and understanding customer purchase behavior across channels. Additionally, e-commerce growth has introduced complexities in order fulfillment, channel performance comparison, and customer segmentation.

Project Goal:
Build a KPI-driven analytics framework to:

Provide holistic visibility into sales, inventory, and promotions across channels.

Forecast SKU-level demand and optimize safety stock to reduce stockouts and overstock.

Identify high-value customers and preferred channels for targeted engagement.

Enable management to make data-driven decisions that improve revenue, gross margin, and operational efficiency.

Approach:

Generate a synthetic but realistic UAE dataset covering Jan 2018 – Sep 2025, including daily transactions, SKU details, store attributes, inventory movements, promotions, and customer behaviors.

Perform exploratory data analysis to uncover trends, seasonality, and channel performance.

Build ML-based forecasting models (XGBoost/LightGBM) to predict demand and optimize safety stock.

Develop a Streamlit dashboard prototype to visualize KPIs and insights for executive stakeholders.

Derive actionable insights for merchandising, marketing, and supply chain teams.

High-Level KPI Mapping
KPI	Description	Data Source / Calculation	Dashboard Placement
Total Revenue	Overall sales across all channels	Transaction table: qty × price	Executive summary + sales trends by channel
Gross Margin % (GM%)	Profitability measure	(Revenue – COGS) / Revenue × 100	Revenue vs. cost analysis by SKU, store, channel
Sales by Channel	Revenue contribution per channel	Transaction channel attribute	Channel performance comparison charts
Inventory Turnover	How efficiently stock is sold	COGS / Avg Inventory	Heatmap by SKU & store; highlight slow movers
Stockout Rate / Fill Rate	% of demand met without stockouts	Inventory table + transactions	Alerts / KPI cards for warehouse & stores
Average Basket Value (ABV)	Avg transaction value per customer	Revenue / #Transactions	Trend line & channel comparison
Sell-through %	% of stocked items sold	Units sold / Units received × 100	SKU-level dashboards for merchandisers
Forecast Accuracy (MAPE)	Model performance metric for demand prediction	Compare predicted vs. actual sales	Model evaluation & KPI card for planning team
Dashboard Structure Recommendations

Executive Overview: Total revenue, GM%, sales by channel, stockout alerts, ABV trends.

Channel Insights: E-commerce vs. store performance, marketplace contributions, click & collect analytics.

Inventory & Supply Chain: Turnover, sell-through, safety stock visualization, supplier lead times.

SKU & Category Performance: Top-selling vs. slow-moving items, seasonal spikes, promotion impact.

Forecast & Planning: ML-based demand forecasts with historical comparison, MAPE KPI, actionable replenishment suggestions.

Customer Insights (derived from analysis): Cohorts, loyalty segmentation, channel preference, and repeat purchase trends.
