# Placement Prediction Model

## Overview
This Python script builds a machine learning model for predicting placement outcomes based on students' academic performance and IQ scores. The model utilizes logistic regression for classification.

## Dependencies
- pandas
- numpy
- matplotlib
- scikit-learn
- mlxtend

## Usage
1. **Data Preparation**: Ensure `placement.csv` is in the `/content` directory.
2. **Running the Code**: Execute the provided Python script in a Jupyter Notebook or any Python environment with the dependencies installed.
3. **Understanding the Code**:
    - **Data Loading**: Loads the placement dataset into a pandas DataFrame.
    - **Data Preprocessing**: Removes the first column and visualizes the data.
    - **Model Building**: Splits the data, standardizes features, builds a logistic regression model, and evaluates its performance.
4. **Results**: Displays the accuracy score of the model on the test set.

## Learning Source
I learned to create this model from the CampusX YouTube channel.
