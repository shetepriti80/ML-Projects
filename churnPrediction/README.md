# Customer Churn Prediction System

A Machine Learning-based web application that predicts whether a bank customer is likely to leave (churn) or stay using a **Random Forest Classifier**. The application is built with **Python**, **Scikit-learn**, and **Streamlit** for an interactive user interface. The trained model and scaler are loaded using Pickle for real-time predictions. :contentReference[oaicite:0]{index=0}

---

## 📌 Project Overview

Customer churn prediction helps banks identify customers who are likely to discontinue their services. This project uses historical customer data to train a machine learning model capable of predicting customer churn based on various financial and demographic factors.

The application allows users to input customer details through a simple web interface and instantly predicts whether the customer will stay or exit.

---

## 🚀 Features

- Predicts customer churn using Machine Learning
- Interactive Streamlit web interface
- Uses a trained Random Forest Classifier
- Real-time prediction
- Data preprocessing with StandardScaler
- Supports categorical feature encoding
- Simple and user-friendly interface

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- NumPy
- Pandas
- Pickle
- Jupyter Notebook

---

## 📂 Project Structure

```
Customer-Churn-Prediction/
│
├── app.py
├── Python_Implementation_for_churn_prediction.ipynb
├── random_forest_churn_model.pkl
├── scaler.pkl
├── 1_Churn_Modelling.csv
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The project uses the **Churn Modelling Dataset** containing customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Active Member
- Estimated Salary
- Exited (Target Variable)

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Random Forest Classifier

**Preprocessing**

- Label Encoding
- One-Hot Encoding
- Feature Scaling using StandardScaler

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

### 2. Navigate to project folder

```bash
cd customer-churn-prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 📝 Input Features

The user provides:

- Credit Score
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Active Member
- Estimated Salary
- Country
- Gender

These inputs are scaled and passed to the trained Random Forest model for prediction. :contentReference[oaicite:1]{index=1}

---

## 📈 Prediction Output

The application displays one of the following:

- ✅ Customer Will Stay
- ❌ Customer Will Exit

---

## 📸 Application Interface

The Streamlit application includes:

- Numeric input fields
- Dropdown menus
- Predict button
- Prediction result

---

## 📦 Requirements

Example:

```txt
streamlit
numpy
pandas
scikit-learn
pickle-mixin
```

---

## 🔮 Future Improvements

- Deploy on Streamlit Cloud
- Add probability score
- Improve UI with charts
- Support multiple ML algorithms
- Hyperparameter tuning
- Feature importance visualization

  ---

  ## 👨‍💻 Author

**Priti Shete**

- GitHub: https://github.com/shetepriti80
- LinkedIn: https://linkedin.com/in/shetepriti80

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub!

---

