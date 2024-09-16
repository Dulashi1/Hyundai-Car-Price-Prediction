# Hyundai-Car-Price-Prediction
"A machine learning model for predicting Hyundai car prices."
# Project Overview
The goal of this project is to develop a predictive model that can estimate the price of a car based on various features such as the car's manufacturer, model, production year, engine specifications, and other attributes. This model can assist car dealerships and car dealers in determining competitive prices for vehicles based on their features.
# Dataset
The dataset used for training the model contains the following key features:

Manufacturer: The brand of the car (e.g., Toyota, BMW, etc.)
Model: The specific model of the car
Prod. year: The year of production
Category: The type of car (e.g., SUV, Sedan, Hatchback)
Mileage: The number of miles the car has been driven
Fuel type: The type of fuel used by the car (e.g., Petrol, Diesel, etc.)
Engine volume: The volume of the car’s engine in liters
Cylinders: The number of cylinders in the engine
Gear box type: The type of transmission (e.g., Manual, Automatic)
Drive wheels: The drivetrain (e.g., Front-wheel, Rear-wheel, All-wheel drive)
Leather interior: Whether the car has leather interiors or not
Airbags: The number of airbags
Levy: A tax applied to certain types of vehicles (has missing values)
# Columns excluded for modeling:

ID
Levy
Handling Missing Data
Levy: Missing values represented by - were handled by replacing them with the median or mode, based on the data distribution.
# Modeling
The machine learning pipeline includes the following steps:

Data Preprocessing:

Dropping irrelevant columns such as ID, Levy.
Handling missing values, particularly in the Levy column
Encoding categorical features using techniques like one-hot encoding
Scaling the numerical features to normalize the data
# Model Training:

A combination of models was tested including Linear Regression and Random Forest.
The final model used is  Random Forest.
The dataset was split into training and test sets, using an 80-20 split.
# Evaluation:

Metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE) were used to evaluate model performance.
