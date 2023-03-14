# Career Foundry - Rockbuster Stealth Data Analysis
This repository contains SQL queries related to the project "Rockbuster Stealth Data Analysis".

The project was part of the Data Analytics program I attended at Career Foundry.

All queries have been written and run on **PostgreSQL**.

## Project overview:
Rockbuster stealth is a fictional movie rental company, that used to have stores all over the world. Because of competition from streaming services (Netflix, Amazon and so on), the management team is planning to launch an online video rental service to stay competitive.

My goal, as a data analyst, was to analyze the data within the company relational database management system and help with the launch strategy.

Stakeholders needed data-driven answers for some **key questions** related to movies, revenue and customers, such as:
- which movies contributed the most/least to revenue gain?
- what was the average rental duration for all videos? 
- which countries are Rockbuster customers based in? 
- where are customers with a high lifetime value based? 
- do sales figures vary between geographic regions?

The answers to these questions were provided in a **Power Point presentation** that you can find in the repository or by clicking [here](https://github.com/SimoneCalabro/Career-Foundry---Rockbuster-Stealth-Data-Analysis/blob/main/3.%20Final%20Presentation.pdf).

## Contents:
The repository contains:

- **1. Rockbuster ERD:** The Entity Relationship Diagram of Rockbuster Database.
- **2. Data dictionary:** Dictionary containing all necessary informations of database's tables.
- **3. Final presentation:** My final presentation (Power Point) containing charts and answers to the project's key questions.
- **4. Queries:** A collection of some of the queries I wrote to extract data from the database.

## Database:
Rockbusters' database is made of 15 different tables, in relationship between each other through primary keys and foreign keys.

Tables contain information about film inventory, customers and payments, among other things.

For a complete overview of the database structure, please check the [Entity Relationship Diagram](https://github.com/SimoneCalabro/Career-Foundry---Rockbuster-Stealth-Data-Analysis/blob/main/1.%20Rockbuster%20ERD.png) contained in the repository.

## Data dictionary:
Need extra information about Rockbuster Database?

Please refer to the [Data dictionary](https://github.com/SimoneCalabro/Career-Foundry---Rockbuster-Stealth-Data-Analysis/blob/main/2.%20Data%20dictionary.pdf) I created.

There you will find a detailed overview of every table, containing:

- Primary and foreign keys
- Columns' names
- Columns' datatypes
- Columns' description
- Columns it links to
- Columns it links from

## Datasets:
[Rockbuster Database](https://www.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip)

## Tools:
- PostgreSQL
- Tableau

## Queries:

- **Query 1:** Data summary example - (a table data summary using descriptive statistics)
- **Query 2:** Joining tables (with subquery) - (joining tables and using a subquery to extract the top 10 cities within the top 10 countries)
- **Query 3:** Common Table Expressions - (using two CTE to create a more complex query)

## Skills:
A summary of what I applied during the project:

- Cleaning data:
  - Checking and handling duplicates
  - Checking and handling non-uniform data
  - Checking and handling incorrect or missing data
- CRUD operations (Create, Read, Update, Delete)
- Aliasing
- Ordering and grouping data
- Aggregating data (COUNT, MAX, MIN, SUM, AVG)
- Sorting and limiting data
- Filtering data with WHERE (+ operators: BETWEEN, NOT, OR, IN, LIKE) and HAVING clause
- Using CASE statements
- Creating a VIEW
- Joining tables
- Creating subqueries
- Creating common table expressions

## Resources:
[My tableau profile](https://public.tableau.com/app/profile/simone.calabro) (contains interactive visualizations used to answer key questions)
