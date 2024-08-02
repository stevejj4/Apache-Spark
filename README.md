# Welmart Sales Insights Project

## Overview

This project involves analyzing sales data from Welmart, a wholesale store operating nationwide in the United States. The goal is to gain insights into sales patterns across different customer segments and regions using PySpark. The analysis aims to assist Welmart in improving inventory management, optimizing delivery logistics, and tailoring marketing strategies based on data-driven insights.

## Project Structure

The project is organized into multiple Jupyter notebooks, each focusing on a specific aspect of the analysis:

1. **Notebook 1: Data Ingestion and Cleaning**
   - Loads data from Google Sheets into a Spark DataFrame.
   - Cleans and preprocesses the data by converting columns to appropriate data types.

2. **Notebook 2: Determine the Best-Selling Product Sub-Category**
   - Identifies the product sub-category with the highest total quantity sold.

3. **Notebook 3: Identify the Product Category Generating the Highest Revenue**
   - Determines the product category with the highest total revenue.

4. **Notebook 4: Compile a Top 10 List of the Most Valuable Customers**
   - Generates a list of the top 10 customers based on total sales.

5. **Notebook 5: Determine the State Responsible for the Highest Number of Orders**
   - Finds the state with the highest number of orders.

6. **Notebook 6: Find the Year with the Highest Revenue Generation**
   - Identifies the year with the highest total revenue.

## Setup and Requirements

1. **Google Colab or Local Environment:**
   - Ensure you have access to Google Colab or a local Spark environment.

2. **Dependencies:**
   - PySpark
   - gspread
   - google-auth
   - pandas (if using local environment)

3. **Data Source:**
   - The dataset is sourced from a Google Sheets document named "Superstore".

## Usage

1. **Authenticate with Google Colab:**
   - Run the data ingestion and cleaning notebook to authenticate and load the data.

2. **Execute Notebooks Sequentially:**
   - Run each notebook in sequence to perform the analysis tasks.

3. **View Results:**
   - Results will be displayed directly in the notebooks.

## Contribution

Feel free to contribute to this project by opening issues or submitting pull requests. For any questions, contact the project maintainer.

## License

This project is licensed under the MIT License. 

