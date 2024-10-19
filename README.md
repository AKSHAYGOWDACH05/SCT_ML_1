# SCT_ML_1
# House Price Prediction using Linear Regression

This project demonstrates how to use linear regression for predicting house prices based on various features such as area, number of bedrooms, age of the house, and more. It is implemented using Python and employs the `scikit-learn` library for building the regression model.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Description](#model-description)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction

The primary objective of this project is to predict the price of houses using historical data. Linear regression is a statistical method that models the relationship between a dependent variable (house price) and one or more independent variables (house features).

This project serves as an introduction to basic machine learning regression techniques, where we focus on building a model that fits a linear equation to observed data.

## Dataset

The dataset used for training the model contains features commonly associated with real estate pricing such as:

- **Lot Area**: Total area of the house lot.
- **Number of Bedrooms**: Total number of bedrooms.
- **Year Built**: The year when the house was constructed.
- **Total Rooms**: Total number of rooms excluding bathrooms.
- **Garage Area**: Area of the garage in square feet.
- **Sale Price**: The final selling price of the house (target variable).

The dataset can be found in the `data/` directory.

## Features

Key features in the dataset include:

- **Lot Area**: The size of the house's lot in square feet.
- **Bedrooms**: Number of bedrooms.
- **Bathrooms**: Number of bathrooms.
- **Garage Area**: Size of the garage.
- **Year Built**: Year the house was constructed.
- **Sale Price**: The target variable, which is the price of the house.

## Requirements

This project is built using Python 3 and the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `seaborn`

You can install all the required libraries by running the following command:

```bash
pip install -r requirements.txt
