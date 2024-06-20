# Instacart Analysis
**Data Analyst Bootcamp** @ Tripleten<br>
Sprint 7 Project - Exploring and Cleaning Data with Pandas

<br> 

## Project Description
Instacart is a grocery delivery platform that allows customers to place grocery orders and have them delivered to their doorsteps, similar to Uber Eats and DoorDash. Our mission is to clean up the data and prepare a report that provides insight into the shopping habits of Instacart customers.

## Data Dictionary
- **`instacart_orders.csv`**: each row corresponds to one order on the Instacart app<br>
`order_id`: ID number that uniquely identifies each order<br>
`user_id`: ID number that uniquely identifies each customer account<br>
`order_number`: the number of times this customer has placed an order<br>
`order_dow`: day of the week that the order placed (which day is 0 is uncertain)<br>
`order_hour_of_day`: hour of the day that the order was placed<br>
`days_since_prior_order`: number of days since this customer placed their previous order<br>

- **`products.csv`**: each row corresponds to a unique product that customers can buy<br>
`product_id`: ID number that uniquely identifies each product<br>
`product_name`: name of the product<br>
`aisle_id`: ID number that uniquely identifies each grocery aisle category<br>
`department_id`: ID number that uniquely identifies each grocery department category<br>

- **`order_products.csv`**: each row corresponds to one item placed in an order<br>
`order_id`: ID number that uniquely identifies each order<br>
`product_id`: ID number that uniquely identifies each product<br>
`add_to_cart_order`: the sequential order in which each item was placed in the cart<br>
`reordered`: 0 if the customer has never ordered this product before, 1 if they have<br>

- **`aisles.csv`**<br>
`aisle_id`: ID number that uniquely identifies each grocery aisle category<br>
`aisle`: name of the aisle<br>

- **`departments.csv`**<br>
`department_id`: ID number that uniquely identifies each grocery department category<br>
`department`: name of the department

## Project Requirements
- Preprocess data.
- Visualizations:
  - The number of people placing orders for each hour of the day.
  - The days of the week when people shop for groceries.
  - The duration between successive orders placed by customers.
  - The distribution of the number of orders placed by customers.
- Questions to answer:
  - Is there a difference in the 'order_hour_of_day' distributions between Wednesdays and Saturdays?
  - What are the top 20 most frequently ordered products (include their IDs and names)?
  - How many items do people typically buy in one order? What does the distribution of this look like?
  - What are the top 20 most frequently reordered items (include their names and product IDs)?
  - For each product, what proportion of its orders are reorders?
  

## About the Data
This dataset was publicly released by Instacart in 2017 for a Kaggle competition. Although the original dataset is no longer available on the Instacart website, modified CSV files are used for this project. The data size has been reduced, so that the calculations can run faster for the purpose of this project. While missing and duplicate values have been introduced, these changes have been made carefully to preserve the original data distribution.
