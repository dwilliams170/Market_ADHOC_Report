
# 🏢 Market Ad-Hoc Analysis

This project involves generating an Ad-hoc report on the NYC-based wholesale food supplier called Osiris-Foods companies database. The task is to  generate a report based on past performances using SQL for queries and Pandas for visualizations to provide an insight to market of the company. 


## Requirements

**Market Database**: The Market.db database is provided, which contains sales and product data for the company.

**SQL**: You will need to write SQL queries to extract the relevant data from the database.

**Python & Pandas**: Use Python for data analysis and Pandas for handling data frames and generating visualizations.

**SQLite3**: This is the recommended database tool for interacting with the database file.
## Installation

Install the following dependencies:
```bash
import sqlite3

import pandas as pd 

import seaborn as sns
import matplotlib.pyplot as plt
```

## Review

Before you beginning the project, please review the ERD Diagram attached under the images folder: 

For this project, you will use the ERD Diagram to formulate how to form your joins across tables and to learn more about your tabl;es columns. 

**Note**: Download `sqlite3` VSCode extension to open your database within your code editor to view the content and columns of your table.   
## Exploratory Data Analysis (EDA)

Key Analytical Questions to analyze your data:

1 ) Which countries have the greatest number of customers? How does this correlate with the number of suppliers by country (i.e. do more customers lead to less or more suppliers)? Which evidence supports your answer?

2) What is the least popular product by order quantity? How does this correlate with revenue (i.e. do less popular products by quantity lead to less or more revenue)? Which evidence supports your answer?

3) Which country has the most orders? How does this correlate with the number of customers who do not order (i.e. do countries with more ordering customers have more or less non-ordering customers)? Which evidence supports your answer?

4) Which supplier has the most orders? Which evidence supports your answer?
## License

[The Knowledge House](https://www.theknowledgehouse.org/) provided the project instructions and raw data for this Ad-Hoc project. 


