# In-Class Lab Assignment 6: Neural Networks

**Author:** Zin Min Thant  
**Date:** `r Sys.Date()`  

---

## Project Overview

This project involves building a neural network model to predict car seat sales using a real-world dataset. The goal is to apply neural networks with hyperparameter tuning and 5-fold cross-validation to improve predictive accuracy.

---

## Data Description

The dataset `car_seat_sales.csv` contains information about different stores and factors influencing car seat sales, including:

- **Store:** Unique identifier for each store (excluded from modeling).
- **CompPrice:** Competitor’s price.
- **Income:** Average income of local population (in thousands).
- **Advertising:** Advertising budget (in thousands).
- **Population:** Local population size (in thousands).
- **Price:** Store’s price of the car seat.
- **ShelfLoc:** Quality of shelf location (Good, Medium, Bad).
- **Age:** Average age of local population.
- **Education:** Average years of education of local population.
- **Urban:** Store location urban status (Yes/No).
- **US:** Whether store is in the US (Yes/No).
- **Sales:** Number of car seats sold (target variable, in hundreds).

---

## Project Files

- `Final_Project_Neural_Network.Rmd` — R Markdown file containing the full analysis and code.
- `car_seat_sales.csv` — Dataset for model training.
- `new_car_seat_sales_data.csv` — New data for making predictions with the trained model.

---

## Methodology

- Used the `caret` package in R to train a neural network model.
- Applied 5-fold cross-validation to validate model performance.
- Tuned two hyperparameters:
  - **Size:** Number of neurons in the hidden layer.
  - **Decay:** Regularization parameter to prevent overfitting.
- Predicted sales on new unsee
