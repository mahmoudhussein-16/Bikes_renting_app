# Bike Rental Business Analysis

## Project Overview

This project analyzes the financial and operational aspects of a bike rental business. The goal is to gain insights into profitability and operational efficiency by leveraging data analysis and machine learning techniques. The analysis considers various factors such as rental types, taxes, and maintenance costs.

## Key Features

- **Business Understanding**:

  - Rental cost for casual users: \$10/hour.
  - Rental cost for registered users: \$3/hour.
  - Taxes: 14% of gross income.
  - Maintenance cost: \$2000/year.

- **Data Analysis and Processing**:

  - Data cleaning and preprocessing using libraries like Pandas and NumPy.
  - Exploratory data analysis with Seaborn to visualize trends and relationships.

- **Profit Calculation**:

  - A custom function to calculate net profit per hour based on:
    - Hourly rental revenue.
    - Applicable taxes.
    - Maintenance expenses.

- **Machine Learning Models**:

  - Multiple regression models (Linear Regression, Decision Trees, Random Forest, XGBoost) to predict key metrics and derive insights.

## Technologies Used

- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Seaborn, Scikit-learn, XGBoost
- **Tools**: Jupyter Notebook

## Data

The dataset, `bikes.csv`, includes:

- Rental information for casual and registered users.
- Features influencing rental trends, such as weather conditions and time of day.

## How to Run the Project

1. Clone the repository or download the notebook.
2. Ensure all dependencies are installed. Use the following command to install missing packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run the cells sequentially.
4. Analyze the outputs and visualizations.

## Results and Insights

The analysis provides insights into:

- The impact of user type (casual vs. registered) on revenue.
- Seasonal and hourly trends affecting bike rentals.
- Predictive models for future rental trends and profitability.
