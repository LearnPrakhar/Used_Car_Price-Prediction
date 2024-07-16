# Used Car Price Prediction

This repository contains code and a Jupyter notebook for predicting the prices of used cars using machine learning algorithms. The dataset used in this project includes various features of cars such as mileage, engine size, power, and more.

## Project Overview

This project involves the following steps:
1. **Data Loading**: Loading the dataset from a CSV file.
2. **Data Preprocessing**: Handling missing values, converting data types, and encoding categorical variables.
3. **Exploratory Data Analysis (EDA)**: Visualizing the distribution of features and their relationships with the target variable (price).
4. **Feature Engineering**: Scaling the features for better model performance.
5. **Model Training and Evaluation**: Training and evaluating Linear Regression and Random Forest Regressor models.

## Dataset

The dataset used for this project is `carsdataset.csv`. The dataset includes the following columns:
- `Name`: Name of the car.
- `Year`: Year of manufacture.
- `Kilometers_Driven`: Total kilometers driven by the car.
- `Fuel_Type`: Type of fuel used by the car (Petrol, Diesel, etc.).
- `Transmission`: Type of transmission (Manual, Automatic).
- `Owner_Type`: Type of ownership (First Owner, Second Owner, etc.).
- `Mileage`: Mileage of the car (in kmpl or km/kg).
- `Engine`: Engine capacity (in CC).
- `Power`: Power of the car (in bhp).
- `Seats`: Number of seats in the car.
- `Price`: Price of the car (target variable).

## Requirements

To run the code in this repository, you need the following Python libraries:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using the following command:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
