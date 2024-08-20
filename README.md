#  Project

This project is a comprehensive analysis of personal financial transactions. It uses SQL queries to gain insights into spending patterns, budgeting, and overall financial health based on transaction data.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [SQL Scripts](#sql-scripts)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Personal Finance Analysis Project allows you to analyze your personal finances by using SQL scripts to query transaction data stored in a database. The analysis includes summaries of spending by category, month, and year, comparisons against budgeted amounts, and identification of trends over time.

## Features

- **Number of Records**: Retrieves the number of records in the budget and transaction tables.
- **Monthly Transactions Summary**: Displays the total number of transactions by month for each year.
- **Category Summary**: Shows distinct categories present in the transactions and budget tables.
- **Annual Spending**: Summarizes the total money spent per year.
- **Descriptive Analysis**: Provides statistical measures such as maximum, minimum, standard deviation, and variance of amounts spent by category.
- **Top Spending Categories**: Lists the top five spending categories based on transaction data.
- **Spending vs. Budget**: Compares actual spending against budgeted amounts on a monthly basis.
- **Outspent Categories**: Identifies categories where spending exceeded the budget.

## Setup

To set up the project on your local machine:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    ```
2. **Database Setup**:
    - Ensure you have a SQL Server database set up with two tables: `dbo.Budget` and `dbo.personal_transactions`.
    - Import your transaction data into the `dbo.personal_transactions` table.
    - Import your budget data into the `dbo.Budget` table.

3. **Import SQL Scripts**:
    - Use SQL Server Management Studio (SSMS) or any other SQL editor to run the provided SQL scripts against your database.

## Usage

To perform the analysis:

1. **Run SQL Queries**: 
    - Open the SQL scripts provided in the `/sql` folder.
    - Execute each script against your database to get insights on different aspects of your personal finances.

2. **Analyze Results**:
    - Review the output of each query to understand your spending patterns, compare against your budget, and identify areas for improvement.

## SQL Scripts

- **`01_Number_of_Records.sql`**: Counts the number of records in the Budget and Personal Transaction tables.
- **`02_Total_Transactions_By_Month.sql`**: Summarizes the total number of transactions by month for 2021 and 2022.
- **`03_Total_Categories.sql`**: Displays distinct categories in both transaction and budget tables.
- **`04_Annual_Spending.sql`**: Summarizes total money spent per year.
- **`05_Descriptive_Analysis.sql`**: Provides a descriptive analysis of spending by category.
- **`06_Printing_Budget.sql`**: Outputs all data from the Budget table.
- **`07_Spending_By_Month.sql`**: Shows spending by month, comparing 2021 and 2022.
- **`08_Spending_By_Card_Type.sql`**: Summarizes spending by card type.
- **`09_Income_Versus_Spending_By_Month.sql`**: Compares income versus spending by month.
- **`10_Spending_By_Category.sql`**: Summarizes spending by category for each year.
- **`11_Top_Five_Spending_Categories.sql`**: Lists the top five spending categories.
- **`12_Category_Wise_Monthly_Spending_Compared_To_Budget.sql`**: Compares monthly spending against budget by category.
- **`13_Outspent_Categories.sql`**: Identifies categories that have outspent their budget.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request.



