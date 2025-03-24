# Pizza Analysis

## Project Overview
This project focuses on analyzing pizza sales data to uncover key insights into customer preferences, trends, and performance metrics. By leveraging data from multiple datasets, it provides a comprehensive view of pizza sales across various categories, sizes, and time periods.

## Datasets Used
1. **order_details.csv**
   - Contains detailed information on each order, including:
     - `order_det`: Unique detail ID for each order.
     - `order_id`: Identifier for the order.
     - `pizza_id`: Specific pizza ordered.
     - `quantity`: Quantity of the pizza ordered.

2. **order.csv**
   - Provides timestamps for each order, including:
     - `order_id`: Identifier for the order.
     - `date`: Date of the order.
     - `time`: Time of the order.

3. **pizzas.csv**
   - Details individual pizzas, such as:
     - `pizza_id`: Unique identifier for each pizza and size.
     - `pizza_type`: Type of pizza (e.g., bbq_ckn).
     - `size`: Size of the pizza (Small, Medium, Large).
     - `price`: Price based on pizza type and size.

4. **pizza_types.csv**
   - Contains information about pizza types, including:
     - `pizza_type`: Unique identifier for the pizza type.
     - `name`: Full name of the pizza.
     - `category`: Category (e.g., Chicken, Supreme, Classic, Veggie).
     - `ingredients`: List of ingredients for each pizza.

## Key Metrics from the Dashboard
- **Total Revenue**: ₹78.24M
- **Total Orders**: 21K
- **Total Quantity Sold**: 49.57K
- **Breakdowns**:
  - Trends by day name and month name.
  - Sales by pizza size (Small, Medium, Large) and category (Chicken, Supreme, Classic, Veggie).
  - Performance of specific pizzas like "The Barbecue Chicken Pizza," "The California Chicken Pizza," and more.

## How to Use
1. Clone the repository using `git clone`.
2. Explore the datasets and dashboard for insights.
3. Use tools like Python, R, or Excel for further analysis or visualization.

![pizza](https://github.com/user-attachments/assets/83574abd-8ab5-4a0f-9266-dcdefbc2d08a)
