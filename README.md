
# Restaurant Order & Menu Analysis Using SQL

This project is part of my **Week-4 internship task at Rhives Technologies**.  
The goal of this project is to analyze restaurant menu and order data using **SQL** to understand menu performance, customer ordering patterns, and high-value revenue trends.

---

## Project Overview

The project uses two main tables:

- `menu_items` – Contains details of each menu item  
  - `menu_item_id`, `item_name`, `category`, `price`
- `order_details` – Contains details of each ordered item  
  - `order_details_id`, `order_id`, `order_date`, `order_time`, `item_id`

Using these tables, various SQL queries were written to explore:

- Menu pricing and category-wise distribution  
- Order volume and date range  
- Most and least ordered items  
- Highest spend orders and their item breakdown  

---

##  Objectives

Key analysis objectives:

1. Explore the **menu_items** table  
   - Total items on the menu  
   - Least and most expensive items  
   - Italian dishes count and their price range  

2. Explore the **order_details** table  
   - Date range of orders  
   - Total number of orders and items ordered  
   - Orders with the highest number of items  
   - Orders having more than 12 items  

3. Item popularity analysis  
   - Most ordered item(s) and their categories  
   - Least ordered item(s) and their categories  

4. Revenue & high-value orders  
   - Top 5 highest-spend orders  
   - Items purchased in the highest-spend order  
   - Item-level details for top 5 high-value orders  

---

##  Tech Stack

- **Database:** MySQL  
- **Language:** SQL  
- **Tools Used:** MySQL Workbench / any SQL client  
- **Other:** Basic data interpretation & reporting

---

##  Files in This Repository

- `create_restaurant_db.sql` – SQL script to create schema, tables, and insert data  
- `queries.sql` – SQL queries used for analysis (objectives-wise)  
- `presentation_week4.pptx` – Project presentation (findings & visuals)  
- `report_week4.pdf` – Detailed report of analysis (optional, if added)

*(Rename files as per your actual filenames before committing.)*

---

##  How to Run

1. Open your SQL client (e.g., MySQL Workbench).  
2. Create a new schema or use the one defined in the script.  
3. Run `create_restaurant_db.sql` to:
   - Create the `restaurant_db` schema
   - Create `menu_items` and `order_details` tables
   - Insert all sample data
4. Execute the queries from `queries.sql` to reproduce:
   - Menu analysis  
   - Order analysis  
   - Item popularity  
   - High-spend order analysis  

---

##  Key Findings (Summary)

### 🧾 Menu Findings
- The menu includes a variety of items across multiple categories.  
- There is a clear price range between the **least** and **most** expensive items.  
- Italian dishes are well represented, with distinct low and high price points.  
- Mid-priced items form the core of the menu, supporting balanced customer choice.

###  Order Findings
- Orders span across a defined date range, showing consistent customer activity.  
- Multiple high-item orders and bulk orders were identified.  
- The **top 5 highest-spend orders** significantly contribute to total revenue.  

###  Customer Behaviour Findings
- Certain items are ordered very frequently, indicating strong customer preference.  
- Some items are rarely ordered, highlighting potential candidates for promotion or menu revision.  
- Customers tend to choose moderately priced items, reflecting price-sensitive behaviour.  

---

##  Acknowledgements

This project was completed as part of my **internship at Rhives Technologies**.  
It helped me strengthen my skills in:

- SQL querying  
- Data analysis using relational databases  
- Interpreting business insights from transactional data  

---


