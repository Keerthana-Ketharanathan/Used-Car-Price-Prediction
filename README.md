# Used-Car-Price-Prediction
Used car price prediction using Regression Machine Learning
# Used Car Price Prediction – Machine Learning

## Project Overview

Used Car Price Prediction is a machine learning regression project developed to predict the price of used cars based on various vehicle features such as make, model, year, kilometers driven, fuel type, transmission, location, engine, power, torque, and other specifications.

The project includes data cleaning, preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and comparison of multiple regression models.

## Dataset

The dataset contains 2,059 used-car records with 20 features.

## Features include:

- Make
- Model
- Price
- Year
- Kilometer
- Fuel Type
- Transmission
- Location
- Color
- Owner
- Seller Type
- Engine
- Max Power
- Max Torque
- Drivetrain
- Length
- Width
- Height
- Seating Capacity
- Fuel Tank Capacity

**Target Variable:** Price

## Analysis Performed

The project analyzes:

- Used car prices
- Car make and model
- Vehicle age/year
- Kilometers driven
- Fuel type
- Transmission type
- Engine capacity
- Maximum power
- Maximum torque
- Drivetrain
- Seating capacity
- Fuel tank capacity
- Numerical and categorical features
- Descriptive statistics
- Feature distributions and skewness

## Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset shape and structure
- Checked data types
- Identified missing values
- Checked duplicate records
- Converted Engine, Max Power and Max Torque into numerical values
- Filled numerical missing values using median
- Filled categorical missing values using mode
- Performed one-hot encoding for categorical variables
- Split the dataset into training and testing sets

## Machine Learning Models

Three regression models were trained and evaluated:

1. Linear Regression
2. Decision Tree Regression
3. Random Forest Regression

## Model Evaluation

The models were evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- Adjusted R²

### Model Performance

| Model | RMSE | R² Score | Adjusted R² |
| Linear Regression | 1,560,726.45 | 0.6513 | 0.4467 |
| Decision Tree | 1,091,894.88 | 0.8293 | 0.7292 |
| Random Forest | 1,151,067.48 | 0.8103 | 0.6990 |

Based on the recorded evaluation results, the Decision Tree model achieved the highest R² score among the three evaluated models.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

## Key Features

- Data cleaning and preprocessing
- Missing value handling
- Duplicate record checking
- Exploratory Data Analysis
- Statistical analysis
- Feature engineering
- One-hot encoding
- Train-test split
- Multiple regression models
- Model performance comparison
- Actual vs. predicted price analysis

## Skills Demonstrated

- Python Programming
- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Statistical Analysis
- Machine Learning
- Regression Modeling
- Model Evaluation
- Model Comparison
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

## Project File

- `Used Car Price Prediction.ipynb` – Complete Jupyter Notebook containing data preprocessing, EDA, model training, evaluation, and comparison.
