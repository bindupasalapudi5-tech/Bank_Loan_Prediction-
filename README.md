# Bank Loan Prediction 

A Machine Learning-based web application that predicts whether a loan application will be approved or rejected based on applicant information. The project uses a Random Forest Classifier trained on historical loan data and is deployed using Flask and Render.

## 🚀 Live Demo

https://bank-loan-prediction-1.onrender.com/

## 📌 Project Overview

The Bank Loan Approval Prediction System helps automate the loan approval process by analyzing applicant details such as income, credit history, education, loan amount, and property area. The system predicts loan eligibility quickly and accurately, reducing manual effort and improving decision-making efficiency.

## 🎯 Features

- Predicts loan approval status in real time
- User-friendly web interface
- Machine Learning-based decision making
- Fast and accurate predictions
- Online deployment using Render
- Responsive and easy-to-use design

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-Learn
- Pandas
- NumPy
- HTML
- CSS
- Joblib
- Render

## 📊 Dataset

The project uses the Loan Prediction Dataset containing applicant information such as:

- Gender
- Married Status
- Dependents
- Education
- Self Employed
- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- Loan Status

## ⚙️ Project Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Encoding
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Model Saving
8. Flask Integration
9. Deployment on Render

## 🤖 Machine Learning Model

### Random Forest Classifier

The Random Forest Classifier was used because it:

- Provides high prediction accuracy
- Handles large datasets efficiently
- Reduces overfitting
- Works well with structured data

## 📈 Results

- Accuracy: Approximately 80% - 85%
- Fast prediction response time
- User-friendly prediction interface

## 📂 Project Structure

```text
Bank-Loan-Prediction/
│
├── app.py
├── loan_model.pkl
├── requirements.txt
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── dataset/
│   └── loan_data.csv
└── README.md
```

## 💻 Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/your-username/Bank-Loan-Prediction.git
cd Bank-Loan-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

### Open Browser

```text
http://127.0.0.1:5000
```

## 🔮 Future Enhancements

- Integration with real-time banking databases
- Advanced Machine Learning models
- Mobile application development
- AI-based risk assessment
- Enhanced authentication and security
- Cloud scalability improvements

## 📚 References

- Scikit-Learn Documentation
- Flask Documentation
- Pandas Documentation
- NumPy Documentation
- Kaggle Loan Prediction Dataset
