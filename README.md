🎬 MavenMovies SQL Data Analysis Project
📌 Overview

This repository contains a comprehensive SQL-based data analysis project built on the MavenMovies (Sakila-inspired) database. The project demonstrates practical SQL skills including data retrieval, joins, aggregations, subqueries, and data manipulation.

The goal of this project is to explore and analyze a movie rental database to extract meaningful insights about films, customers, rentals, and business operations.

🗄️ Dataset Description

The dataset is based on the Sakila sample database, which simulates a DVD rental business.
It includes multiple relational tables such as:

film – movie details (title, rental rate, release year, etc.)
customer – customer information
rental – rental transactions
inventory – stock of films
category – film categories
payment – payment details
staff – store employees

The schema is fully normalized and uses foreign keys to maintain relationships between tables.

📊 Analysis Covered

The SQL analysis file includes a wide range of queries, progressing from basic to advanced concepts:

🔹 Basic Queries
Retrieve all films
Filter films by release year
Search films by title patterns
Get distinct categories

🔹 Sorting & Filtering
Order films by rental rate
Filter categories based on count

🔹 Joins
Customer rentals with film titles
Staff and pending rentals
Left joins to include customers with no rentals

🔹 Aggregations
Number of films per category
Total rentals per film
Average payment per customer
Customer count by category

🔹 Subqueries
Customers who rented a specific film
Second highest rental rate film

🔹 Data Manipulation (DML)
Update rental rates
Delete rental records

🔹 Advanced SQL Concepts
CASE statements for rental status
UNION operations
CROSS JOIN usage

All queries are written in a structured manner for learning and demonstration purposes.

