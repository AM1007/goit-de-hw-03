# Homework. Data Analysis in PySpark

### Input Data:

You will be working with three input CSV files:

**users.csv** — User data:

- `user_id` (unique identifier for the user)
- `name` (user’s name)
- `age` (user’s age)
- `email` (email address)

**purchases.csv** — Purchase data:

- `purchase_id` (unique identifier for the purchase)
- `user_id` (identifier of the user who made the purchase)
- `product_id` (unique identifier for the product)
- `date` (purchase date)
- `quantity` (number of items purchased)

**products.csv** — Product information:

- `product_id` (unique identifier for the product)
- `product_name` (name of the product)
- `category` (product category)
- `price` (price per unit)


### Step-by-Step Instructions

1. Load and read each CSV file as a separate DataFrame.
2. Clean the data by removing any rows with missing values.
3. Calculate the total purchase amount for each product category.
4. Determine the total purchase amount for each product category within the age group of 18 to 25 (inclusive).
5. Calculate the share of spending for each product category as a percentage of total expenditures within the 18 to 25 age group.
6. Identify the top 3 product categories with the highest percentage of spending by consumers aged 18 to 25.