Overview

This project focuses on optimizing retail pricing using data analysis and machine learning techniques. It explores the relationships between unit price, quantity, competitor prices, and product scores to predict total retail prices accurately.

Features

Data preprocessing and exploratory data analysis (EDA)

Visualization of price distributions, box plots, and scatter plots

Calculation of competitor price differences

Machine learning model (Decision Tree Regressor) for retail price prediction

Performance evaluation using mean squared error and visual comparison

Dataset

The script uses a CSV file named retail_price.csv, which includes the following key columns:

qty: Quantity of the product sold

unit_price: Price per unit of the product

comp_1: Competitor's price for the product

product_score: Score assigned to the product

total_price: Total price of the transaction

Installation

Prerequisites

Ensure you have Python installed along with the following dependencies:

pip install pandas plotly scikit-learn

Usage

Place retail_price.csv in the same directory as the script.

Run the Python script:

python retail_price_optimization.py

The script will generate various plots and display them interactively.

It will train a Decision Tree Regressor and compare actual vs. predicted prices.

Visualization

The script generates:

A histogram of total price distribution

A box plot of unit prices

A scatter plot showing quantity vs. total price with a trendline

A bar chart of average competitor price differences by product category

A scatter plot comparing predicted and actual retail prices

Model Performance

The Decision Tree Regressor is trained on a subset of the data and evaluated using mean squared error. A scatter plot is used to visualize the predicted vs. actual prices.

Contributing

Feel free to fork this repository, submit pull requests, or report issues for improvements.

License

This project is licensed under the MIT License.

Author

Developed by Irffanaa Asssmi K
