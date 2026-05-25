# 🏦 Credit Risk Intelligence Engine

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.45.0-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.5.0-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.26.4-013243?style=for-the-badge&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-2.2.2-150458?style=for-the-badge&logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> An AI-powered Streamlit web application that automates credit risk evaluation for loan processing officers. The app assesses a borrower's creditworthiness in real-time using machine learning — providing credit scores, default probabilities, and risk tier classifications to support smarter lending decisions.
---

# 🔗 Live Demo

[![Live Demo](https://img.shields.io/badge/Live_Demo-Open_App-success?style=for-the-badge&logo=streamlit)]([https://yourstreamlitlink.streamlit.app](https://prateek-credit-risk-model-ml-project.streamlit.app/))

---

# 📋 Table of Contents

- Overview
- Features
- Tech Stack
- Project Structure
- ML Models
- Model Evaluation
- Input Features
- Risk Tiers
- Installation
- Usage
- Deployment
- Requirements
- Author

---

# 🔍 Overview

Credit risk modelling is one of the most important tasks in the banking and finance sector. This project uses Machine Learning algorithms to analyze applicant details and predict:

- 📊 Credit Score
- ⚠️ Default Probability
- 🏷️ Risk Classification
- 💡 Loan Approval Intelligence

The system helps financial institutions make smarter lending decisions.

---

# ✨ Features

- 🎯 Credit Score Prediction
- 📉 Default Probability Analysis
- 🏷️ Risk Tier Classification
- 📊 Loan-to-Income Ratio
- ⚡ Fast Real-Time Prediction
- 🖥️ Interactive Streamlit Dashboard
- ☁️ Cloud Deployment Support
- 🤖 Machine Learning Powered

---

# 🛠 Tech Stack

| Category | Technology |
|---|---|
| Language | Python 3.10 |
| Frontend | Streamlit |
| Backend | Python |
| ML Libraries | Scikit-learn, XGBoost |
| Data Processing | Pandas, NumPy |
| Model Saving | Joblib |
| Deployment | Streamlit Cloud |
| Version Control | Git & GitHub |

---

# 📁 Project Structure

```bash
credit-risk-intelligence-engine/
│
├── app/
│   ├── main.py
│   ├── prediction_helper.py
│   ├── artifacts/
│   │   └── model_data.joblib
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# 🤖 ML Models

## Model 1: Default Prediction

- Algorithm: Logistic Regression / XGBoost
- Output: Default Probability (%)

## Model 2: Credit Score Prediction

- Score Range: 300–900
- Risk-based Scoring System

---

# 📊 Model Evaluation

| Metric | Description |
|---|---|
| AUC Score | Overall Model Performance |
| Gini Score | Risk Separation Capability |
| KS Statistic | Default Detection Accuracy |
| Recall | Detection of High-Risk Users |

---

# 📝 Input Features

| Feature | Description |
|---|---|
| Age | Applicant Age |
| Annual Income | Yearly Income |
| Loan Amount | Requested Loan Amount |
| Loan Tenure | Loan Duration |
| Credit Utilization | Credit Usage Ratio |
| Delinquency Ratio | Missed Payment Ratio |
| Open Loan Accounts | Active Loans |

---

# 🏷️ Risk Tiers

| Credit Score | Risk Tier | Classification |
|---|---|---|
| 750–900 | 🏆 Excellent | Very Low Risk |
| 650–749 | ✅ Good | Low Risk |
| 500–649 | ⚠️ Average | Moderate Risk |
| 300–499 | ❌ Poor | High Risk |

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/prateekwaghmare/credit-risk-intelligence-engine.git
cd credit-risk-intelligence-engine
```

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

## 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

## 4️⃣ Run Application

```bash
streamlit run app/main.py
```

---

# 🚀 Usage

1. Open the web application
2. Enter applicant information
3. Click **Calculate Risk**
4. View:
   - Credit Score
   - Default Probability
   - Risk Classification
   - Loan Decision Support

---

# ☁️ Deployment

Deploy easily using:

- Streamlit Community Cloud
- Render
- Railway
- Hugging Face Spaces

---

# 📦 Requirements

```txt
streamlit
numpy
pandas
scikit-learn
xgboost
joblib
```

---

# 👨‍💻 Author

## Prateek Waghmare

[![GitHub](https://img.shields.io/badge/GitHub-PrateekWaghmare-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prateekwaghmare)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Prateek_Waghmare-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/prateek-waghmare)

[![Gmail](https://img.shields.io/badge/Gmail-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](prateekbidark2003@gmail.com)

---

# 📄 License

This project is licensed under the MIT License.

---

# 🙏 Acknowledgements

- Streamlit
- Scikit-learn
- XGBoost
- Open Source Community

---

# ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub!

```
