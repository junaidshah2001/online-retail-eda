# 🛍️ Online Retail Store Analysis

A data analysis project focused on understanding customer behavior and sales trends using a real-world online retail dataset. This project explores key metrics such as top-selling products, most valuable customers, and country-wise sales performance.

---

## 📌 Objectives

- Analyze sales performance across different countries
- Identify best-selling products and top revenue-generating customers
- Discover patterns in order frequency, time, and quantity
- Gain business insights from visualizations

---

## 🔧 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel (for source data)

---

## 📂 Dataset Description

- **File Name**: `online_retail.xlsx`
- **Source**: Online retail transactions from a UK-based store
- **Features**:
  - `InvoiceNo`: Unique transaction ID
  - `StockCode`: Product/item ID
  - `Description`: Product name
  - `Quantity`: Number of items sold
  - `InvoiceDate`: Date and time of purchase
  - `UnitPrice`: Price per item
  - `CustomerID`: Unique customer identifier
  - `Country`: Customer's country

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Key Visualizations

- Top 10 best-selling products
- Country-wise revenue comparison
- Top 10 highest spending customers
- Time-of-day order distribution

### 📈 Sample Plots

![Top Products](images/top_products.png)
![Sales by Country](images/sales_by_country.png)

---

## 🔍 Key Insights

- 🇬🇧 **United Kingdom** accounts for the majority of total sales
- 🛍️ The product "**WHITE HANGING HEART T-LIGHT HOLDER**" is the top seller
- 💰 A small group of customers contributes a large portion of the revenue (Pareto effect)
- 🕒 Most purchases occur during working hours on weekdays

---

## 🧠 How to Run This Project

1. Clone the repository or download the `.ipynb` file
2. Make sure you have Python 3 and the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn

