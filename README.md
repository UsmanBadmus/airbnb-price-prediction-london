# airbnb-price-prediction-london
MSc Data Science assessment: Airbnb London price prediction using machine learning
# Airbnb London Price Prediction

## Project Overview
This repository contains the code and analysis for an MSc Data Science assessment 
focused on predicting Airbnb listing prices in London. The analysis uses property 
characteristics, location attributes, and guest ratings to build and evaluate 
machine learning regression models.

## Dataset
The dataset includes Airbnb listings from London with variables such as:
- Room type and capacity
- Guest satisfaction and cleanliness ratings
- Geographic coordinates (latitude and longitude)
- Distance to city centre and metro stations
- Engineered accessibility and quality features

## Methods
The analysis includes:
- Exploratory Data Analysis (EDA)
- Feature engineering
- Correlation analysis
- Model development using:
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - XGBoost Regressor
- Model evaluation using R², MAE, and RMSE
- Feature selection using Recursive Feature Elimination (RFE)
- Hyperparameter tuning using GridSearchCV
- Ethical and domain impact analysis

## How to Run the Analysis

### Requirements
The analysis was developed using Python 3 and requires the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

### Steps to Run
1. Clone the repository or download it as a ZIP file.
2. Open the `notebooks/` directory.
3. Launch Jupyter Notebook or JupyterLab.
4. Open `LDS7003M_ASSESSMENT.ipynb`.
5. Run all cells from top to bottom to reproduce the analysis and results.

## Repository Structure
- `notebooks/` – Contains the Jupyter notebook with the full analysis and modelling
- `README.md` – Project documentation
- `.gitignore` – Git ignore configuration

## Author
USMAN BADMUS - MSc Data Science Coursework Submission
