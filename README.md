# Dataware_house_SQL_Project
# SQL Data Warehouse Project

## Overview
This project demonstrates a **simple SQL-based data warehouse** built using a layered architecture.  
The goal is to show how raw data can be ingested, cleaned, and transformed into analytics-ready tables using SQL.

---

## Architecture
The project follows a simplified **Medallion Architecture**:

### Bronze Layer
- Raw data loaded from CSV files
- No transformations applied

### Silver Layer
- Data cleaning and standardization
- Handles null values and duplicates

### Gold Layer
- Business-ready tables
- Fact and dimension tables
- Analytical views for reporting

---

## Tech Stack
- SQL Server
- SQL Server Management Studio (SSMS)
- Git & GitHub

---

## Project Structure
<img width="787" height="542" alt="Data architecture diagram drawio" src="https://github.com/user-attachments/assets/50ecf174-4350-4d0c-a460-21c0f9dd1f88" />
