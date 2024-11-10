# Housing Price Regression

Predicting house prices in King County, Seattle, using various regression models. This project includes data preprocessing, feature engineering, and model evaluation with multiple algorithms to achieve accurate predictions.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [License](#license)

## Project Overview

This project aims to predict house prices using machine learning regression models. We explore and analyze house sales data from King County, Seattle, including homes sold between May 2014 and May 2015. The project covers:
- Data preprocessing and feature engineering
- Applying multiple regression algorithms
- Evaluating model performance using metrics like R-squared, MSE, and MAE

## Dataset

The dataset is provided in the `data/kc_house_data.csv` file. It contains various features of houses, such as square footage, number of bedrooms, and location (zipcode).

## Features

Key features used in this analysis include:
- `sqft_living`: Square footage of the home’s interior
- `bedrooms` and `bathrooms`: Number of bedrooms and bathrooms
- `zipcode`: Location identifier
- `age`: Age of the house at the time of sale
- `price_per_sqft`: Price per square foot
- And more...

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/berkaykaratas07/housing-price-regression.git
   cd housing-price-regression
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Open Jupyter Notebook:**
   ```bash
   jupyter notebook notebooks/House-Price-Regression-Models.ipynb
   ```
   
2. **Follow the steps in the notebook to preprocess the data, apply feature engineering, and evaluate the models.**

## Models

The following regression models are implemented and evaluated in this project:

- **Linear Regression**: A simple linear approach to model the relationship between the target and features.
- **Random Forest Regressor**: An ensemble model that uses multiple decision trees to improve prediction accuracy and control overfitting.
- **Gradient Boosting Regressor**: A boosting algorithm that builds models sequentially to correct errors from previous models.
- **XGBoost Regressor**: An optimized gradient boosting algorithm designed to be highly efficient, flexible, and accurate.

Each model is trained on the scaled features and evaluated based on its ability to predict transformed house prices accurately.

## Results

The performance of each model is evaluated using the following metrics:

- **R-squared (R²)**: Measures how well the model explains the variance in the target variable.
- **Mean Squared Error (MSE)**: Measures the average squared difference between actual and predicted values.
- **Mean Absolute Error (MAE)**: Measures the average absolute difference between actual and predicted values.

Results are visualized in the notebook, showing comparisons of true vs. predicted values to assess the models' effectiveness in predicting house prices. These metrics help determine the best-performing model for this dataset.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

