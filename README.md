# Customer Churn Prediction Web Application

A machine learning-based web application that predicts whether a customer is likely to leave a service based on their account information, subscription details, and service usage.

The application uses Python, Flask, and Scikit-learn to connect a trained machine learning model with a simple web interface, allowing users to enter customer details and receive churn predictions.

## Live Demo

**Web Application:** https://churn-prediction.onrender.com/

**GitHub Repository:** https://github.com/karanvirchahal28-max/Customer_Churn_Prediction

---

## Project Overview

Customer churn occurs when customers stop using a company's products or services. Identifying customers who are likely to leave can help businesses understand retention risks and make better customer engagement decisions.

This project demonstrates an end-to-end machine learning workflow, from data preprocessing and exploratory data analysis to model-based prediction through a Flask web application.

## Key Features

- Customer churn prediction using a trained machine learning model.
- Interactive web interface for entering customer information.
- Data preprocessing and categorical feature encoding.
- Exploratory Data Analysis (EDA) to understand customer behaviour.
- Machine learning classification for churn prediction.
- Flask backend for handling user input and generating predictions.
- Web-based display of prediction results.

## Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Backend | Flask |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Frontend | HTML, CSS |
| Model Persistence | Pickle |
| Version Control | Git, GitHub |
| Deployment | Render |

## Project Workflow

### 1. Data Preprocessing

- Load and inspect historical customer data.
- Handle missing values and duplicate records.
- Convert categorical variables into numerical representations.
- Prepare the dataset for machine learning.

### 2. Exploratory Data Analysis

EDA helps understand customer behaviour and identify patterns associated with churn.

Some of the factors explored include:

- Contract type
- Payment method
- Monthly charges
- Total charges
- Customer tenure
- Technical support services

### 3. Model Development

The machine learning workflow involves:

- Separating input features and target labels.
- Splitting data into training and testing sets.
- Encoding categorical variables.
- Training classification models.
- Evaluating model performance using classification metrics.

Models explored in the original project include Decision Tree, Random Forest, and XGBoost. SMOTE-ENN was also described as a technique for addressing class imbalance.

### 4. Flask Web Application

The Flask backend connects the web interface with the trained machine learning model.

**Prediction workflow:**

1. User enters customer details through the web form.
2. The form submits the information to the Flask application.
3. Flask processes the submitted customer attributes.
4. The trained model generates a churn prediction.
5. The application displays the prediction to the user.

### 5. Deployment

The web application is deployed using Render and can be accessed through the live demo link.

## Project Structure

```text
Customer_Churn_Prediction/
│
├── Images/
├── Jupyter Notebooks/
├── static/
├── template/
├── app.py
├── model.sav
├── first_telc.csv
└── README.md
```

## Evaluation Metrics

The machine learning workflow uses the following evaluation metrics:

| Metric | Purpose |
|---|---|
| Accuracy | Measures overall prediction correctness |
| Precision | Measures how many predicted churn cases are actually churn cases |
| Recall | Measures how many actual churn cases are identified |
| F1-Score | Balances precision and recall |

Actual performance values should be reported only after verifying the results from the model evaluation notebook.

## Applications

- Customer retention analysis
- Identification of potential customer churn
- Subscription-based business analysis
- Customer behaviour understanding
- Data-driven business decision-making

## Future Improvements

- Develop a dedicated JSON-based REST API.
- Add customer-level churn probability visualizations.
- Improve model evaluation and hyperparameter tuning.
- Add an interactive analytics dashboard.
- Implement user authentication and prediction history.
- Improve deployment and backend scalability.

## Learning Outcomes

Through this project, I explored:

- Machine learning classification workflows.
- Data preprocessing and exploratory analysis.
- Flask application development.
- Integration of a trained ML model with a web interface.
- Understanding how predictive analytics can support business decisions.

## Acknowledgement

This repository is adapted from the original project:

**Original Repository:** https://github.com/11-aryan/Customer-Churn-Prediction

Original author: [11-aryan](https://github.com/11-aryan)

The original implementation and its contributors are acknowledged. Modifications and additional contributions to this repository should be documented separately.

---

**Developed and maintained by Karanvir Singh**

GitHub: https://github.com/karanvirchahal28-max
