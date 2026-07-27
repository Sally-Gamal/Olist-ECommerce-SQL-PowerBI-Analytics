# 🛒 Olist E-Commerce Analytics (SQL Server & Power BI Case Study)

## 1. 📊 Interactive Dashboard Overview
![Olist Dashboard 1](olist_dashboard1.jpg)
![Olist Dashboard 2](olist_dashboard2.jpg)
![Olist Dashboard 3](olist_dashboard3.jpg)

---

## 2. 📝 Executive Summary
This analytics project explores the **Olist E-Commerce Dataset** (Brazilian Market) containing **99k+ orders**. By leveraging **SQL Server for data extraction & business logic validation** and **Power BI for dynamic visualization**, the goal is to evaluate overall revenue performance, shipping efficiency, geographic market share, and customer satisfaction metrics.

### 📈 Key Performance Indicators (KPIs):
* **Total Revenue:** ~$13.59 Million
* **Total Customers:** 99,441
* **Average Review Score:** 4.0 / 5.0
* **Completed Orders:** 96,478 Delivered Orders
* **Geographic Coverage:** 27 Brazilian States

---

## 3. 🛢️ SQL Queries & Logic Validation (Code Documentation)
*Below are the validated T-SQL queries executed on SQL Server to aggregate KPIs, calculate delivery durations (`DATEDIFF`), analyze hourly sales trends (`DATEPART`), and extract state-level market share:*

![SQL Query 1](olist_queries1.sql)
![SQL Query 2](olist_queries2.sql)
![SQL Query 3](olist_queries3.sql)
![SQL Query 4](olist_queries4.sql)
![SQL Query 5](olist_queries5.sql)

---

## 4. 🔍 Deep-Dive Insights (Analytical Findings)

### A. Geographic Revenue & Market Share
* **Regional Dominance:** **São Paulo (SP)** is the undisputed market leader, accounting for **41,746+ customers** and over **$5.99 Million** in total payments.
* **Secondary Markets:** **Rio de Janeiro (RJ)** and **Minas Gerais (MG)** follow as the second and third largest revenue drivers (~$2.14M and ~$1.87M respectively).

### B. Shipping Performance & Fulfillment Speed
* **Fastest Delivery:** São Paulo (SP) boasts the fastest fulfillment time with an average delivery speed of **8 days**.
* **Regional Bottlenecks:** Northern states (e.g., AC, SE, PB) experience longer delivery times averaging **20 to 21 days**, highlighting potential logistics bottlenecks in distant regions.

### C. Category Performance & Sales Trends
* **Top Revenue Categories:** `cama_mesa_banho` (Bed/Bath), `beleza_saude` (Health/Beauty), and `relogios_presentes` (Watches/Gifts) drive the highest overall sales volume.
* **Hourly Shopping Patterns:** Peak ordering hours occur between **10:00 AM and 4:00 PM**, generating over **$1 Million in hourly revenue** during peak slots.

---

## 💡 5. Strategic Recommendations for Olist
1. **Logistics Optimization:** Establish regional fulfillment centers in North/Northeast states to cut down delivery times from 21 days to under 12 days.
2. **Targeted Promotions:** Schedule marketing push notifications during peak buying hours (**10 AM – 4 PM**) to maximize conversion rates.
3. **Inventory Allocation:** Prioritize stock replenishment for top revenue-generating categories (`beleza_saude` & `cama_mesa_banho`) in SP and RJ hubs.

---

## 📂 Repository Content
* `olist_dashboard*.jpg`: Dashboard visualizations and executive reporting screens.
* `olist_queries*.jpg`: Execution snapshots of T-SQL analytical scripts from SQL Server.
