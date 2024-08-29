# Salary Prediction Using Linear Regression

## Overview

This project aims to predict an individual's salary based on their years of experience using a simple Linear Regression model. By providing years of experience as input, the model outputs the predicted salary. Linear Regression is a statistical method that models the relationship between a dependent variable (Salary) and one or more independent variables (YearsExperience).


You can install the necessary packages using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Project Structure

```
salary_prediction/
│
├── data/
│   └── salary_data.csv         # The dataset with years of experience and corresponding salaries
│
├── src/
│   └── salary_prediction.py    # Script for loading the data, training, and predicting salary
│
├── README.md                   # Project description and instructions
└── requirements.txt            # List of required Python libraries
```

## Dataset

The dataset `salary_data.csv` contains two columns:
- `YearsExperience`: Number of years of professional experience
- `Salary`: Annual salary in dollars

The dataset is used to train and validate the model.

## Workflow

1. **Data Loading**: The dataset is loaded from a CSV file using `Pandas`.
2. **Exploratory Data Analysis (EDA)**: The data is explored visually and statistically to understand trends and relationships. We plot Years of Experience vs. Salary using Matplotlib.
3. **Model Training**: A Linear Regression model is trained using the `scikit-learn` library.
4. **Prediction**: The trained model is used to predict salaries for new input values of years of experience.
5. **Evaluation**: The performance of the model is evaluated using metrics such as Mean Squared Error (MSE) or R-squared.

## How to Run the Project

### Step 1: Prepare the Data
Ensure you have the dataset (`salary_data.csv`) stored in the `data/` directory.

### Step 2: Run the Prediction Script
Navigate to the `src/` directory and execute the Python script:

```bash
python salary_prediction.py
```

The script will train the Linear Regression model on the dataset and display the predicted salaries for new input values.

### Step 3: Visualize the Results
The script also provides a visual plot of the best fit line for the Linear Regression model over the dataset points.


## Model Performance

The performance of the Linear Regression model can be evaluated using:
- **Mean Squared Error (MSE)**: Measures the average squared difference between actual and predicted values.
- **R-squared Score**: Indicates how well the independent variable explains the variability in the dependent variable.

These metrics will be printed when running the script.

## Conclusion

This project demonstrates how to build a simple machine learning model using Linear Regression to predict salaries based on years of experience. With just a few lines of code, you can train a predictive model and use it to make forecasts for new data.
