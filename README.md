# E-commerce-Sales-Dataset.
E-commerce Sales Dataset with 959 orders and 20 features with target variable 'Total_Sales_NGN, cleaned and feature engineered for predicting sales, revenue and customer analysis all monetary values are in NGN.
# Data Overview.
**Rows** 959
**Columns** 20
**Target Variable**  'Total_Sales_NGN'
# Columns
- Order_ID : unique identifier for each order.
- Customer_ID: unique identifier for each customer.
- Customer_Age: Age of customer.
- Product : Product name.
- Category: Product category.
- Unit_Price_NGN : Price per unit in Nigerian Naira
- Discount: Discount applied as decimal.
- Total_Sales_NGN: Total revenue per order in NGN.
- Order_Date: Date and time of order.
- Payment_Method: Card, TRansfer, Cash etc.
- Location : Customer location / city.
  # Engineered Features
  -Year: year of order
  - Month: Month of order.
  - Day: Day of the Month.
  - Day_of_week: Day of the week
  - Hour: Hour of order
  - Gross_sales: Product of quantity and unit_price_NGN
  - Discount_amount: Product of Gross_sales and Discount/100
    # Data cleaning
    - Corrected categorical data standardization issues.
    - Filled null values with median, others, unknown and zero
    - Filled missing values.
    - Coverted to the appropriate data types
    # Potential use cases:
    - Sales Trend analysis.
    - Product Performance
    - impact of discount analysis.
    - Customer Behaviour
