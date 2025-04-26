# Coffee Sales Analysis Project

## Problem Statement

The goal of this project is to analyze coffee sales from a vending machine and discover customer purchasing patterns, sales trends, and product popularity. The project also builds a simple machine learning model to predict sales using historical data.

## Dataset Description

The dataset contains detailed records of coffee sales from a vending machine.  
It spans from March 2024 to July 2024, capturing daily transactions.  

The dataset columns include:
- Date
- Datetime
- Cash Type (Card or Cash)
- Card ID (anonymized)
- Money (amount spent)
- Coffee Name

## Tools and Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

### 1. Data Collection
- Loaded the coffee sales dataset using pandas.

### 2. Data Preparation and Cleaning
- Checked and handled missing values.
- Converted `date` and `datetime` columns to datetime format.
- Created new columns: `Month`, `Day`, `Hour` from the date and time.
- Removed outliers using Z-score method.

### 3. Exploratory Data Analysis (EDA)
- Analyzed transaction volume by payment type.
- Explored product popularity and customer preferences.
- Visualized total revenue by coffee type.
- Studied monthly and daily sales trends.
- Analyzed weekly and hourly sales patterns.
- Identified peak hours and best-selling products.

### 4. Machine Learning Modeling
- Prepared features and target variable.
- Applied One-Hot Encoding to categorical features.
- Split the data into training and testing sets.
- Trained a Linear Regression model to predict sales.
- Evaluated the model using Mean Squared Error and R-squared score.

### 5. Model Interpretation and Conclusion
- Interpreted model coefficients to understand feature impacts.
- Identified major factors influencing coffee sales.

## Results and Key Insights

- Around 92 percent of transactions were card-based.
- Americano with Milk and Latte were the most popular coffee products.
- Sales peaked around 10:00 AM and again around 7:00 PM daily.
- Tuesday had the highest overall sales compared to other days.
- Latte contributed the highest revenue among all coffee types.
- Simple Linear Regression provided a basic sales prediction model.


