# Customer-Churn-Prediction---End-to-End-ML-Project
Built a machine learning model to predict telecom customer churn, reducing potential revenue loss. Developed, trained, and deployed a Random Forest Classifier via Flask API, with feature analysis providing actionable business insights.
Project Title:
Customer Churn Prediction – End-to-End Machine Learning Project

Project Overview:
This project focuses on predicting customer churn for a telecom company using machine learning. Churn prediction is critical for businesses to identify at-risk customers and implement retention strategies, thereby reducing revenue loss. The project is implemented end-to-end, including data preprocessing, model training, evaluation, deployment via REST API, and optional containerization.

Key Features & Components:
Data Collection & Exploration:
Used the Telco Customer Churn dataset from Kaggle.
Explored customer demographics, service usage, and payment patterns.
Handled missing values and analyzed target variable distribution.

Data Preprocessing:
Encoded categorical variables using one-hot encoding.
Scaled numerical features using StandardScaler.
Split data into training and test sets.

Modeling:
Trained a Random Forest Classifier for high predictive performance.
Evaluated model using classification metrics (accuracy, precision, recall, F1-score, ROC-AUC).
Identified top features influencing customer churn for business insights.

Model Saving & Deployment:
Saved the trained model using Pickle.
Built a Flask API to serve predictions from the model.
Exposed the API publicly using ngrok for testing.
Optional deployment via Heroku for production use.

Testing API:
Tested the API using Python requests and JSON payloads.
Enabled real-time prediction of churn probability for new customer data.

Optional Containerization:
Dockerized the application for consistent deployment across environments.

Technologies & Libraries Used:
Programming Language: Python
Libraries: pandas, numpy, scikit-learn, Flask, flask-ngrok, pickle
Deployment Tools: ngrok, Heroku, Docker
Environment: Google Colab or Local Machine

Business Impact:
Enables telecom companies to predict potential churners and take preventive actions.
Provides feature insights to identify key factors affecting churn.
API deployment allows real-time integration with business applications or dashboards.

Learning Outcomes:
End-to-end machine learning project lifecycle experience.

Practical knowledge of data preprocessing, modeling, and evaluation.

Hands-on experience with Flask API development, deployment, and Docker containerization.

Understanding of real-world business problem-solving using AI/ML.
