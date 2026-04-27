# churn-prediction-app

A Streamlit-based machine learning application that predicts whether a customer is likely to churn based on their demographic and service details.

This project uses Logistic Regression and Random Forest models, with hyperparameter tuning via GridSearchCV, and deploys the best-performing model for real-time predictions.

🚀 Features

📌 Interactive UI built with Streamlit
🤖 Machine Learning pipeline with:
Data preprocessing (imputation, scaling, encoding)
Model training & evaluation

🔍 Hyperparameter tuning using GridSearchCV

📊 Probability-based churn prediction

📈 Visual comparison of Churn vs Stay probability

🧾 Customer input summary table

🧠 Machine Learning Workflow

Data Preprocessing

Missing values handled using SimpleImputer
Numerical features scaled using StandardScaler
Categorical features encoded using OneHotEncoder

Models Used

Logistic Regression

Random Forest Classifier

Model Selection

Both models are tuned using GridSearchCV

Evaluated using F1-score

Best model (Random Forest) is selected for prediction

📁 Project Structure

📦 churn-predictor
 ┣ 📜 app.py           # Streamlit frontend
 ┣ 📜 model.py         # Model training & pipeline
 ┣ 📜 telco.csv        # Dataset
 ┣ 📜 README.md        # Project documentation
