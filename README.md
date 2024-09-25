## Salary Prediction Data Science Project

# Overview

This project uses exploratory data analysis (EDA) and machine learning to predict salaries based on input features. The project consists of two main components:

**Data Preprocessing and Modeling:** The data is preprocessed and a machine learning model is trained to predict salaries. The model is saved as a pickle file (model.pkl).

**Streamlit App:** A Streamlit app is built to load the saved model and make predictions based on user input.

# Files and Folders

* app.py: The Streamlit app code.
* Employees.xlsx: The original dataset.
* model.pkl: The saved machine learning model.
* analysis-modeling.ipynb: Exploratory Data Analysis

Dataset Source: 
https://www.kaggle.com/datasets/abdallahwagih/company-employees

# How to Run

1. Clone the repository: git clone https://github.com/your-username/salary-prediction-data-science-project.git
2. Run the Streamlit app: streamlit run app.py

# Usage

1. Open the Streamlit app in your web browser.
2. Enter input features (e.g. years of experience, job rate) in the app.
3. Click the "Predict" button to get the predicted salary.

# Model Details
* The model is trained on a dataset of Employees.xlsx
* The model uses Linear Regression to predict salaries.
* The model is saved as a pickle file (model.pkl) and loaded into the Streamlit app.

# Future Work
* Collect more data to improve model accuracy.
* Experiment with different machine learning algorithms.
* Add more features to the app (e.g. data visualization, model interpretation).