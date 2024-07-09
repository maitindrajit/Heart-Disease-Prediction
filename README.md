# Heart-Disease-Prediction
## Overview.


This study focuses on developing a machine learning model to predict the existence of heart disease in patients. The model makes predictions based on a dataset comprising numerous medical variables related to heart health. The logistic regression approach is used to do binary classification, separating patients with and without cardiac disease.

## Project Structure.

- **data.csv** is the dataset used to train and test the model.
- **heart_disease_prediction.py**: The primary Python script that handles data loading, processing, model training, and prediction code.
- **README.md**: The file you are currently reading describes the project and how to execute it.

## Dependencies.

This project requires the following Python libraries:
- NumPy - Pandas
- Scikit-Learn

Pip can be used to install NumPy, Pandas, and Scikit-Learn.

Data Collection and Processing
Data is loaded from a CSV file into a Pandas DataFrame. Basic exploratory data analysis (EDA) is carried out, which includes looking for missing values, viewing statistical measures, and determining the distribution of the target variable.

Splitting Features and Target
The dataset is separated into features ('X') and targets ('Y'). The target variable specifies whether a patient has cardiac disease ('1')or not('0').

Divide the data into training and test sets.
The data is divided into training and test sets in an 80/20 split. Stratification is used to verify that both sets have a similar distribution of the target variable.

Model Training
The training data is then used to train a logistic regression model.

Model Evaluation.
The model's accuracy is tested across both the training and test sets.

Developing a Predictive System
The trained model is used to make predictions about new data. An example input is included to show how the model predicts the existence of heart disease.

Running the Project
Make sure you have all of the essential dependencies installed.
Move the data.csv file to the same directory as the script.
Execute the heart_disease_prediction.py script.
Contributions are welcome. Please fork this repository and submit pull requests containing improvements or bug fixes.

License
This project is open source and distributed under the MIT License.
