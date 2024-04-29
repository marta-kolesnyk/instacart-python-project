# Instacart Grocery Basket Analysis

## Overview:
This project was focused on Instacart - an online grocery store that operates through an app. The company already had good sales, but they asked to uncover more information about their operations.

## Objective:
Provide information about company’s sales patterns and criteria for customer segmentation that can be used for developing a new marketing campaign.

## Key Questions:
- What are the busiest days and hours of the week in terms of number of orders?
- Are there particular times of the day when people spend more money?
- Make simpler price range groupings for products.
- Are certain types of products more popular than others?
- Are there differences in ordering habits based on a customer’s loyalty status and region?
- Is there a connection between age and family status in terms of ordering
habits?

## Data Used:
1. “The Instacart Online Grocery Shopping Dataset 2017”, 
Accessed from www.instacart.com/datasets/grocery-shopping-2017 via Kaggle.
It includes a list of products, departments, and amount of items sold.
2. Customers dataset - fabricated for learning purposes and includes customer age, gender, marital status, and city of living.

## Data Analysis Phases
- All datasets were checked for data consistency and integrity. Unrealistic and duplicate values were removed, while missing values were left, as the records were useful for further analysis. 
- Wrangling steps included dataframe transposing, columns renaming and removal of unneccessary variables.
- Dataframes were merged using a key column.
- New columns were derived, based on multiple conditions. Frequency tables were built to show the distribution of different categories.
- Suitable visualizations were created to easily display different type of information. 

## Insights and Recommendations
- The lowest number of orders come on Wednesdays and Thursdays, from 6 a.m. to 9 a.m. and from 5 p.m. to midnight. Marketing team should consider scheduling ads for this time.
- Customers spend the most money per one product in the early morning, from 4 a.m. to 6 a.m. The lowest spendings are within 9-11 a.m.
- The most popular products were from the next departments: produce, dairy and eggs,  snacks,  beverages, frozen, and pantry. Offering exclusive discounts for these products might attract more customers.
- Meat and seafood products are on average twice as expensive as other products. This category is ordered less frequently but provides roughly 5 % of the company's income.
- More than half of all customers are new customers. They spend slightly more per product than the other groups, but generate the lowest income as they place fewer orders. The loyal group is the smallest - less than 10 %.  Loyal customers spend on average less money per product and bring in almost one-third of the income. Regular customers bring in almost half of the income.
- All regions have more low-spending customers than high-spending, and the same type of products are popular across all regions. South region generates the highest income.
- Customers that belong to the low-income group spend on average less per product compared to people with higher income. Customers of different age, income, and family status groups tend to buy the same type of products and place on average the same number of orders.  

## What went well?
- Deriving new variables was beneficial, as it helped to make such a large dataset easier to analyze by assigning labels (such as customers loyalty group, price range) to the records and building visualizations based on the new variables.
- Learning how to create subset dataframes allowed to work with smaller pieces of data, which speeded up the computation and made it easier to answer business questions.

## Challenges
Learning how to build the appropriate charts was challenging for me. Also, taking into consideration the size of the dataset, it was time-consuming to make a single graph, as this required more computing power from my computer.

## Project Deliverables:
- Excel report with documented data cleaning process, visualizations and recommendations
- Jupyter Notebook Scripts
