# Optimizing Courier Costs: Analyzing Delivery Partner Charges for Accuracy

## Overview
🚚 This project aims to optimize courier costs by analyzing the charges levied by delivery partners for the delivery of products. The goal is to verify the reason for higher charges imposed by courier companies and to create an Excel sheet containing specific dataset information.

## Business Problem
📦 The client, an ecommerce company in India (referred to as X), receives a large volume of orders daily and relies on multiple courier companies for deliveries. The charges imposed by these courier companies are influenced by two factors: the weight of the product and the distance between the warehouse and the customer's delivery address. With approximately 1,00,000 orders per month, X incurs substantial costs, prompting them to verify the accuracy of charges levied by their delivery partners per order.

## Steps Involved
1. **Importing Dependencies:** 📊 Importing necessary libraries such as pandas, numpy, datetime, and pandas_datareader for data analysis.
2. **Dataset Description:** 🗂️ Describing the dataset, which consists of five Excel sheets containing various information related to orders, pincode zones, SKU master, courier company invoices, and courier rates.
3. **Loading Dataset:** 📑 Loading data from each Excel sheet into pandas DataFrame.
4. **Exploratory Data Analysis (EDA):** 🔍 Performing data cleaning, transformation, and merging of datasets to analyze the relationship between order details, pincode zones, and courier charges.
5. **Result Analysis:** 📊 Calculating expected charges based on weight slabs and comparing them with billed charges to identify discrepancies. Summarizing results in Excel sheets for further analysis and decision-making.

## Documentation Steps
1. **Project Initialization:** 🚀 Importing necessary libraries and setting up the project environment.
2. **Dataset Description:** 📋 Providing an overview of the dataset structure and contents.
3. **Loading Dataset:** 💾 Reading data from Excel files into pandas DataFrames.
4. **Exploratory Data Analysis (EDA):** 🔍 Cleaning, transforming, and merging datasets to perform analysis.
5. **Result Analysis:** 📈 Calculating expected charges, comparing with billed charges, and summarizing results.

## Folder Structure
- `data/`: Contains Excel sheets with dataset information.
- `README.md`: Overview and documentation of the project.
- `Final_Result.xlsx`: Excel file containing the final analysis results.

## Getting Started
1. Clone the repository.
2. Ensure Python and required dependencies are installed.
3. Open the Jupyter Notebook or Python script to run the analysis.

## Author
- Prakhar Tripathi

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
