# Bike Rental Demand Prediction

A machine learning project using the UCI Bike Sharing dataset to predict daily bike rental demand based on weather and calendar information.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Project Overview

- Cleaned and explored the dataset.
- Analyzed monthly, seasonal, and working-day rental patterns.
- Built three regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Compared model performance using MAE and R².
- Visualized actual vs predicted bike rentals.

## Dataset

**Source:** [UCI Bike Sharing Dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset)

The dataset contains daily bike rental records from Washington, D.C., covering 2011–2012.

## How to Run

1. Download the dataset and extract `day.csv`.
2. Open `Bike_Rental_Demand_Prediction.ipynb` in Google Colab.
3. Upload `day.csv` using the notebook's upload cell.
4. Run all cells in order.

## Limitations

The dataset covers only 2011–2012 bike-sharing activity in Washington, D.C. Model performance may differ for other cities or time periods.
