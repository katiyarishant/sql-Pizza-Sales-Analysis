# 🍕 Pizza Sales Analysis Using SQL

Welcome to my SQL-based Pizza Sales Analysis project!  
This project uses SQL queries to uncover valuable business insights from pizza sales data.

---

## 📌 Project Objectives

- Analyze sales performance of different pizza types and categories
- Identify customer preferences (sizes, categories, etc.)
- Evaluate peak order times
- Track revenue growth over time
- Help optimize business strategy using data insights

---

## 🛠️ Tools & Technologies Used

- **SQL** (Structured Query Language)
- **RDBMS** (MySQL)
- **Excel / CSV files** (for raw data)
- **DB Diagram** (for schema visualization)

---

## 🗂️ Database Schema

This project uses four main tables:

- **Orders**
  - `order_id` (Primary Key)
  - `order_date`
  - `order_time`

- **Order_Details**
  - `order_details_id` (Primary Key)
  - `order_id` (Foreign Key)
  - `pizza_id` (Foreign Key)
  - `quantity`

- **Pizzas**
  - `pizza_id` (Primary Key)
  - `pizza_type_id` (Foreign Key)
  - `size`
  - `price`

- **Pizza_Types**
  - `pizza_type_id` (Primary Key)
  - `name`
  - `category`
  - `ingredients`

---

## 🔍 Key SQL Queries and Insights

- ✅ Total revenue generated from pizza sales  
- ✅ Highest-priced pizza  
- ✅ Most common pizza size ordered  
- ✅ Top 5 most ordered pizza types  
- ✅ Total quantity ordered by pizza category  
- ✅ Distribution of orders by hour of the day  
- ✅ Average pizzas ordered per day  
- ✅ Top 3 pizza types by revenue  
- ✅ Revenue contribution % of each pizza category  
- ✅ Cumulative revenue over time  
- ✅ Top 3 revenue-generating pizzas per category  

---

## 🙋‍♂️ Author

**Ishant Katiyar**   
📧 [ishantkatiyar68@gmail.com](mailto:ishantkatiyar68@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/ishantkatiyar/)

