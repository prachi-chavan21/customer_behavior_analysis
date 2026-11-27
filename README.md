# Customer Shopping Behavior Analysis

## About the Project

I worked on this project to understand customer shopping behavior and identify useful insights from customer purchase data. The dataset contains 3,900 transactions with information about customer demographics, products, purchase amounts, discounts, subscriptions, shipping types, and ratings.

I used Python for data cleaning and exploratory data analysis, PostgreSQL for SQL-based analysis, and Power BI to create an interactive dashboard.

The main goal was to understand customer preferences, purchasing patterns, revenue trends, and customer segments.

## Dataset

The dataset contains 3,900 rows and 18 columns.

It includes information such as:

- Customer age, gender, and location
- Product name and category
- Purchase amount
- Season, size, and color
- Review rating
- Subscription status
- Discount and promo code usage
- Previous purchases
- Purchase frequency
- Shipping type

There were 37 missing values in the Review Rating column.

## Tools Used

- Python – Data analysis and cleaning
- Pandas & NumPy – Data manipulation
- Matplotlib & Seaborn – Data visualization
- PostgreSQL – Database management
- SQL – Business analysis
- Power BI – Dashboard creation
- Jupyter Notebook – Python analysis
- Gamma – Project presentation

## Work Performed

### Python

I loaded the dataset using Pandas and performed initial exploration to understand the data structure, columns, data types, and statistical information.

I checked missing values, analyzed numerical and categorical columns, and cleaned the dataset before performing further analysis.

### Data Cleaning

- Handled missing review ratings using the median rating of each product category.
- Standardized column names into snake_case.
- Checked duplicate and redundant information.
- Removed the promo_code_used column after checking its redundancy with discount_applied.
- Prepared the dataset for further analysis.

### Feature Engineering

I created additional columns to make the analysis more useful:

- age_group – Categorized customers based on age.
- purchase_frequency_days – Converted purchase frequency into a numerical format.

### SQL Analysis

I connected Python with PostgreSQL and imported the cleaned data into the database.

Using SQL, I analyzed:

- Revenue by gender
- Customers using discounts with above-average spending
- Top-rated products
- Average purchase amount by shipping type
- Subscribers vs. non-subscribers
- Products with high discount dependency
- Customer segmentation
- Top products in each category
- Repeat buyers and subscription behavior
- Revenue by age group

## Power BI Dashboard

I created an interactive Power BI dashboard to present the results of my analysis.

The dashboard includes:

- Total customer metrics
- Average purchase amount
- Average review rating
- Subscription analysis
- Revenue by category
- Sales by category
- Revenue by age group
- Sales by age group

I also added interactive filters to explore data by gender, category, subscription status, and shipping type.

## Key Findings

- Male customers generated higher total revenue than female customers in this dataset.
- Non-subscribers contributed more total revenue than subscribers.
- Customers choosing Express shipping had a higher average purchase amount than Standard shipping customers.
- Gloves, Sandals, Boots, Hat, and Skirt were among the highest-rated products.
- Hat, Sneakers, Coat, Sweater, and Pants had relatively high discount dependency.
- Most customers belonged to the Loyal customer segment.
- Young Adult customers contributed the highest revenue among the analyzed age groups.

## Business Recommendations

Based on my analysis, I identified the following opportunities:

- Encourage customers to subscribe through exclusive offers and benefits.
- Improve customer retention through loyalty programs.
- Review discount strategies to balance sales and profitability.
- Promote top-rated and popular products.
- Focus marketing campaigns on high-performing customer segments.
- Evaluate express shipping as an opportunity to improve customer experience.

## How to Run

1. Download or clone this repository.
2. Download and place the dataset in the project folder.
3. Open the Python notebook in Jupyter Notebook or VS Code.
4. Install the required Python libraries.
5. Run the notebook to perform data cleaning and analysis.
6. Create a PostgreSQL database and import the cleaned dataset.
7. Execute the SQL queries provided in the SQL folder.
8. Open the Power BI `.pbix` file to explore the dashboard.

## What I Learned

Through this project, I gained practical experience in data cleaning, exploratory data analysis, feature engineering, PostgreSQL database integration, SQL queries, data visualization, dashboard development, and converting data into meaningful business insights.

---

**Tools:** Python | Pandas | SQL | PostgreSQL | Power BI | Excel
