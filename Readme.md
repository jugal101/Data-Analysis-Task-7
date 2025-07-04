# Sales Data Analysis with SQLite and Python

## Overview
This project demonstrates how to connect Python to an SQLite database, run SQL queries to analyze sales data, and visualize the results using matplotlib. It was created as part of a Data Analyst Internship Task.

## Features
- Creates a sample SQLite database with sales data if one doesn't exist
- Runs SQL queries to calculate:
  - Total quantity sold by product
  - Revenue by product (quantity × price)
  - Overall sales totals
- Displays results in a formatted table
- Generates a bar chart visualization of revenue by product

## Prerequisites
- Python 3.x
- Required Python packages:
  - `sqlite3` (built into Python)
  - `pandas`
  - `matplotlib`

## Installation
1. Clone this repository
2. Install required packages:
   ```bash
   pip install pandas matplotlib