# Phone Store Database Management System

## Overview
This repository contains the SQL scripts and database design for managing a mobile phone store's operations. Developed as a group project for SQL Based Data Architectures II, this project includes scripts for database creation, data insertion, and complex queries to answer business-critical questions.

## Database Design
The database is structured to manage mobile phone inventory, sales transactions, and payment processing. It incorporates a variety of tables like `Inventory`, `Supplier`, `Phone`, `Customer`, `Payment_Info`, and many more, linked through well-defined relationships ensuring data integrity and normalization up to the third normal form (3NF).

### ER Diagram
<img width="668" alt="Screenshot 2024-05-06 at 16 06 07" src="https://github.com/jessih828/SQL_DBManagementSystem/assets/147946414/2a6b640d-5080-4584-93d1-2006fd3c4834">

## Project Structure
- `createtables.sql`: Scripts for creating all the database tables.
- `insert_data.sql`: Scripts for populating the tables with initial data.
- `analytics.sql`: Contains complex SQL queries to extract meaningful insights from the data, addressing specific business questions.
