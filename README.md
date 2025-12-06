# Farmers Market Database — SQL Query Practice

## Overview

This repository contains a curated set of SQL practice tasks based on the **Farmers Market relational database**.  
The exercises are designed to help learners strengthen their understanding of:

- SQL joins  
- Filtering and conditional logic  
- Aggregation and grouping  
- String manipulation  
- Date-based queries  
- Real-world analytical reporting  

The dataset represents a realistic farmers market environment, including customers, vendors, products, booths, inventory, and purchase activity.

---

## Database Schema Overview

The database includes the following main tables:

- **product** — Stores product information.
- **vendor_booth_assignments** — Tracks vendor booth assignments by market date.
- **customer_purchases** — Logs all purchase transactions made by customers.
- **customer** — Contains customer demographic details.
- **market_date_info** — Holds market dates and weather-related information.
- **vendor** — Stores vendor identities and business types.
- **product_category** — Categorizes products into defined groups.
- **vendor_inventory** — Contains vendor inventory and pricing data.

---

## SQL Tasks

1. Retrieve all products available in the market.  
2. Display 10 rows from `vendor_booth_assignments` including market_date, vendor_id, and booth_number.  
3. Calculate the total amount spent in each purchase (quantity × cost_per_qty), including all purchase details.  
4. Merge each customer’s first and last name into a single full-name column.  
5. Extract all product names belonging to product category 1.  
6. Count how many products were for sale on each market date.  
7. Generate a detailed report of all purchases made by customer_id 4, sorted by market_date, vendor_id, and product_id.  
8. Retrieve product information for product IDs between 3 and 8 (not inclusive), or product ID 10.  
9. Show all purchases made by customer_id 4 at vendor_id 7, including total amount.  
10. Find customer details for customers named “carlos” or with the last name “diaz.”  
11. Retrieve vendor 7's booth assignments between April 3, 2019, and May 16, 2019.  
12. Return customers with last names: Diaz, Edwards, or Wilson.  
13. Analyze purchases made on market days when it rained.  
14. List all products that do not have a size value.  
15. Retrieve customer data for partial name matches such as “jerry,” “jeremy,” or “jeremiah.”  
16. Merge customer first and last names into a single UPPERCASE full-name column.  
17. List all booths assigned to vendor 2 on or before April 20, 2019.  
18. Identify which vendors primarily sell fresh produce vs. other products.  
19. Calculate the total quantity purchased by each customer per market date.  
20. Count the number of different product types that customer 10 purchased on each market date.

---

