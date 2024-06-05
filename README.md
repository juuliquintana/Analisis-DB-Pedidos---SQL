# Orders DB Analysis - SQL

This project is an implementation of a database for a fast-food restaurant. The database includes the main orders table and other tables such as products, employees, delivery personnel, among others. The primary objective is to answer a series of questions proposed by the chair using MySQL queries integrated in Python.

For each question, the solution involved creating a DataFrame and a .csv file, which can be viewed in the csv folder.

---

## Database

The database used is about the orders of a restaurant, which employees were involved in them, and the products. It is composed of a main orders table, which is normalized and linked to the rest of its tables via PK-FK, resulting in the following entity-relationship diagram:

![alt text](image.png)

## Project Structure
 - *Data Analysis*: The primary focus is on answering analytical questions about the orders.
 - *MySQL Queries*: Queries are written in MySQL and integrated with Python for data extraction and manipulation.
 - *DataFrames and CSVs*: Each query result is stored in a DataFrame and exported to a CSV file for further analysis and visualization.

## How to Use
- Setup: Ensure you have Python and MySQL installed on your system.
- Database: Import the database schema and data into your MySQL server.
- Scripts: Run the Python scripts to execute the MySQL queries and generate the CSV files.
- Analysis: Review the CSV files in the csv folder for insights. 


This project is part of a Data Analyst Bootcamp at Upgrade Hub.