# SecureTrans - A Power BI Dashboard for Banking Transaction Fraud Analysis
## 🎯 Objective

To design and develop an interactive Power BI dashboard that analyzes banking transaction data, identifies fraudulent patterns, and visualizes key metrics to support data-driven decision-making in financial operations.

---

## 📌 Dashboard Features

### 🔹 Page 1: Transaction Overview Dashboard

**🎯 Purpose:** Summarize key business metrics and transaction behavior.

- ✅ KPI Cards: Total Transactions, Total Amount, Fraud Count, Avg Latency  
- 📊 Donut Chart: Transaction Type Distribution  
- 📊 Bar Chart: Transaction Status (Success vs Failed)  
- 📈 Line Chart: Daily Transaction Trend  
- 📊 Stacked Column Chart: Device Used (Mobile vs Desktop)  
- 🌍 Map: Transactions by Geolocation  
- 🔘 Slicers: Transaction Type, Date  

![Dashboard Screenshot](https://github.com/RaginiAG/SecureTrans-A-Power-BI-Dashboard-for-Banking-Transaction-Fraud-Analysis/blob/main/Overview%20Dashboard.png)

### 🔹 Page 2: Fraud Analytics

**🎯 Purpose:** Deep dive into fraud trends and behavioral indicators.

- 📊 Bar Charts: Fraud by Transaction Type and Device Used  
- 🌍 Map: Fraud Locations (Fraud Flag = TRUE)  
- 📈 Line Chart: Fraud Trend Over Time  
- 🔥 Heatmap: Day of Week vs Hour vs Fraud Count  
- 📊 Column Chart: Fraud % by Network Slice ID  
- 📊 Fraud Count by Latency/Bandwidth Range  
- 🔘 Slicers: Fraud Flag, Device, Date  

![Dashboard Screenshot](https://github.com/RaginiAG/SecureTrans-A-Power-BI-Dashboard-for-Banking-Transaction-Fraud-Analysis/blob/main/Fraud%20Analytics.png)

### 🔹 Page 3: Technical & Risk Insights

**🎯 Purpose:** Explore technical network metrics and identify suspicious behavior.

- ⚙️ Scatter Plot: Bandwidth vs Latency  
- 📊 Bar Chart: Average Latency by Device  
- 📋 Table: High-Amount & High-Latency Transactions  
- 🚨 Risk Score Visual: Score 0–3 based on latency, amount, and device  
- 🧾 Table: Suspicious Transactions (not flagged as fraud)  
- 🔘 Slicers: Risk Score, Bandwidth, Device Used  

![Dashboard Screenshot](https://github.com/RaginiAG/SecureTrans-A-Power-BI-Dashboard-for-Banking-Transaction-Fraud-Analysis/blob/main/Technical%20%26%20Risk%20Insights.png)

---

## 📂 Dataset Source

**Kaggle Dataset (Transaction Data for Banking Operations)**:  
[Dataset](https://www.kaggle.com/datasets/ziya07/transaction-data-for-banking-operations)

---
## 🧠 Insights Gained


- Gained practical experience in designing multi-page dashboards tailored for different analytical needs.  
- Improved data cleaning and transformation skills using Power Query.  
- Created custom DAX logic for fraud detection, risk scoring, and latency analysis.  
- Used time-based and geospatial visuals to highlight anomalies.  
- Applied interactive slicers for better user control and storytelling.

---

## 🔧 Tools Used

- Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions) 
- Excel/CSV for preprocessing
- GitHub for version control and documentation

---

## ✅ Conclusion

SecureTrans successfully demonstrates how advanced data visualization and analytics in Power BI can be leveraged to uncover fraudulent banking transactions, monitor operational performance, and assess technical risk. Through a structured 3-page dashboard layout, it provides actionable insights for stakeholders by combining business metrics, fraud behavior patterns, and technical indicators like latency and network slice performance.
By combining DAX-based risk scoring, geospatial mapping, and interactive drill-downs, this project delivers a practical solution for fraud detection and informed decision-making. It demonstrates the real-world impact of data storytelling, transformation, and visualization in financial analytics.

---

  ## ⭐️ If you found this project useful, consider giving it a star on GitHub!
