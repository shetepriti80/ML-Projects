Super Store Sales Prediction using KNN Regression
A Machine Learning web application that predicts Super Store sales using K-Nearest Neighbors (KNN) Regression and Flask.

📌 Overview
Super Store Sales Prediction is a Machine Learning project designed to predict product sales based on various product and outlet-related features.

The project uses a KNN Regression model trained on Super Store sales data. The trained model is integrated into a Flask web application, allowing users to enter product and outlet details through a simple web interface and receive a predicted sales value.

This project demonstrates the complete Machine Learning workflow, from data preprocessing and model training to model deployment using Flask.

🎯 Objective
The main objective of this project is to build a Machine Learning system that can:

Predict product sales using historical retail data.
Apply KNN Regression to a real-world dataset.
Process numerical and categorical features.
Deploy the trained Machine Learning model using Flask.
Provide predictions through a user-friendly web interface.
✨ Key Features
🤖 KNN Regression-based sales prediction
📊 Super Store retail sales dataset
🧹 Data preprocessing and feature transformation
🔢 Categorical feature encoding
💾 Pre-trained Machine Learning model
🌐 Flask-based web application
🖥️ Simple and interactive prediction interface
⚡ Real-time sales prediction
🧠 Machine Learning Model
The project uses K-Nearest Neighbors (KNN) Regression to predict sales.

KNN Regression works by identifying data points that are most similar to a given input and using their target values to estimate the prediction.

The trained model is saved as:

knn_regression_model.pkl

📊 Features Used
The model uses different product and outlet characteristics, including:

Item Weight
Item Fat Content
Item Visibility
Item MRP
Item Type
Outlet Identifier
Outlet Size
Outlet Location Type
Outlet Establishment Year
Outlet Type
🔄 Project Workflow
Dataset
   ↓
Data Cleaning & Preprocessing
   ↓
Feature Engineering
   ↓
Categorical Encoding
   ↓
Train/Test Split
   ↓
KNN Regression Model
   ↓
Model Evaluation
   ↓
Save Trained Model
   ↓
Flask Web Application
   ↓
User Input
   ↓
Sales Prediction

🛠️ Technologies Used
Technology	Purpose
🐍 Python	Programming language
🐼 Pandas	Data manipulation and preprocessing
🤖 Scikit-learn	Machine Learning
📈 KNN Regression	Sales prediction
🌐 Flask	Web application
📝 HTML	Web interface
🎨 CSS	Styling
📓 Jupyter Notebook	Model development
💾 Pickle	Model saving/loading

📂 Project Structure
Super_Store/
│
├── Super_store/
│   ├── app.py
│   ├── KNN Regression.ipynb
│   ├── KNN_reg_outlet_sales - KNN_reg_outlet_sales.csv
│   ├── knn_regression_model.pkl
│   │
│   ├── templates/
│   │   └── index.html
│   │
│   └── static/
│       └── ...
│
└── README.md

🌐 Web Application
The Flask application allows users to enter the required product and outlet information through a web form.

The application then:

Receives user input.
Converts the input into a Pandas DataFrame.
Performs the required feature encoding.
Aligns the input features with the trained model.
Passes the data to the KNN Regression model.
Displays the predicted sales value.
📓 Model Development
The Machine Learning model was developed using a Jupyter Notebook:

KNN Regression.ipynb

The notebook contains the data analysis, preprocessing, model development, and training process.

🚀 Future Improvements
Add detailed model evaluation metrics.
Compare KNN with other regression algorithms.
Improve the user interface.
Add data visualization.
Add prediction history.
Improve input validation.
Deploy the application to a cloud platform.
Add automated model retraining.
🎓 Learning Outcomes
Through this project, the following concepts are demonstrated:

Machine Learning
Regression
KNN Algorithm
Data preprocessing
Feature engineering
Categorical encoding
Model training
Model serialization
Flask application development
Machine Learning deployment

