# 🏦 Credit Risk Prediction

> Predict whether a loan applicant is likely to default on a loan using Machine Learning.

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Objective

Build a binary classification model to predict whether a loan applicant will be **Approved (Y)** or **Rejected (N)** based on personal and financial attributes.

---

## 📂 Project Structure

```
credit-risk-prediction/
│
├── loan_prediction.ipynb   # Main Jupyter Notebook
├── train.csv               # Dataset (from Kaggle)
└── README.md               # Project documentation
```

---

## 📊 Dataset

**Loan Prediction Dataset** — Analytics Vidhya / Kaggle

| Feature | Description |
|---|---|
| Gender | Male / Female |
| Married | Applicant married (Yes/No) |
| Dependents | Number of dependents |
| Education | Graduate / Not Graduate |
| Self_Employed | Self employed (Yes/No) |
| ApplicantIncome | Applicant income |
| CoapplicantIncome | Coapplicant income |
| LoanAmount | Loan amount (in thousands) |
| Loan_Amount_Term | Term of loan (in months) |
| Credit_History | Credit history meets guidelines (1/0) |
| Property_Area | Urban / Semiurban / Rural |
| **Loan_Status** | **Target — Y (Approved) / N (Rejected)** |

📥 **Dataset:** [Kaggle - Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)

---

## 🔧 Steps Covered

1. **Data Loading** — Loaded dataset using Pandas
2. **Exploratory Data Analysis (EDA)** — Visualized loan amount, income, education, credit history vs loan status
3. **Missing Value Handling** — Mode imputation for categorical columns, median for numerical columns
4. **Label Encoding** — Converted categorical variables to numeric using LabelEncoder
5. **Train / Test Split** — 80% training, 20% testing
6. **Model Training** — Logistic Regression & Decision Tree Classifier
7. **Model Evaluation** — Accuracy score, Confusion Matrix, Classification Report

---

## 📈 EDA Highlights

- Applicants with **Credit History = 1** have significantly higher approval rates
- **Graduates** are more likely to get loans approved
- **Semiurban** property applicants have the highest approval rate
- Higher income does not always guarantee approval — loan amount matters too

---

## 🤖 Models Used

| Model | Result |
|---|---|
| Logistic Regression | Higher Accuracy ✅ |
| Decision Tree (max_depth=5) | Slightly Lower Accuracy |

**Logistic Regression** performed better on this dataset as the relationships between features and target are relatively linear.

---

## 📉 Model Evaluation

Both models were evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-Score)

---

## 🚀 How to Run

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/credit-risk-prediction.git
cd credit-risk-prediction
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Add dataset
Place `train.csv` from Kaggle in the project root folder.

### 4. Launch Jupyter Notebook
```bash
jupyter notebook loan_prediction.ipynb
```

---

## 🛠 Skills Demonstrated

- Data Cleaning & Missing Value Handling
- Exploratory Data Analysis (EDA)
- Data Visualization (Matplotlib & Seaborn)
- Label Encoding
- Binary Classification using Machine Learning
- Model Evaluation using Confusion Matrix & Accuracy

---

## 👩‍💻 Author

**Aimen Safdar**
- 💼 LinkedIn: [Aimen Safdar](https://www.linkedin.com/in/aimen-safdara1a096373)
- 📧 safdarashahid243@gmail.com
