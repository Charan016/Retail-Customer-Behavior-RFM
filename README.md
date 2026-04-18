# 🛒 Retail Customer Behavior & RFM Analysis  

A complete retail analytics project built to understand customer purchasing behavior, segment customers using RFM analysis, discover product associations, study retention patterns, and estimate Customer Lifetime Value (CLV). The project uses Python, SQL, Pandas, SQLite, and data visualization libraries to transform raw retail transactions into business insights. :contentReference[oaicite:1]{index=1}

---

## 📌Project Overview

This project analyzes retail transaction data to:
- clean and prepare raw sales records
- design a star schema for analysis
- calculate KPI metrics
- perform RFM customer segmentation
- run market basket analysis
- study customer retention through cohort analysis
- predict CLV using probabilistic models
- visualize business insights
- export results for reporting and dashboards :contentReference[oaicite:2]{index=2}

---

## 🧰Techniques Used

- Python
- Pandas
- NumPy
- SQLite / SQL
- Matplotlib
- Seaborn
- Plotly
- Apriori Algorithm
- Cohort Analysis
- BG/NBD Model
- Gamma-Gamma Model :contentReference[oaicite:15]{index=15}

---

## Features

- Data import from Excel into Pandas
- Data cleaning using SQL in SQLite
- Star schema design with fact and dimension tables
- KPI metrics calculation
- RFM scoring and customer segmentation
- Market Basket Analysis using Apriori rules
- Cohort analysis for retention tracking
- CLV prediction using BG/NBD and Gamma-Gamma models
- Visualizations for segment and behavior analysis
- CSV export for BI tools like Power BI or Tableau :contentReference[oaicite:3]{index=3}

---

## Project Workflow

1. **Data Import**  
   Load retail data into a DataFrame. :contentReference[oaicite:4]{index=4}

2. **Data Cleaning (SQL)**  
   Remove NULL customer IDs, duplicates, cancelled invoices, negative quantities, negative prices, and standardize dates. :contentReference[oaicite:5]{index=5}

3. **Star Schema Design**  
   Create `Fact_Sales`, `Dim_Customer`, and `Dim_Product` tables. :contentReference[oaicite:6]{index=6}

4. **KPI Metrics**  
   Calculate revenue, AOV, customer count, retention, churn, and market basket KPIs. :contentReference[oaicite:7]{index=7}

5. **RFM Analysis**  
   Score customers using Recency, Frequency, and Monetary values. :contentReference[oaicite:8]{index=8}

6. **Market Basket Analysis**  
   Identify products frequently bought together using association rules. :contentReference[oaicite:9]{index=9}

7. **Cohort Analysis**  
   Measure customer retention over time. :contentReference[oaicite:10]{index=10}

8. **CLV Prediction**  
   Estimate customer lifetime value using BG/NBD and Gamma-Gamma models. :contentReference[oaicite:11]{index=11}

9. **Data Visualization**  
   Display customer segment distribution and recency vs monetary patterns. :contentReference[oaicite:12]{index=12}

10. **Data Export**  
   Export cleaned and analytical outputs into CSV files. :contentReference[oaicite:13]{index=13}

---

## Key Performance Indicators (KPIs)

- **Total Revenue** = Quantity × Unit Price
- **Average Order Value (AOV)** = Total Revenue / Number of Orders
- **Total Customers**
- **Average Revenue per Customer**
- **Recency, Frequency, Monetary**
- **Segment-wise customer count**
- **Revenue contribution by segment**
- **Retention Rate**
- **Churn Rate**
- **Support, Confidence, and Lift** for basket analysis :contentReference[oaicite:14]{index=14}

---



## Output Files

The project generates files for further analysis and reporting, including:
- `clean_retail_data.csv`
- `rfm_segments.csv`
- `market_basket_rules.csv` :contentReference[oaicite:16]{index=16}

---

## Business Value

This project helps businesses:
- identify high-value customers
- target at-risk customers
- improve retention
- increase sales through product bundling
- understand purchasing patterns
- make better marketing decisions :contentReference[oaicite:17]{index=17}

---

## Future Scope

- Build an interactive dashboard
- Add customer churn prediction
- Deploy as a web application
- Improve recommendation system logic
- Automate weekly sales reporting

---

## How to Run

1. Clone the repository
2. Open the notebook in Jupyter Notebook / VS Code
3. Install required libraries
4. Run cells step by step
5. Review generated CSV files and charts

---

## Author

**Charan**

---

## Notes

This project is designed for retail customer analytics and can be extended for marketing, sales strategy, and BI reporting.