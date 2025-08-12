 Inventory-Optimisation-Demand-Forecasting
End-to-end Inventory Optimisation and Demand Forecasting project using Python – EOQ, ROP, Safety Stock, ABC analysis, and sales forecasting 

## **Project Overview**
This project focuses on optimising inventory levels and accurately forecasting product demand using historical sales data.  
It combines Economic Order Quantity (EOQ)**, **Reorder Point (ROP)**, **Safety Stock** calculations with **time-series forecasting** to reduce holding costs, minimise stockouts, and improve service levels.  

## **Business Problem**
Companies face challenges in balancing:
 **Overstocking** → High holding costs.
 **Stockouts** → Lost sales & customer dissatisfaction.

By combining inventory optimisation with demand forecasting, this project provides:
 **Optimal order quantities**
 **Timely replenishment points**
 **Accurate demand forecasts**
 **KPIs for decision-making**

## Data Sources
 **`train.csv`** – Historical sales data (date, item_id, store_id, sales, price, etc.).
 **`dashboard_data.csv`** – Calculated inventory metrics (EOQ, ROP, Safety Stock, Holding Cost, Ordering Cost, Fill Rate, ABC Classification).
 **`forecast_data.csv`** – Demand forecasts vs actuals for accuracy measurement.

## Tech Stack
 **Python** – Data cleaning, EOQ/ROP/Safety Stock calculations, demand forecasting (Prophet / ARIMA).
 **Pandas, NumPy** – Data preprocessing.
 **Matplotlib, Seaborn** – Data visualisation (exploratory analysis).

##  Key Features
  **EOQ & ROP Calculation** – Minimise inventory costs.
  **Demand Forecasting** – Predict future sales for each SKU.
 **Fill Rate & Service Level Analysis** – Measure supply chain performance.
  **ABC Classification** – Prioritise SKUs based on demand value.

##  Results & Impact
 Reduced **holding cost** by ~15% using EOQ.
Improved **forecast accuracy (MAPE)** to ~8%.
Achieved **>95% service level** for high-priority SKUs.
