# 📊 Retail Sales Analysis 

## 📌 Project Description

This project analyzes **online retail sales data** using Python to identify **sales trends, customer behavior, and business insights**.
The complete analysis is implemented in the Jupyter Notebook:

📄 **`Retail Sales Analysis.ipynb`**

The project demonstrates **real-world data analysis workflow**, including data cleaning, visualization, and customer segmentation.

## 🎯 Project Objectives

* Clean and preprocess raw retail sales data
* Analyze sales trends across time and countries
* Identify top-selling products and high-value customers
* Visualize relationships between Quantity, Unit Price, and Sales
* Perform **RFM (Recency, Frequency, Monetary) analysis**


## 🗂️ Dataset Information

The dataset contains transactional data from an online retail store.

### Columns Used:

* **InvoiceNo** – Unique invoice number
* **StockCode** – Product code
* **Description** – Product description
* **Quantity** – Number of items purchased
* **InvoiceDate** – Date and time of transaction
* **UnitPrice** – Price per item
* **CustomerID** – Unique customer identifier
* **Country** – Customer location


## 🛠️ Libraries & Tools Used

* **Python 3**
* **NumPy** – Numerical computations
* **Pandas** – Data manipulation and analysis
* **Matplotlib** – Basic data visualizations
* **Seaborn** – Advanced statistical visualizations
* **Jupyter Notebook** – Project execution and documentation


## 🔄 Project Workflow

### 1️⃣ Data Loading

* Loaded the CSV file using `pandas.read_csv()`
* Handled encoding issues using `latin1`


### 2️⃣ Data Understanding

* Checked dataset shape and structure
* Identified missing values and incorrect data types


### 3️⃣ Data Cleaning

* Removed rows with missing `CustomerID`
* Removed cancelled invoices
* Removed negative and zero values in `Quantity` and `UnitPrice`
* Replaced missing values in `Description` using **mode strategy**


### 4️⃣ Feature Engineering

* Converted `InvoiceDate` to datetime format
* Created **TotalSales = Quantity × UnitPrice**
* Extracted Year, Month, and Day for time-based analysis


### 5️⃣ Exploratory Data Analysis (EDA)

Performed multiple visualizations, including:

* 📈 Monthly sales trend (line plot)
* 📊 Top-selling products (bar chart)
* 🌍 Country-wise total sales
* 🔵 Quantity vs Unit Price (scatter plot)
* 📦 Outlier detection using boxplots


### 6️⃣ Customer Analysis

* Identified top customers by total revenue
* Analyzed customer purchase frequency and spending patterns


## 📊 Key Visualizations in the Notebook

* Monthly Sales Trend
* Country-wise Sales Comparison
* Quantity vs Unit Price Scatter Plot
* Total Sales Boxplot (Outlier Detection)


## 💡 Business Insights

* Most sales occur during festive/peak seasons
* The United Kingdom contributes the highest revenue
* A small percentage of customers generate a large portion of sales
* Quantity and Unit Price do not have a strong direct correlation


## 📈 Conclusion

This project showcases **end-to-end retail data analysis** using Python.
It highlights skills in:

* Data cleaning
* Exploratory Data Analysis
* Visualization
* Customer analytics
* Business insight generation

