# 🏦 Industrial Credit Risk Assessment System

An AI-based Credit Risk Assessment System developed using Machine Learning and Streamlit to predict the probability of loan default and assist financial institutions in making data-driven lending decisions. The system combines machine learning predictions, bank policy rules, and model explainability to provide transparent and reliable credit risk evaluation.

## 📌 Project Overview

The Industrial Credit Risk Assessment System analyzes applicant financial, credit, and loan-related information to estimate the likelihood of loan default. Based on the prediction probability, the system calculates a CIBIL-like score and applies banking policy rules to generate a final decision such as approval, high-interest approval, or rejection.

The system also provides model explainability using SHAP (SHapley Additive Explanations), allowing users to understand how each feature contributes to the prediction outcome.

This project demonstrates the practical application of Artificial Intelligence and Machine Learning in the finance domain for risk assessment and decision support.

## ✨ Features

- Machine Learning-based loan default prediction

- Probability-based risk assessment

- Automatic CIBIL score calculation

- Bank policy override rules

- SHAP-based model explainability

- Interactive Streamlit user interface

- Credit assessment history storage using SQLite

- Automated PDF credit report generation

- Data visualization for model interpretation

## 🧠 System Workflow

- User enters applicant personal, loan, and financial details.

- Input data is processed and passed to the trained ML model.

- Model predicts default probability.

- Probability is converted into a CIBIL-like credit score.

- Bank policy rules validate financial conditions.

- Final credit decision is generated.

- SHAP explainability visualizes feature impact.

- Assessment details are stored in database.

- Credit report can be downloaded as a PDF.

## 🛠 Technologies Used

Python

Machine Learning (Scikit-learn)

Streamlit – Web interface

Pandas & NumPy – Data processing

SHAP – Model explainability

Matplotlib – Visualization

SQLite – Local database storage

ReportLab – PDF generation

Joblib – Model loading

# ⚙️ Installation & Setup
## 1️⃣ Clone Repository
git clone https://github.com/khushikumari-2003/Credit-Risk-Analysis-System

cd Credit-Risk-Analysis-System

## 2️⃣ Install Dependencies
pip install -r requirements.txt

## 3️⃣ Run Application
streamlit run app.py

## 📊 Model Explainability

The system uses SHAP (SHapley Additive Explanations) to explain model predictions. The waterfall plot shows how individual features increase or decrease the probability of loan default, improving transparency and trust in AI-based decisions.

## 📄 Report Generation

After assessment, the system generates a downloadable credit report containing:

- Applicant name

- Default probability

- Calculated CIBIL score

- Final decision

- System-generated summary

## 🎯 Use Cases

- Banking and financial institutions

- Loan approval analysis

- Risk management systems

- Credit scoring research

- AI-based financial decision support

## 🚀 Future Improvements

- Integration with real-time banking APIs

- Advanced deep learning models

- Cloud database integration

- User authentication system

- Deployment on cloud platforms

## 👩‍💻 Author
Khushi Kumari 

B.tech CSE(Ai & Ml)
