# 📊 E-Commerce Sales Analysis & Power BI Dashboard

## 📌 Project Overview

This project is an **E-Commerce Sales Analysis Dashboard** developed using **Microsoft Power BI** as part of my **CodeAlpha Data Analytics Internship**.

The project analyzes **150,000 e-commerce order records** to understand sales performance, customer behavior, product performance, regional trends, payment methods, marketing channels, and order status.

The main goal of this project is to transform raw e-commerce data into meaningful business insights using **Power Query, DAX, data modeling, and interactive Power BI visualizations**.

---

## 🎯 Project Objectives

The key objectives of this project are:

* Analyze overall e-commerce sales performance.
* Identify top-performing products and categories.
* Analyze sales performance across regions, states, and cities.
* Understand customer segments and age groups.
* Analyze customer payment preferences.
* Evaluate marketing channel performance.
* Analyze order status and delivery performance.
* Identify important sales trends and patterns.
* Create an interactive dashboard for business analysis and decision-making.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Microsoft Excel**
* **Data Cleaning**
* **Data Transformation**
* **Data Modeling**
* **Data Visualization**
* **Business Intelligence**

---

## 📂 Dataset

The dataset contains **150,000 e-commerce order records** along with product and geographical information.

### Dataset Tables

### 1. Orders

The `Orders` table contains transaction-level information.

Key columns include:

* Order ID
* Order Datetime
* Customer ID
* Gender
* Age Group
* Customer Segment
* Region
* State
* City
* Category
* Product
* Quantity
* Unit Price (INR)
* Gross Amount (INR)
* Discount %
* Discount Amount (INR)
* Shipping Fee (INR)
* Net Amount (INR)
* Payment Method
* Order Status
* Delivery Days
* Rating (1-5)
* Marketing Channel

### 2. Products

The `Products` table contains product information:

* Category
* Product
* Price Range Low (INR)
* Price Range High (INR)

### 3. Geography

The `Geography` table contains geographical information:

* Region
* State
* City

---

## 📌 Data Source

The dataset used in this project was collected from **Kaggle** and used for educational and analytical purposes as part of the CodeAlpha internship project.

The dataset contains **150,000 e-commerce order records** along with product and geographical information.

The data was cleaned and transformed using **Power Query** before creating the Power BI dashboard.

---

## 📊 Dashboard Features

The interactive Power BI dashboard provides analysis of the following areas:

### 💰 Sales Performance

* Total Revenue
* Total Orders
* Average Order Value
* Average Customer Rating
* Cancelled Orders
* Cancellation Rate
* Average Delivery Days

### 🛍️ Product & Category Analysis

* Revenue by Category
* Product-wise performance
* Top-performing products
* Category comparison

### 🌍 Geographic Analysis

* Orders by State
* Regional sales performance
* State-wise order distribution

### 👥 Customer Analysis

* Customer Segment
* Age Group
* Gender
* Customer behavior

### 💳 Payment Analysis

The dashboard analyzes different payment methods such as:

* UPI
* Credit Card
* Debit Card
* Cash on Delivery
* Other payment methods

### 📢 Marketing Analysis

Marketing channels analyzed include:

* Organic Search
* Social Media
* Paid Ads
* Direct
* Email Campaign
* Referral

### 📦 Order & Delivery Analysis

* Orders by Month
* Sales by Time
* Orders by Discount %
* Order Status
* Cancellation Rate
* Average Delivery Days

---

## 📈 Key Performance Indicators

Based on the complete dataset analysis:

| KPI                     |         Value |
| ----------------------- | ------------: |
| Total Orders            |       150,000 |
| Total Quantity Sold     |       214,958 |
| Total Net Sales         | ₹176.25 Crore |
| Average Order Value     |       ₹11,750 |
| Average Customer Rating |      4.06 / 5 |
| Total Discount Amount   |  ₹26.55 Crore |

---

## 🔑 Key Findings

### 🏆 Category Performance

**Electronics** was the highest-performing category, generating approximately **₹134.21 Crore** in net sales.

### 🛒 Top-Performing Products

The major revenue-generating products included:

* Power Bank
* Laptop
* Smartwatch
* Smartphone
* Bluetooth Speaker

### 🌍 Regional Performance

The **South Region** generated the highest net sales, contributing approximately **₹46.10 Crore**.

### 🗺️ State Performance

**Rajasthan** generated approximately **₹14.88 Crore** in net sales, followed by Maharashtra and Gujarat.

### 👥 Customer Segment

The **Regular Customer** segment generated the highest sales, contributing approximately **₹88.72 Crore**.

### 🎯 Age Group

Customers in the **25–34 age group** generated the highest sales, contributing approximately **₹62.18 Crore**.

