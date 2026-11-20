
# Hi there, I'm Krishna! 👋
## Data Analyst | Business Analyst
### 💡Transforming Raw Data into Actionable Business Insights
I am a detail-oriented Data Analyst focused on bridge-building between complex data sets and executive decision-making. I specialize in designing interactive dashboards, building efficient ETL data pipelines, and executing deep statistical analyses to uncover growth opportunities and operational efficiencies.

---
### 🛠️ Skills & Technologies

* **Data Analysis & Spreadsheets:** Microsoft Excel (Data Cleaning, Advanced Formulas, Pivot Tables) 
* **Business Intelligence & Visualization:** Power BI (Data Modeling & Interactive Dashboards) | Tableau (Visual Analytics & Storytelling)
* **Database Management:** SQL (CTEs, Window Functions & Schema Design) | PostgreSQL (pgAdmin) | MySQL
* **Programming & Data Engineering:** Python (Pandas, SQLAlchemy, REST API Integration & Automated Pipelines) | R (Statistical Analysis) | C++ (Core Programming)
* **Development Environments:** VS Code / Visual Studio | Jupyter Notebook | Anaconda Navigator

---
### 📁 Projects
#### 📈 Finnhub Live Market Tracker
A real-time financial dashboard powered by a continuous **10-second data ingestion loop** that turns raw Finnhub API feeds into live market insights.

* **10-Second Ingestion Engine:** Built a resilient **Python** loop **(Finnhub, Pandas, SQLAlchemy)** that pulls live quotes, computes net/percentage changes, and handles network blips every 10 seconds without breaking the stream.
* **Zero-Lag PostgreSQL Design:** Split storage into `live_stock_history` (appending 7 new rows every 10 seconds for trend lines) and `live_stock_history_snapshot` (replacing a 7-row table every 10 seconds for instant KPI loading).
* **Live Power BI Command Center:** Visualized real-time KPI cards, intraday area charts, and a color-coded watchlist with one-click company filtering.
* 🔗 [**View Project Repository**](https://github.com/krishna043-prog/Finnhub-Live-Market-Tracker) | [**View Power BI Dashboard**](https://github.com/krishna043-prog/Finnhub-Live-Market-Tracker/blob/main/finnhub_live_dashboad/finnhub_live_dashboard_screenshot.png) | [**Open Project Report**](https://github.com/krishna043-prog/Finnhub-Live-Market-Tracker/blob/main/Finnhub_live_market_tracker_report.pdf)


#### 🛍️ Customer Shopping Behavior Analysis
* **The Business Problem:** Fragmented consumer transaction records made it difficult to analyze buyer demographic trends, track promotion code conversion rates, or evaluate shipping tier performance.
* **The Approach:** Engineered an end-to-end data pipeline modeling a realistic business intelligence lifecycle. Cleansed and standardized 3,900 rows and 18 columns using **Python (Pandas)** in **Jupyter Notebook** by handling missing values and automating schema string modifications. Migrated the structured tables into **SQL (MySQL/pgAdmin)** to write advanced aggregations (CTEs, subqueries, and window functions), and deployed an executive dashboard in **Power BI** to map key KPIs.
* **The Impact:** Replicated a full corporate BI lifecycle that streamlined raw data inputs into an interactive dashboard, allowing stakeholders to instantly segment visual charts by subscription level, gender, and shipping type with single-click functionality.
* 🔗 [**View Project Repository**](https://github.com/krishna043-prog/Customer-Shopping-Behavior-Analysis) | [**View Power BI Dashboard**](https://github.com/krishna043-prog/Customer-Shopping-Behavior-Analysis/blob/main/customer_shopping_behavior_dashboard.pdf) | [**Open Project Report**](https://github.com/krishna043-prog/Customer-Shopping-Behavior-Analysis/blob/main/customer_shopping_behavior_report.pdf)

#### 🚚 Supply Chain Data Analysis
* **The Business Problem:** Raw global logistics logs made it difficult to pinpoint which shipping regions were missing delivery SLAs or which product categories were causing recurring fulfillment delays.
* **The Approach:** Built a structured ELT pipeline in **PostgreSQL** by importing 50+ raw attributes from the DataCo Supply Chain dataset into an all-text staging table `staging_dataco` and casting core fields (::INT, ::NUMERIC) into a typed production table `supply_chain_raw`. Engineered two reusable **SQL views** —`view_regional_sla` (tracking late-delivery percentages and average shipping days by region) and `view_product_friction` (filtering categories with >100 orders to rank average overdue days)—before connecting them to an interactive **Tableau** dashboard.
* **The Impact:** Streamlined raw logistics data into a clean, reusable SQL reporting layer, enabling stakeholders to instantly identify high-delay regions and overdue product categories without scanning raw transaction tables.
* 🔗 [**View Project Repository**](https://github.com/krishna043-prog/Supply-Chain-SLA-Analysis) | [**View Tableau Dashboard**](https://github.com/krishna043-prog/Supply-Chain-SLA-Analysis/blob/main/supply_chain_dashboard_screenshot.png)



---
### 📜 Certifications
|   | Certificate Title | Issuing Organization | Verification Link |
|---|---|---|---|
| <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/2acd0cc0-0d7d-458d-b686-fb7677544b0e" /> | **Microsoft Power BI Data Analyst** | Microsoft | [Verify Credential](https://www.coursera.org/account/accomplishments/specialization/QMQVRAF7H0PX) |
| <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/2e5b392e-f528-44ad-96bb-2a5eebfb3019" /> | **SQL (Basic)** | HackerRank | [Verify Credential](https://www.hackerrank.com/certificates/9f1e971468ea) |
| <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/5b592151-2b52-4073-a5dd-0601bcbc8542" /> | **Python (Basic)** | HackerRank | [Verify Credential](https://www.hackerrank.com/certificates/87441f916a81) |
| <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/02d1a790-1259-409f-a8b7-e57ea6b9f94d" /> | **Python Developer Certificate** | freeCodeCamp | [Verify Credential](https://www.freecodecamp.org/certification/fcc-da44991e-840f-4a49-81f7-1f412507fd18/python-v9) |
---
## 🤳 Connect with me:
[**<img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/7f67513f-9c9e-4c15-80b0-ed3ff6f38fc2" align="absmiddle" />**](https://www.linkedin.com/in/krishna-savaliya-535059115/)   





