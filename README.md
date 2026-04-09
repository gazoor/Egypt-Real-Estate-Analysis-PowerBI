# 🏢 Egypt Real Estate Market Analysis Dashboard

## 🏗️ Data Architecture (Star Schema)
To ensure high performance and scalability, the data model was built using a **Star Schema** architecture:
* **Fact Table:** Contains all property transactions and core metrics (Price, Area, Bedrooms).
* **Dimension Tables:** Separate tables for **Geography** (City/District), **Property Details** (Type/Level), and **Builders**.
* **Relationships:** Optimized One-to-Many (1:*) relationships for efficient filtering and DAX performance.

---

## 🚀 Key Insights & Features
* **Market Overview:** Quick KPIs for Total Projects, Average Area, and Average Pricing.
* **Price Benchmarking:** Deep dive into pricing by Bedrooms, Property Type, and City.
* **Advanced Filtering:** User-friendly search panel to filter data by Level, Type, and Area range.

---

## 🛠️ Technical Stack
* **Tool:** Power BI Desktop.
* **Modeling:** **Star Schema** with optimized table relationships.
* **Data Cleaning:** Power Query (ETL) for data normalization.
* **DAX:** Implementation of custom measures for dynamic market analysis.