### 💳 Payment Method

**UPI** was the leading payment method, contributing approximately **₹60.00 Crore** in net sales.

### 📢 Marketing Channel

**Organic Search** was the leading marketing channel, contributing approximately **₹44.55 Crore** in net sales.

### 📦 Order Status

**Delivered orders** contributed approximately **₹120.59 Crore** in net sales.

---

## 💡 Business Insights

The analysis provides the following business insights:

1. **Electronics is the strongest-performing category**, indicating high customer demand for electronic products.

2. The **25–34 age group** represents an important customer segment and can be targeted with personalized campaigns and offers.

3. **Regular customers contribute significantly to revenue**, highlighting the importance of customer retention strategies.

4. **UPI is a major payment method**, showing the importance of convenient digital payment options.

5. **Organic Search performs strongly**, indicating that SEO and organic marketing can be valuable customer acquisition channels.

6. Regional differences in sales can help businesses optimize inventory distribution and marketing strategies.

7. Order and delivery analysis can help identify opportunities to improve customer experience and operational efficiency.

---

## 🔄 Data Analysis Process

### Step 1: Data Collection

The e-commerce dataset was collected from **Kaggle**.

### Step 2: Data Cleaning

The dataset was imported into Power BI and processed using **Power Query**.

The cleaning process included:

* Checking missing values
* Checking duplicate records
* Correcting data types
* Formatting columns
* Handling inconsistent values
* Preparing the data for analysis

### Step 3: Data Transformation

Power Query was used to:

* Transform columns
* Format date and numerical fields
* Prepare tables for analysis
* Create a structured dataset

### Step 4: Data Modeling

Relationships between the relevant tables were created to build an effective Power BI data model.

Main tables:

* Orders
* Products
* Geography

### Step 5: DAX

DAX measures were used to calculate important business metrics such as:

* Total Revenue
* Total Orders
* Total Quantity
* Average Order Value
* Average Rating
* Cancellation Rate
* Average Delivery Days

### Step 6: Data Visualization

Different Power BI visualizations were used, including:

* KPI Cards
* Bar Charts
* Column Charts
* Line Charts
* Donut Charts
* Tables
* Slicers

### Step 7: Dashboard Development

An interactive dashboard was created with filters and slicers to allow users to explore sales data based on different dimensions.

---

## 🖼️ Dashboard Preview

### Overall Dashboard

![E-Commerce Sales Power BI Dashboard](screenshots/dashboard.png)

### Filtered Dashboard

![Filtered E-Commerce Sales Power BI Dashboard](screenshots/dashboard_filtered.png)

---

## 📁 Project Structure

```text
CodeAlpha-Ecommerce-Sales-PowerBI-Dashboard/
│
├── E-Commerce_Sales_Dashboard.pbix
├── ecommerce_sales_dataset.xlsx
├── README.md
│
└── screenshots/
    ├── dashboard.png
    └── dashboard_filtered.png
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `E-Commerce_Sales_Dashboard.pbix` using **Microsoft Power BI Desktop**.
3. If required, update the Excel dataset path.
4. Refresh the dataset.
5. Use the available slicers and filters to interact with the dashboard.
6. Explore sales, customer, product, geographic, payment, and marketing insights.

---

## 🎓 Internship Details

**Internship:** CodeAlpha Data Analytics Internship

**Project:** E-Commerce Sales Analysis Dashboard

**Technology:** Microsoft Power BI

**Key Skills Used:**

* Power BI
* Power Query
* DAX
* Excel
* Data Cleaning
* Data Transformation
* Data Modeling
* Data Visualization
* Business Analytics

---

## 📌 Project Highlights

* Analyzed **150,000 e-commerce transactions**.
* Built an interactive **Power BI dashboard**.
* Used **Power Query** for data cleaning and transformation.
* Used **DAX** for analytical calculations.
* Created interactive slicers and filters.
* Performed product and category analysis.
* Performed customer and demographic analysis.
* Performed geographic analysis.
* Analyzed payment and marketing channels.
* Generated business-focused insights from raw data.

---

## 👨‍💻 Author

### Ayan Kharadi

**Aspiring Data Analyst | Python Developer | Power BI**

📍 Solapur, Maharashtra, India

---

## ⭐ Conclusion

This project demonstrates how raw e-commerce transaction data can be transformed into an interactive and meaningful **Business Intelligence dashboard using Microsoft Power BI**.

The dashboard provides insights into sales performance, products, customer segments, geographic performance, payment methods, marketing channels, and order trends.

Through this project, I gained practical experience in **Power Query, DAX, data modeling, data visualization, and business analytics**.

---

⭐ If you find this project useful, consider giving the repository a star!
