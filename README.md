# SQL_ASSIGMENT_3 – E-Commerce Customer Churn Analysis

📌 Project Overview

This project focuses on MySQL database management, data cleaning, transformation, and customer churn analysis using an e-commerce customer dataset.

The assignment involves creating database tables, handling missing values, standardizing inconsistent data, performing SQL queries, and analyzing customer behavior and churn patterns.

🎯 Objectives

Create and manage an e-commerce database using MySQL.

Clean missing and inconsistent data.

Identify and handle outliers.

Standardize categorical values.

Transform columns using UPDATE, ALTER TABLE, and CASE.

Analyze customer churn, complaints, payment methods, and order behavior.

Perform aggregations, subqueries, and joins.

🛠️ Technologies Used

Database: MySQL

Language: SQL

Concepts: Data Cleaning, Data Transformation, Aggregation, Subqueries, Joins, Conditional Logic

📂 Database Structure

1. customer_churn

Contains customer information, including:

Customer ID and tenure

Preferred login device and payment mode

City tier and warehouse-to-home distance

Gender and marital status

Order count and coupon usage

Satisfaction score and cashback amount

Complaint status and churn status

2. customer_returns

Contains customer return information:

Return ID

Customer ID

Return date

Refund amount

🧹 Data Cleaning and Transformation

The SQL script includes:

Handling missing values through mean imputation.

Identifying and removing records with warehouse-to-home distances above 100.

Standardizing login devices, order categories, and payment methods.

Renaming columns for improved consistency.

Creating ComplaintReceived and ChurnStatus columns.

Removing the original Churn and Complain columns after deriving their descriptive status values.

📊 SQL Analysis Performed

The assignment explores:

Customer churn status distribution.

Average tenure and total cashback for churned customers.

Complaint percentage among churned customers.

Churned customers by city tier for laptop and accessory orders.

Most common payment methods among active customers.

Order amount increases by marital status and product category.

Average registered devices for UPI users.

Customer distribution by city tier.

Coupon usage by gender.

Maximum app usage hours by product category.

Customer satisfaction among customers who complained.

Average cashback by product category.

Customer distance classification.

Married customers in Tier-1 cities whose order counts exceed the overall average.

Customer returns using an INNER JOIN with customer churn data.

🧠 SQL Concepts Practiced

CREATE DATABASE · CREATE TABLE · INSERT · UPDATE · DELETE · ALTER TABLE · CASE · WHERE · GROUP BY · ORDER BY · HAVING · Aggregate Functions · Subqueries · INNER JOIN

▶️ How to Run the Project

Download or clone this repository.

Open the SQL script in MySQL Workbench.

Connect to your MySQL server.

Execute the script to create the database, insert the data, perform cleaning operations, and run the analysis queries.

Review the query results in MySQL Workbench.

File: SQL ASSIGMENT 3.sql

Note: The script begins by dropping and recreating the ecomm database. Back up any existing database with that name before running it.

📚 Learning Outcomes

Improved understanding of MySQL syntax and database operations.

Practical experience cleaning and transforming customer data.

Ability to use aggregate functions, conditional expressions, and subqueries.

Experience combining related tables using joins.

Improved ability to answer business questions using SQL.

Project Type: SQL Assignment
Domain: E-Commerce Analytics
Database: MySQL
AUTHOR: TS MUHAMMED NABEEL
