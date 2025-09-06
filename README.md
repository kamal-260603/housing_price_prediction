California House Price Predictor Model
This project is a comprehensive machine learning solution for predicting the median house prices in California based on the 1990 census data. It serves as a practical example of a complete end-to-end regression task.

Project Structure

Housing_price_predictions.ipynb: The main Jupyter Notebook that contains all the code for the project.

housing.csv: The dataset used for training and testing the models.

Housing_price_predictions.pdf: for clearly visualizing the outputs of cells.

README.md: This file, providing an overview of the project.

📝 Overview
The objective is to build a predictive model that accurately estimates the median house value for a given block group in California. The project covers the entire machine learning pipeline, from data preprocessing to model evaluation.

✨ Key Features
Data Cleaning & Preprocessing:

Handling of missing values in the total_bedrooms column.

Conversion of the categorical ocean_proximity feature into a numerical format using one-hot encoding.

Splitting the data into training and testing sets.

Model Implementation:

Linear Regression: A simple, interpretable baseline model.

Decision Tree Regressor: A non-linear model that partitions the data to make predictions.

Random Forest Regressor: An ensemble model that is robust and capable of capturing complex, non-linear relationships.

Performance Evaluation:

The models are evaluated using standard regression metrics, including Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R^2).

🚀 Getting Started
To run this project, you will need to have Python and the following libraries installed:

pandas

scikit-learn

matplotlib (for visualizations)

seaborn (for visualizations)

You can install them using pip:

Bash

pip install pandas scikit-learn matplotlib seaborn
Once the dependencies are installed, you can open and run the Housing_price_predictions.ipynb notebook to see the data analysis, model training, and performance results.

📊 Results
The notebook provides detailed output for each step, including the performance metrics for each model. The results demonstrate the superior predictive power of the ensemble model (Random Forest) compared to the simpler Linear Regression and Decision Tree models.

You can see the output of cells in the Housing_price_predictions.pdf. 