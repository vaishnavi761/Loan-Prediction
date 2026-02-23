# Loan Prediction App

A Machine Learning powered web application that predicts whether a loan will be **approved or rejected** based on applicant details.

🔗 Live Demo: https://loan-prediction-zpufgynfmx7rywkkwmx2f6.streamlit.app/

---

## 🚀 Overview

This app is built using **Streamlit** and a trained ML model to help users estimate loan eligibility.

It takes user inputs like income, credit history, loan amount, etc., and returns a prediction indicating if the loan is likely to be **approved** or **declined**.

---

## 🛠️ Features

✔ Collects user input for key loan application parameters  
✔ Real-time prediction using a trained ML model  
✔ Simple, clean and intuitive UI  
✔ Fast inference with visual feedback

---

## 📥 Input Fields

The app takes the following inputs:

| Feature | Description |
|---------|-------------|
| Gender | Applicant gender |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Education level |
| Self Employed | Self-employment status |
| Applicant Income | Monthly income |
| Co-applicant Income | Co-applicant income |
| Loan Amount | Requested loan amount |
| Loan Amount Term | Loan duration in days |
| Credit History | Past credit record |
| Property Area | Urban / Semi-urban / Rural |

*(Add or remove fields based on your actual app inputs)*

---

## 🧠 How It Works

1. User enters values for each input field  
2. Inputs are preprocessed and scaled (if applicable)  
3. A machine learning model predicts loan eligibility  
4. Result is displayed instantly on the app

---

## 🧪 Model Details

| Attribute | Value |
|-----------|-------|
| Algorithm | [e.g., Random Forest / Logistic Regression] |
| Dataset | [e.g., Loan Prediction Dataset from …] |
| Performance | Accuracy: [XX%] |

*(Replace with actual model used and evaluation results)*

---

## 🖥️ Screenshots

You can include screenshot images here if required.

---

## 📦 Tech Stack

- 🧰 **Python**
- 📊 **Pandas**
- 🔢 **scikit-learn**
- 🌐 **Streamlit**

---

## 🧑‍💻 Installation

To run locally:

```bash
git clone https://github.com/your-username/loan-prediction-app.git
cd loan-prediction-app
pip install -r requirements.txt
streamlit run app.py
