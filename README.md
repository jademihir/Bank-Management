# ICICI Bank Management System

## Overview

This project is a management system for ICICI Bank, built using SQL, aimed at organizing and managing bank operations efficiently. The system includes a database with tables for employee details, account details, and other essential banking data. The project showcases the ability to create relational databases, establish foreign keys, and run SQL queries to extract insights.

## Objectives

- Design and implement a relational database system for managing bank operations.

- Organize employee and account data, ensuring data integrity through the use of foreign keys.

- Create SQL queries to perform key operations such as customer account management, transaction history retrieval, and employee information analysis.

## Features

- Employee Details Table: Stores information about employees (e.g., name, position, salary, department).

- Account Details Table: Contains customer account information (e.g., account number, balance, type, branch).

- Foreign Keys: Ensures data integrity by linking employee details to their respective branches, and account details to customers.

- SQL Queries: Includes queries to retrieve relevant data such as customer account details, transaction history, and employee information.

## Technologies


SQL: For creating and managing the database and performing queries.

Database Management System: MySQL or any relational database management system.

## Database Schema


The database consists of the following tables:

- Employees: Stores employee information like ID, name, role, and department.

- Accounts: Stores customer account information, linking each account to the customer.

- Transactions: Keeps track of all banking transactions.

- Branches: Contains details of the bank branches and their locations.

## Key SQL Queries

Query 1: Retrieve all customer accounts linked to a specific branch.

Query 2: Get the transaction history for a given customer.

Query 3: Calculate the total balance in the bank by summing the balances of all account
