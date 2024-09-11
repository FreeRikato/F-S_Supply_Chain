# Dataco SMART SUPPLY CHAIN FOR BIG DATA ANALYTICS

## About Dataset 

A DataSet of Supply Chains used by the company DataCo Global was used for the analysis. Dataset of Supply Chain , which allows the use of Machine Learning Algorithms and R Software.
Areas of important registered activities : Provisioning , Production , Sales , Commercial Distribution.It also allows the correlation of Structured Data with Unstructured Data for knowledge generation.

> Type Data :
- Structured Data : DataCoSupplyChainDataset.csv
- Unstructured Data : tokenized_access_logs.csv (Clickstream)

> Types of Products : Clothing , Sports , and Electronic Supplies

Additionally it is attached in another file called DescriptionDataCoSupplyChain.csv, the description of each of the variables of the DataCoSupplyChainDatasetc.csv.

## **Objective**
To perform a basic analysis of supply chain performance using structured data (DataCoSupplyChainDataset.csv) and basic insights from the clickstream data (tokenized_access_logs.csv). The final output will be a basic Streamlit dashboard highlighting essential supply chain metrics and customer behavior insights.

## **Project Scope**
- **Main focus areas**:
  - Sales analysis
  - Inventory analysis
  - Basic customer behavior insights using clickstream data
  - Simple demand forecasting for future planning

## **Steps**

### 1. **Data Exploration and Cleaning**
   - **Load the structured data (DataCoSupplyChainDataset.csv)**:
     - Explore the dataset to understand key variables, focusing on product categories, sales data, inventory levels, and shipment data.
   - **Basic Data Cleaning**:
     - Handle missing values, if any.
     - Ensure consistent data formats (e.g., dates, numeric fields).
   - **Unstructured Data (Clickstream)**:
     - Conduct basic exploration of the clickstream data.
     - Focus on key metrics like number of clicks, session durations, and page visits.

### 2. **Exploratory Data Analysis (EDA)**
   - **Sales Analysis**:
     - Calculate total sales per product category (Clothing, Sports, Electronics).
     - Identify top-selling products.
     - Create simple visualizations for sales trends over time (e.g., line charts).
   - **Inventory Analysis**:
     - Analyze current stock levels and calculate average inventory turnover rate (how often stock is sold and replaced).
   - **Shipping and Delivery Times**:
     - Analyze delivery times to see how efficient the supply chain is and identify possible delays or bottlenecks.
   - **Clickstream Data**:
     - Analyze customer behavior, focusing on:
       - Number of sessions
       - Most visited product pages
       - Basic correlation with sales trends

### 3. **Basic Demand Forecasting**
   - **Simple Sales Forecasting**:
     - Using historical sales data, create a simple forecasting model (e.g., using moving averages) to predict future demand for the next few months for each product category.

### 4. **Visualization and Dashboard (Streamlit)**
   - **Key Metrics Dashboard**:
     - **Sales Overview**:
       - Total sales by product category.
       - Sales trends over time (line chart).
     - **Inventory Insights**:
       - Current stock levels.
       - Inventory turnover rates.
     - **Shipping Performance**:
       - Average delivery times.
       - Number of delayed shipments (if data is available).
     - **Customer Behavior** (Clickstream Analysis):
       - Number of sessions and most visited pages.
       - A basic correlation between clickstream data and sales trends (if significant).

   - **User Interaction**:
     - Allow filtering by product category (Clothing, Sports, Electronics).
     - Simple date range filters for analyzing trends over specific periods.

### **Tools and Deliverables**
- **Tools**: Python (Pandas, Matplotlib, Streamlit), basic machine learning for forecasting (e.g., scikit-learn or statsmodels for moving average).
- **Deliverable**: A basic Streamlit app with:
  - Key supply chain metrics (sales, inventory, shipping).
  - Simple visualizations of customer interactions (from clickstream data).
  - A simple demand forecast for planning purposes.

---

This smaller project focuses on the essential aspects of supply chain analytics without diving too deep into advanced predictive modeling or complex correlations. It will allow you to build a simple but functional dashboard to demonstrate key insights from the data.
