
# Flight Deployment Price Prediction

This project uses machine learning algorithms to predict the prices of flight deployments. The machine learning model is trained on historical flight prices, and the Flask web application provides a user interface to enter inputs and get price predictions.


## Overview

<img src = "C:/Users/tusha/Desktop/Flight%20Price%20Predict%20Project/Flight_Deployment/templates/index.html">


## Table of Contents

- Project Description

- Skills Used

- Installation

- Usage

- Data

- Model

- Flask Web Application

- Results



## 🛠 Skills
This project requires knowledge of several skills, including:

- Python : Used to write the machine learning algorithms and the    Flask web application.

- Machine Learning Algorithms : Used to train the model and predict the flight prices.

- Data Cleaning and Preprocessing : Used to clean and preprocess the data before using it to train the machine learning model.

- Flask Web Development : Used to develop the web application that provides the user interface for the price prediction.

- HTML/CSS : Used to design the user interface for the Flask web application.
 
 Python, Machine learning algorithms , Pandas , Numpy , Matplotlib , Sklearn , HTML , CSS , Flask .


## Installation

To use this project, you need to install some packages, including pandas, numpy, matplotlib, scikit-learn, and Flask. You can install these packages using the following command:

```bash
  pip install pandas numpy matplotlib scikit-learn Flask

```
    
## Usage

Using this project is very simple. You just need to run the 'app.py' file and input your desired departure date, destination, and the number of passengers. The model will then generate a predicted price for your flight deployment.


## Data

This project collects data from various online sources such as flight booking websites and airline company websites. I have cleaned and preprocessed the data before using it to train the machine learning model.

Collected data from various airlines' websites and flight booking websites, which included the following features:

- Source
- Destination
- Arrival Airport
- Depature Airport
- airline
- Stopage


## Model 

Have used a random forest regression and Catboost regressor  model for this project. This model is capable of handling non-linear relationships and can handle missing data. The model is trained on the flight data collected from various sources.

We split the data into a training set and a testing set. The model was trained on the training set, and we used the testing set to evaluate the model's accuracy. The model has achieved an accuracy of 83% in predicting flight prices based on the test set.

## Flask Web Application

The Flask web application provides a user-friendly interface to enter inputs and get price predictions. I have used HTML/CSS to design the web interface and Flask to handle the back-end functionality.

The web interface is simple and easy to use. You just need to input the departure date, departure airport, arrival airport, and the number of passengers. The model will then generate a predicted price for your flight deployment.

## Result

The model has achieved an accuracy of 83% in predicting flight prices based on the test set of data
