# CalCOFI Regression

## Overview

This project uses the CalCOFI oceanographic dataset to build and compare two regression models:

* Linear Regression
* SGD Regression

The objective is to predict a continuous target variable using oceanographic features and evaluate the performance of both models.

## Dataset

The CalCOFI dataset contains oceanographic and biological measurements collected off the coast of California from 1949 to the present.

The dataset includes features such as:

* Temperature
* Salinity
* Oxygen
* Phosphate
* Silicate
* Nitrate and Nitrite
* Chlorophyll
* Other physical, chemical, and biological measurements

## Workflow

1. Data loading and exploration
2. Data cleaning and handling missing values
3. Exploratory Data Analysis
4. Feature selection
5. Train-test split
6. Feature scaling
7. Linear Regression
8. SGD Regression
9. Model evaluation and comparison

## Evaluation Metrics

The models are evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset Source

CalCOFI — California Cooperative Oceanic Fisheries Investigations

http://calcofi.org/about-calcofi.html
