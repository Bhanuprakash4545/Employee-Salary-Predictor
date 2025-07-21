📘 Project Title: Employee Salary Prediction Web Application

This project is a machine learning-powered web application developed using Streamlit. It is designed to predict whether an individual's income exceeds $50K per year based on various demographic attributes. The model is trained on the UCI Adult Income Dataset, a commonly used benchmark dataset for classification tasks.



🛠️ Project Description

The application allows users to upload a CSV file containing employee data. Upon uploading, the app processes the input and utilizes a pre-trained model (stored as model.pkl) to predict the income class of each employee record in the dataset. The output includes the original data along with an additional column that displays the predicted income category.



💡 Features

-Upload functionality for .csv files.

-Automatic display of uploaded data.

-Prediction of income class using a trained model.

-Clean tabular display of results.

-Error handling for file issues or model compatibility.



🧪 Technologies Used

Python – Core programming language.

Streamlit – For creating the web interface.

Pandas – For data manipulation.

Scikit-learn – For machine learning model training and prediction.

Joblib – For model serialization.



📁 Files Included

app.py – Main application script.

model.pkl – Serialized machine learning model.

requirements.txt – Python dependencies for running the app.


