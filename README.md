# Superstore Sales Analysis

## 📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on the Superstore dataset to understand business performance and identify meaningful insights related to sales, profit, customers, products, discounts, regions, shipping modes, and time-based trends.

The goal of the analysis is not only to identify high-performing areas but also to discover loss-making products, categories, regions, and discount strategies that may negatively affect profitability.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall sales, profit, orders, and customer performance.
- Identify the best and worst performing product categories.
- Analyze sub-categories that generate high profits or losses.
- Understand the relationship between discount and profit.
- Identify top customers based on sales and profitability.
- Identify high-performing and loss-making products.
- Compare sales and profitability across different regions.
- Analyze sales and profit trends over time.
- Evaluate business performance across different shipping modes.
- Provide data-driven business recommendations.

---

## 📊 Dataset Information

The dataset contains transactional sales data from a retail superstore.

### Dataset Size

- **Rows:** 9,994
- **Columns:** 21
- **Unique Customers:** 793
- **Unique Orders:** 5,009

### Key Features

The dataset includes information about:

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Region
- Product ID
- Product Name
- Category
- Sub-Category
- Sales
- Quantity
- Discount
- Profit

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Data Cleaning and Validation

The following checks were performed:

- Missing value analysis
- Duplicate row detection
- Date conversion
- Data type validation
- Numerical data validation
- Outlier detection using the IQR method

Potential sales outliers were retained because high-value sales may represent legitimate transactions rather than data errors.

---

### 2. Overall Business Performance

The analysis calculated:

- Total Sales
- Total Profit
- Total Quantity Sold
- Unique Customers
- Unique Orders

**Key Results:**

- Total Sales: approximately **$2.3 Million**
- Total Profit: approximately **$286K**
- Total Quantity Sold: **37,873**
- Unique Customers: **793**
- Unique Orders: **5,009**

---

### 3. Category and Sub-Category Analysis

Sales, profit, and profit margins were analyzed across product categories and sub-categories.

**Key Findings:**

- Technology was the strongest-performing category.
- Furniture generated high sales but had a very low profit margin.
- Copiers, Phones, and Accessories were among the most profitable sub-categories.
- Tables, Bookcases, and Supplies were identified as loss-making sub-categories.

---

### 4. Discount and Profit Analysis

The relationship between discount and profitability was investigated.

**Key Findings:**

- Discount and Profit showed a negative correlation of approximately **-0.22**.
- Higher discount levels were generally associated with lower profitability.
- Several products became loss-making when sold with high discounts.

---

### 5. Customer Analysis

Customers were analyzed based on:

- Total Sales
- Total Orders
- Total Profit
- Average Order Value

The analysis showed that customers generating high sales are not necessarily the most profitable customers.

For example, Sean Miller generated the highest sales but resulted in an overall negative profit, while Tamara Chand was among the most profitable customers.

---

### 6. Product Analysis

Products were analyzed based on:

- Total Sales
- Total Profit
- Quantity Sold
- Discount Levels

**Key Findings:**

- The Canon imageCLASS 2200 Advanced Copier generated the highest sales and profit.
- Several high-value products generated significant losses.
- High discount levels were a major factor contributing to losses for some products.

---

### 7. Regional Analysis

Sales, profit, quantity, and profit margin were analyzed across regions.

**Key Findings:**

- The West region generated the highest sales and profit.
- The Central region had the lowest profit margin.
- Losses in the Central region were strongly associated with Furniture products.
- Tables, Bookcases, and Furnishings contributed significantly to poor profitability in this region.

---

### 8. Time Series Analysis

Sales and profit trends were analyzed from **2014 to 2017**.

**Key Findings:**

- Sales generally increased over time.
- 2017 recorded the highest annual sales.
- Sales showed seasonal patterns.
- September, November, and December were among the strongest sales periods.
- February had relatively lower sales.

---

### 9. Shipping Mode Analysis

Business performance was compared across different shipping modes.

**Key Findings:**

- Standard Class generated the highest sales, profit, and number of orders.
- First Class had the highest profit margin.

---

## 💡 Business Recommendations

Based on the analysis, the following recommendations can be made:

1. **Review high discount policies** and establish product-specific discount limits.
2. **Investigate loss-making Furniture products**, especially Tables and Bookcases.
3. **Improve Central region profitability** by reviewing product pricing and discount strategies.
4. **Promote high-profit products** such as Copiers, Phones, and Accessories.
5. **Evaluate customers based on profitability**, not only sales.
6. **Prepare inventory and marketing strategies for high-demand months**, especially September, November, and December.
7. **Use profit margin along with sales and profit** when making business decisions.

---

## 📁 Project Structure

```text
Superstore-Sales-Analysis/
│
├── Superstore_Sales_Analysis.ipynb
├── Sample - Superstore.csv
└── README.md
