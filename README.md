📊 Dataset

The dataset contains sales transactions from a retail superstore.

Column Name	Description
Order ID	Unique order identifier
Order Date	Date when the order was placed
Ship Date	Date when the order was shipped
Ship Mode	Shipping method
Customer Name	Name of the customer
Segment	Market segment (Consumer, Corporate, Home Office)
Country	Country of sale
City	City of customer
State	State of customer
Region	Region of sale
Category	Product category
Sub-Category	Product sub-category
Product Name	Name of the product
Sales	Sales revenue
Quantity	Quantity sold
Discount	Discount applied
Profit	Profit earned
🛠️ Steps Performed

Import & Explore Data

Loaded CSV file using pandas

Checked shape, column names, and data types

Data Cleaning

Dropped unnecessary columns (Row ID, Postal Code)

Converted Order Date and Ship Date to datetime format

Handled missing values

Data Manipulation with Pandas

Filtering (e.g., orders with Sales > 1000)

Selecting specific columns after filtering

Sorting data by Sales & Profit

Grouping by Region, Category, and Segment

Aggregations (sum, mean of Sales & Profit)

Created a new column: Profit Margin

Analysis Insights

Which categories bring the most profit?

Which region contributes the highest sales?

Which customer placed the most orders?

Which shipping mode is most popular?

📌 Key Learnings

Loading and exploring real-world datasets with pandas

Cleaning and transforming data

Using groupby(), agg(), sort_values()

Creating new calculated fields

Extracting insights using only pandas
