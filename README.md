# car_price_prediction
## Overview
This is an end to end project of machine learning using Kaggle data set.

## Objective
The main aim of this project is to predict the car price based on year of purchase, type of fuel, number of previous owners and transmission type.

## Steps involved:
### Loading data set, exploring and cleaning data:
  1. Obtaining latest data set from [Kaggle](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho/version/3?select=car+data.csv)
  2. Creating a virtual environment
  3. Installing the required libraries
  4. Using jupyter notebook to import the installed libraries, load the data set, explore the data
  5. Cleaning the data and performing one hot encoding on categorical features

#### Exploring_data
![Exploring_data](https://github.com/msna121/car_price_prediction/blob/master/images/Explore.JPG)

#### Missing_data
![Missing_data](https://github.com/msna121/car_price_prediction/blob/master/images/missing_values.JPG)

#### One_hot_encoding
![One_hot_encoding](https://github.com/msna121/car_price_prediction/blob/master/images/one_hot_encoding.JPG)

### Visualizing, feature engineering, feature selection:
  1. Visualizing the data using seaborn and matplotlib
  2. Checking for top correlated features
  3. Checking feature importance
  4. Creating target and input features for training

#### Correlation
![Correlated_features](https://github.com/msna121/car_price_prediction/blob/master/images/top_corr_features.JPG)

#### Feature_importance
![Important_features](https://github.com/msna121/car_price_prediction/blob/master/images/feature_importance.JPG)

### Hyperparameter tuning, predictions and evaluation metrics:
  1. Model creation
  2. Hyperparameter tuning to select optimized values
  3. Predicting the test results
  4. Evaluating the model predictions

#### Hyperparameter_tuning
![Hyperparameter_tuning](https://github.com/msna121/car_price_prediction/blob/master/images/hyperparameter_tuning.JPG)

#### Prediction
![Prediction](https://github.com/msna121/car_price_prediction/blob/master/images/predictions.JPG)

#### Evaluation_metrics
![Evaluation](https://github.com/msna121/car_price_prediction/blob/master/images/evaluation_metrics.JPG)

### API creation and deployment:
  1. Flask is used to create the API
  2. The app.py is deployed on heroku platform ![App_link](https://carpricepredictionmsna.herokuapp.com/)
