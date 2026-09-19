# 🛒 E-Commerce Sales & Customer Analytics

## 📌 Project Overview

This project analyzes the Olist Brazilian E-Commerce dataset to understand sales performance, customer behavior, product performance, payment preferences, customer satisfaction, and delivery performance.

The analysis was performed using **Python, SQL, and Tableau** to transform raw e-commerce data into meaningful business insights and an interactive dashboard.

---

## 🎯 Project Objectives

- Analyze overall e-commerce sales and revenue trends
- Identify high-performing product categories
- Understand customer purchasing behavior
- Analyze repeat customer activity
- Identify preferred payment methods
- Evaluate customer review patterns
- Analyze delivery performance
- Examine sales distribution across Brazilian states
- Build an interactive Tableau dashboard for business reporting

---

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
- **SQL**
  - SQLite
- **Tableau**
  - Data visualization
  - Dashboard development
- **Jupyter Notebook**
- **Excel**

---

## 📂 Dataset

The project uses the **Olist Brazilian E-Commerce Public Dataset**, containing information about customers, orders, order items, payments, reviews, and products.

### Main Tables

- Customers
- Orders
- Order Items
- Payments
- Reviews
- Products

The dataset contains approximately **99K orders** and **96K unique customers**.

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Preparation

- Inspected dataset structure and data types
- Identified missing values
- Converted date columns to appropriate datetime formats
- Created delivery-time and delivery-delay metrics
- Prepared data for Python, SQL, and Tableau analysis

### 2. Exploratory Data Analysis

Analyzed:

- Monthly revenue trends
- Product category performance
- Customer purchasing behavior
- Repeat customers
- Payment methods
- Review scores
- Customer distribution by state
- Delivery performance
- Delivery time vs. review scores

### 3. SQL Analysis

SQL queries were used to analyze:

- Orders by status
- Revenue by customer state
- Monthly revenue
- Product category performance
- Repeat customers
- Repeat-customer percentage
- Payment methods
- Review distribution
- Delivery performance

### 4. Tableau Dashboard

An interactive dashboard was created containing:

- Total Revenue
- Total Orders
- Unique Customers
- Average Order Value
- Average Delivery Time
- Monthly Revenue Trend
- Revenue by Product Category
- Top 10 Products
- Sales by State
- Payment Method Distribution
- Review Score Distribution
- Delivery Performance

---

## 📊 Key Business Insights

### Revenue

The dataset contains approximately **16.01M in total payment value**, with revenue increasing substantially during 2017 and 2018.

### Product Performance

The highest product-price revenue categories included:

1. `beleza_saude` — approximately 1.26M
2. `relogios_presentes` — approximately 1.21M
3. `cama_mesa_banho` — approximately 1.04M

### Customer Retention

- Unique customers: **96,096**
- Repeat customers: **2,997**
- Repeat-customer percentage: **3.12%**

### Payment Preferences

Credit cards represented approximately **78.34%** of total payment value, followed by boleto at **17.92%**.

### Customer Satisfaction

- Average review score: **4.09 / 5**
- Positive reviews (4–5): **77.07%**

### Delivery Performance

- Average delivery time: **12.09 days**
- **6.77%** of orders with available delivery-date data were delivered later than the estimated delivery date.
- Late orders had an average delay of **10.62 days**.

### Delivery & Reviews

Orders delivered within 7 days had an average review score of **4.41**, while orders taking more than 30 days had an average score of **2.18**.

This indicates an **association between longer delivery times and lower review scores**.

### Geographic Sales

São Paulo recorded the highest payment value among Brazilian states, followed by Rio de Janeiro and Minas Gerais.

---

## 📈 Dashboard Preview

The Tableau dashboard provides a consolidated view of:

- Revenue trends
- Product performance
- Customer distribution
- Payment behavior
- Review scores
- Delivery performance

*Add your Tableau dashboard screenshot here.*

---

## 💡 Business Takeaways

The analysis highlights several areas that can support business decision-making:

- Monitor high-performing product categories to understand revenue drivers.
- Investigate the relatively low repeat-customer percentage and explore customer retention strategies.
- Continue monitoring delivery performance because longer delivery times are associated with lower review scores.
- Focus on major customer markets such as São Paulo, Rio de Janeiro, and Minas Gerais.
- Track payment-method preferences to understand customer purchasing behavior.

---

## 👩‍💻 Skills Demonstrated

**Python | Pandas | Data Cleaning | Exploratory Data Analysis | SQL | SQLite | Tableau | Data Visualization | Dashboard Development | Business Analysis | Excel**

---

## 📌 Project Outcome

This project demonstrates an end-to-end **Data Analytics workflow**, from raw data preparation and exploratory analysis to SQL-based analysis, business insight generation, and interactive Tableau dashboard development.
