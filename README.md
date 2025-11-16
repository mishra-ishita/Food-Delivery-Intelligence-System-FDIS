# 📦 **Food Delivery Intelligence System (FDIS)**

## 📝 **Project Overview**

Food Delivery Intelligence System (FDIS) is an analytics project designed to understand and optimize the operations of an online food-delivery platform.
Using a real-world structured dataset containing orders, customers, restaurants, menus, food items, and order types, this project aims to generate insights across:

* Customer behavior
* Restaurant performance
* Sales & revenue trends
* Food preferences
* Operational efficiency
* Billing accuracy

The project is suitable for portfolios targeting **analytics, product, operations, decision science, and strategy roles**.

## 🎯 **Objectives**

This project focuses on extracting actionable insights across the food-delivery lifecycle:

### **1. Customer Insights**
* Customer demographics and ordering patterns
* High-value and low-value user segments
* Veg vs non-veg preference trends

### **2. Restaurant & Cuisine Analytics**
* Best-performing restaurants
* Cuisine popularity by city
* Rating vs revenue relationships

### **3. Sales & Revenue Analysis**
* Daily and monthly revenue trends
* Average order value (AOV) and growth
* Discount vs final billing analysis

### **4. Operational Performance**
* Order type performance (Delivery / Pickup / Dine-in)
* Preparation vs delivery time patterns
* Delay and distance analysis

### **5. Billing & Financial Accuracy**
* Price vs sales amount validation
* Detection of negative or inconsistent billing entries
* Revenue contribution by city and restaurant

## 📌 Dataset Schema

| Table Name   | Columns |
|--------------|---------|
| **menu**     | menu_id, r_id, f_id, cuisine, price |
| **users**    | user_id, name, age, gender, marital_status, occupation |
| **orders**   | order_date, sales_qty, sales_amount, currency, user_id, r_id |
| **orders_type** | order_id, type |
| **restaurant** | id, name, country, city, rating, rating_count, cuisine_link, address |
| **food**     | f_id, item, veg_or_non_veg |


## 🛠️ **Tools & Technologies**

* **SQL** for data cleaning, joins, aggregation & analysis
* **Python (Pandas, Matplotlib/Seaborn)** for EDA & visualization
* **Power BI / Tableau** for dashboards
* **Excel** for quick exploratory checks

## 🔍 **Key Analysis Performed**

* Revenue, order trends, and seasonality
* City-wise, cuisine-wise, and restaurant-wise performance
* Customer segmentation
* High-selling food categories
* Delivery speed vs customer demographics
* Billing mismatch detection
* Negative sales and outlier identification
* Price vs menu validation

## 📊 **KPIs Designed**

* Average Order Value (AOV)
* Revenue Per User (RPU)
* Orders Per Restaurant
* Top-selling cuisines/items
* Repeat purchase rate
* Delay frequency & average delivery time
* Billing mismatch percentage
* Revenue contribution by city

## 📈 **Insights Summary**

Some typical insights derived (examples):

* Non-vegetarian dishes contribute majority of total sales.
* Young users (18–30) place the highest number of orders.
* High-rated restaurants generate significantly more revenue.
* Delivery orders dominate over pickup/dine-in.
* AOV is higher during weekends.
* Few restaurants show pricing vs billing mismatches.

## 🚀 **Possible Enhancements**

* Implement churn prediction (ML)
* Dynamic pricing model
* Food recommendation system
* Customer segmentation clustering
* Delivery time prediction model

## 📎 **Project Structure**

```plaintext
📁 Food Delivery Intelligence System
│── 📂 data
│── 📂 sql_scripts
│── 📂 python_notebooks
│── 📂 dashboards
│── 📄 README.md
│── 📄 insights_report.pdf
```

## 🤝 **Conclusion**

This project provides an end-to-end analysis of a food delivery ecosystem, making it highly valuable for showcasing:

* Analytical thinking
* Business understanding
* Problem-solving
* Data storytelling
* Dashboarding skills
* SQL + Python proficiency



Just tell me!

