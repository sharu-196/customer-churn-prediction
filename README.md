# Customer Churn Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a customer is likely to leave a telecommunications service using machine learning techniques.

The goal is to analyze customer demographics, service subscriptions, contract details, and billing information to identify patterns associated with customer churn and build a predictive model to support data-driven customer retention strategies.

This project follows an end-to-end machine learning workflow including data exploration, preprocessing, model development, evaluation, and web application deployment.

## 🎯 Problem Statement

Customer churn is a major challenge for businesses, particularly in the telecommunications industry. Losing customers can affect revenue and business growth.

The objective of this project is to build a machine learning model that predicts whether a customer is likely to leave a service based on historical customer data.

The prediction helps businesses identify customers who may be at risk of leaving and supports better customer retention decisions.

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographic information, service subscriptions, contract details, payment methods, and billing information.

### Key Features

**Customer Information**
- Customer ID
- Gender
- Senior citizen status
- Partner status
- Dependents

**Service Information**
- Phone service
- Internet service
- Online security
- Online backup
- Device protection
- Tech support
- Streaming services

**Contract and Billing Information**
- Tenure
- Contract type
- Paperless billing
- Payment method
- Monthly charges
- Total charges

### Target Variable

`Churn`

- `Yes` → Customer left the service
- `No` → Customer continued using the service

## 🧠 Approach

### 1. Data Understanding
- Loaded and explored the customer churn dataset
- Examined dataset structure and feature types
- Analyzed customer characteristics and churn distribution

### 2. Data Preprocessing
- Removed unnecessary customer identifiers
- Handled missing or invalid values
- Converted numerical features into appropriate data types
- Encoded categorical variables
- Prepared the dataset for model training

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer demographics and service subscriptions
- Examined relationships between contract types, tenure, billing, and churn
- Visualized customer churn patterns using charts

### 4. Model Development

The project uses **Logistic Regression** for binary classification to predict customer churn.

The dataset is divided into training and testing sets to evaluate the model's ability to predict unseen customer records.

### 5. Model Evaluation

The model is evaluated using:
- Accuracy
- Confusion Matrix
- Churn Probability
- Predicted Churn Status

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Streamlit
- Jupyter Notebook

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── app.py
├── customer_churn_model.pkl
├── requirements.txt
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md
```

*The CSV dataset is included in the structure only if it has been uploaded to the repository.*

## ✨ Key Features

- Customer information input through an interactive web form
- Machine learning-based churn prediction
- Estimated probability of customer churn
- Prediction result displayed through a simple interface
- Interactive web application built using Streamlit
- Deployed application accessible through a web browser

## 📈 Key Outcomes

- Developed an end-to-end machine learning application
- Applied data cleaning and preprocessing techniques
- Trained a Logistic Regression classification model
- Generated churn probability estimates
- Built and deployed an interactive prediction application

## 🚀 Live Demo

**Live Application:** [Customer Churn Prediction System](https://share.streamlit.io/)

*Replace this link with your actual Streamlit app URL.*

## 🔮 Future Improvements

- Compare Logistic Regression with Random Forest and other algorithms
- Perform hyperparameter tuning
- Analyze feature importance and churn drivers
- Add customer retention recommendations
- Improve model performance and evaluation
- Enhance the application with interactive analytics dashboards

## 👩‍💻 Author

**Sharu Latha**

🎓 Computer Science Graduate

💻 Interests: Python Development | Web Development | AI & Machine Learning

🔗 [GitHub](https://github.com/sharu-196)

🔗 [LinkedIn](https://www.linkedin.com/in/sharu-latha19/)

---

*This project was developed for learning and portfolio purposes to demonstrate skills in Python, data preprocessing, machine learning, model evaluation, and web application deployment.*
