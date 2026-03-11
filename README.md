Laptop Price Prediction is a Machine Learning project that predicts the price of a laptop based on its specifications such as brand, RAM, processor, storage, GPU, operating system, and screen features.

The goal of this project is to help users estimate the price of a laptop based on its configuration using data analysis and machine learning techniques.

# Objective

The main objectives of this project are:

To analyze laptop specifications and their effect on price

To clean and preprocess the dataset

To build a machine learning model that predicts laptop prices

To evaluate model performance using appropriate metrics

# Dataset

The dataset contains various laptop features such as:

Brand

Laptop Type

RAM

Weight

Operating System

CPU

GPU

Screen Resolution

Storage (HDD / SSD)

Price

The dataset is preprocessed to handle missing values, categorical encoding, and feature engineering.

# Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

# Data Preprocessing

The following preprocessing steps were applied:

Handling missing values

Encoding categorical variables

Feature extraction from CPU, GPU, and storage

Removing outliers

Feature scaling

 ## Machine Learning Models Used

Several regression models were tested:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Among these models, Random Forest Regressor performed the best with the highest accuracy.

## Model Evaluation

The model performance was evaluated using:

R² Score

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

# Results

The final model achieved:

High prediction accuracy

Reliable price estimation based on laptop specifications

# How to Run the Project

Clone the repository

git clone https://github.com/yourusername/laptop-price-prediction.git

Navigate to the project folder

cd laptop-price-prediction

Install required libraries

pip install -r requirements.txt

Run the notebook

jupyter notebook
# Project Workflow

Data Collection

Data Cleaning

Exploratory Data Analysis

Feature Engineering

Model Training

Model Evaluation

Price Prediction
