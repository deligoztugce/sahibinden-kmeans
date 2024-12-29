# sahibinden-lineerregression
# Data Analysis and Machine Learning for Various Datasets

## Overview
This repository contains various data analysis and machine learning projects focused on exploring different datasets and performing clustering, regression, and prediction. The projects involve:

1. **Car Data Analysis** (`reno_clio.csv`): Clustering cars based on their age and mileage.
2. **Customer Analysis** (`lineer regresyon - Sayfa1.csv`): Exploring customer spending and income data using clustering and regression.
3. **Customer Spending Prediction** (`müşteri_bilgileri.csv`): Building a linear regression model to predict spending based on income.
4. **Disease Rate Prediction** (`hastalık_oranı.csv`): Analyzing COVID-related data and making predictions.

## Project Details

### 1. Car Data Analysis (`reno_clio.csv`)
This dataset contains information about cars, including their year of manufacture (`yıl`) and mileage (`km`). The analysis includes:
- Calculating the age of each car.
- Visualizing the relationship between age and mileage.
- Using K-Means clustering to group cars based on their age and mileage.
- Classifying cars as "old", "new", etc., based on their clusters.

### 2. Customer Analysis (`lineer regresyon - Sayfa1.csv`)
This dataset contains customer information, including their income (`gelir`) and spending (`harcama`). The analysis involves:
- Calculating the average spending per customer.
- Visualizing the relationship between income and spending.
- Using K-Means clustering to group customers based on their income and spending behavior.
- Building a linear regression model to predict customer spending based on their income.

### 3. Customer Spending Prediction (`müşteri_bilgileri.csv`)
This dataset contains customer spending behavior data. The analysis involves:
- Building a linear regression model to predict spending based on income.
- Visualizing the linear regression model's prediction against the actual data.
- Using K-Means clustering to group customers based on income and spending.

### 4. Disease Rate Prediction (`hastalık_oranı.csv`)
This dataset contains data on the total population and the rate of disease (`cyüzdesi`). The analysis involves:
- Visualizing the relationship between total population and disease percentage.
- Using linear regression to predict the total population based on disease percentage.

## Libraries Used

- **pandas**: For data manipulation and analysis.
- **matplotlib**: For data visualization.
- **sklearn**: For machine learning, including clustering (KMeans) and linear regression.

## Installation

To install the required libraries, use the following command:

```bash
pip install pandas matplotlib scikit-learn
