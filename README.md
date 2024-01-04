# Taxi-Fare-Guru-Total-Amount-Prediction-Challenge

This repository contains code for a taxi fare prediction challenge. The goal is to predict the total fare amount for taxi rides based on various features such as pickup and dropoff locations, passenger count, and trip duration. The dataset consists of training and test sets, and the analysis includes exploratory data analysis (EDA) and preprocessing steps.

# Key Features
VendorID: Identifier for the taxi provider

tpep_pickup_datetime, tpep_dropoff_datetime: Pickup and dropoff timestamps

passenger_count: Number of passengers

trip_distance: Distance of the trip in miles

RatecodeID: Rate code for the trip

store_and_fwd_flag: Flag indicating if the trip record was held in the vehicle memory

PULocationID, DOLocationID: Pickup and dropoff location IDs

payment_type: Payment method (Credit Card, Cash, Wallet, UPI, unknown)

extra, tip_amount, tolls_amount, improvement_surcharge, congestion_surcharge, Airport_fee: Additional trip details

duration of ride: Calculated duration of the ride in minutes

# Data Analysis and Preprocessing

Explored data distribution for key features

Handled missing values in columns like passenger_count, RatecodeID, and congestion_surcharge

Performed one-hot encoding for categorical features like store_and_fwd_flag and payment_type

Standardized numerical features using StandardScaler

Created new feature 'duration of ride' based on pickup and dropoff timestamps
