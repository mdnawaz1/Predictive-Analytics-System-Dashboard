# Predictive Analytics System — Ledger Dashboard
## Project Objective
This repository contains a single, self-contained HTML dashboard designed to demonstrate a complete predictive analytics workflow. It takes a raw retail invoice ledger, walks through the process of data cleaning, visualization, model building, and insight generation, all within a single interactive page.
## DataSet Used
<a href = "https://github.com/mdnawaz1/Predictive-Analytics-System-Dashboard/blob/main/(4b)%20Predictive%20Analytics%20System.xlsx">DataSet</a>
## 📊 Key Performance Indicators (KPIs) at a Glance
The dashboard surfaces critical business metrics upfront, providing an immediate pulse on the trading window:

Total Revenue	£3,122.93
Total Invoices	14 orders
Total Units Sold	1,310 units
Average Order Value (AOV)	£223.07
Unique Customers	7 buyers
Unique SKUs	73 products
Average Basket Size	93.6 units
Best Model R²	0.98

## Dashboard Images
Images 1
<a href = "https://github.com/mdnawaz1/Predictive-Analytics-System-Dashboard/blob/main/Predictive%20Analytics%20System%201.png">Dashboard Images</a>
Images 2
<a href = "https://github.com/mdnawaz1/Predictive-Analytics-System-Dashboard/blob/main/Predictive%20Analytics%20System%202.png">Dashboard Images</a>
Images 3
<a href = "https://github.com/mdnawaz1/Predictive-Analytics-System-Dashboard/blob/main/Predictive%20Analytics%20System%203.png">Dashboard Images</a>
Images 4
<a href = "https://github.com/mdnawaz1/Predictive-Analytics-System-Dashboard/blob/main/Predictive%20Analytics%20System%204.png">Dashboard Images</a>
Images 5 
<a href = "https://github.com/mdnawaz1/Predictive-Analytics-System-Dashboard/blob/main/Predictive%20Analytics%20System%205.png">Dashbaord Images</a>
Images 6 
<a href= "https://github.com/mdnawaz1/Predictive-Analytics-System-Dashboard/blob/main/Predictive%20Analytics%20System%206.png">Dashboard Images</a>
## 🚀 Key Features
📊 End-to-End Analytics Pipeline: The dashboard showcases a full data science pipeline, from ingesting raw, messy data to generating actionable business insights.

📈 Real-Time KPI Monitoring: Critical business metrics are displayed prominently, allowing stakeholders to instantly assess revenue, volume, customer activity, and model performance.
🧹 Data Cleaning & Processing: A regex-based parser is demonstrated to split and clean two composite columns (StockCode+Description, CustomerID+Country), recovering 100% of the data without any row loss.

📊 Interactive Visualizations: Six key charts provide a comprehensive view of the data, including distribution, correlation, and market comparisons, built using Chart.js.

🤖 Three Predictive Models: Three distinct models are trained and explained, each answering a different operational question:
Order Quantity Regression: Predicts line-item quantity (R²: 0.305).
High-Value Order Classifier: Flags high-value orders for priority handling (68% Accuracy).
Revenue Run-Rate Forecast: Projects future revenue based on current trends (R²: 0.98).

💡 Honest & Self-Critiquing Insights: Every model card includes a transparent, honest assessment of its performance, acknowledging limitations like small sample sizes or mathematically inflated R² values.

🖋️ Unique Visual Style: The dashboard borrows its design language from the subject matter—invoice paper, ledger stamps, and ticker tape—for a more engaging and contextually relevant user experience.

🌓 Light/Dark Theme: A toggle is included for user preference, with both themes maintaining the dashboard's unique visual identity.

📦 Zero Dependencies (Beyond CDN): The entire application is a single HTML file that can be opened directly in any browser, requiring no build steps, server, or external data files.
