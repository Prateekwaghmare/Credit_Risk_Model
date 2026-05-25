🏦 Credit Risk Intelligence Engine
Python Streamlit scikit-learn NumPy Pandas License

An AI-powered Streamlit web application that automates credit risk evaluation for loan processing officers. The app assesses a borrower's creditworthiness in real-time using machine learning — providing credit scores, default probabilities, and risk tier classifications to support smarter lending decisions.

🔗 Live Demo: https://prateek-credit-risk-model-ml-project.streamlit.app/

📋 Table of Contents
Overview
App Preview
Features
Tech Stack
Project Structure
ML Models
Model Evaluation
Input Features
Risk Tiers
Installation
Usage
Deployment
Author

🔍 Overview
Credit risk modelling is a critical process in the banking and financial sector. This project builds an end-to-end machine learning pipeline designed for loan processing officers to evaluate an applicant's creditworthiness for an applied loan.

The app takes in applicant parameters like income, loan amount, credit history, and delinquency data — then returns a comprehensive risk assessment report including:

📊 Credit Score (300–900 range)
⚠️ Default Probability (%)
🏷️ Risk Classification (Poor / Average / Good / Excellent)
💡 AI Explainability via model coefficients
✨ Features
🎯 Credit Score Prediction — Scored between 300 and 900
📉 Default Probability — Percentage likelihood of loan default
🏷️ Risk Tier Classification — Categorizes applicants into 4 risk bands
💡 AI Explainability — Model coefficients help business teams understand decisions and plan future enhancements
📊 Loan-to-Income Ratio — Calculated and displayed in real time
🖥️ Clean Streamlit UI — Simple, intuitive interface for loan officers
⚡ Fast Predictions — Results delivered in under 200ms
☁️ Cloud Deployed — Hosted on Streamlit Community Cloud
🛠 Tech Stack
Category	Technology
Language	Python 3.10
Frontend	Streamlit 1.45.0
Backend	Python, FastAPI
Data Processing	Pandas 2.2.2, NumPy 1.26.4
ML Library	Scikit-learn 1.5.0, XGBoost
Model Serialization	Joblib 1.3.2
Deployment	Streamlit Cloud
Version Control	Git & GitHub

📁 Project Structure
ml-project-credit-risk-modelling/
│
├── app/
│   ├── main.py                  # Streamlit app — entry point
│   ├── prediction_helper.py     # ML prediction logic & helper functions
│   ├── hero_image.png           # UI hero banner image
│   └── artifacts/
│       └── model_data.joblib    # Serialized trained ML models
│
├── .gitignore                   # Git ignore rules
├── .python-version              # Python version pin (3.10)
├── requirements.txt             # Project dependencies
└── README.md                    # Project documentation

🤖 ML Models
Model 1: Probability of Default (Classification)
Algorithm: Logistic Regression & XGB Classifier
Task: Binary classification — Default (1) or No Default (0)
Output: Probability of default (%)
Model 2: Credit Score (Derived)
Score Range: 300 — 900
Output: Applicant credit score mapped from default probability
Risk Formula
Credit Score  →  Risk Tier  →  Loan Decision Support
Default Probability (%)  →  Risk Classification

📊 Model Evaluation
Model quality is tracked using industry-standard metrics:

Metric	Description
AUC	Area Under the ROC Curve — overall model quality
Gini	Gini Coefficient — model discrimination power
KS Statistic	Kolmogorov-Smirnov — separation between default/non-default
Recall	Sensitivity — ability to catch actual defaulters

📝 Input Features
Feature	Description
Age	Applicant's age
Annual Income (₹)	Applicant's yearly income
Loan Amount (₹)	Amount of loan applied for
Loan Tenure (Months)	Duration of the loan
Loan Purpose	Home / Education / Personal / Auto, etc.
Loan Type	Secured / Unsecured
Residence Type	Owned / Rented / Mortgage
Average DPD	Average Days Past Due on previous loans
Delinquency Ratio	Ratio of delinquent payments in credit history
Credit Utilization Ratio	% of available credit currently in use
Open Loan Accounts	Number of currently active loan accounts

🏷️ Risk Tiers
Credit Score Range	Risk Tier	Classification
750 — 900	🏆 Excellent	Very Low Risk
650 — 749	✅ Good	Low Risk
500 — 649	⚠️ Average	Moderate Risk
300 — 499	❌ Poor	High Risk

⚙️ Installation
Prerequisites
Python 3.10+
Git
Steps
1. Clone the repository

git clone https://github.com/Junead04/ml-project-credit-risk-modelling.git
cd ml-project-credit-risk-modelling
2. Create a virtual environment

python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows
3. Install dependencies

pip install -r requirements.txt
4. Run the application

streamlit run app/main.py
5. Open in browser

http://localhost:8501
🚀 Usage
Open the web application
Fill in the Applicant Profile section:
Age, Annual Income, Loan Amount
Loan Tenure, Residence Type
Fill in the Loan Configuration section:
Loan Purpose, Loan Type
Delinquency Ratio, Average DPD
Credit Utilization Ratio, Open Loan Accounts
Click "Calculate Risk"
View the Assessment Result:
📊 Credit Score (300–900)
⚠️ Default Probability (%)
🏷️ Risk Classification
📈 Loan-to-Income Ratio
☁️ Deployment
This app is deployed on Streamlit Community Cloud.

Deploy your own instance:
Fork this repository
Go to share.streamlit.io
Connect your GitHub account
Select the repo and configure:
Main file path: app/main.py
Python version: 3.10
Click Deploy 🚀
📦 Requirements
streamlit==1.45.0
numpy==1.26.4
pandas==2.2.2
scikit-learn==1.5.0
joblib==1.3.2
👨‍💻 Author
Junead

GitHub

📄 License
This project is licensed under the MIT License — feel free to use, modify, and distribute.

🙏 Acknowledgements
Streamlit — for the powerful and easy web framework
scikit-learn — for ML tools and models
XGBoost — for gradient boosting classifier
⭐ If you found this project helpful, please give it a star on GitHub! ⭐
