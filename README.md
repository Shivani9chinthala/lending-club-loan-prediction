# lending-club-loan-prediction
# 📌 Lending Club Loan & Defaulter Prediction (Banking Domain – JP Morgan)

## 📖 Project Overview
This project focuses on **predicting loan defaults** using the Lending Club dataset.  
The objective is to help financial institutions like **JP Morgan** identify **high-risk borrowers**, reduce **credit losses**, and make **data-driven lending decisions**.  

---

## 📚 Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## 🔎 Data Loading & Cleaning
- 🔹 Loaded Lending Club dataset (`.csv`)  
- 🔹 Handled missing values & irrelevant columns  
- 🔹 Converted categorical variables into numeric (encoding)  
- 🔹 Created new features (e.g., `income_to_loan`)  

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Univariate Analysis
- 🔹 Distribution of annual income  
- 🔹 Loan repayment vs default  

### ✅ Bivariate Analysis
- 🔹 Loan amount vs loan status  
- 🔹 DTI vs loan status  
- 🔹 Home ownership vs default  
- 🔹 Correlation heatmap  

---

## ⚙️ Feature Engineering
- 🔹 Created **income-to-loan ratio**  
- 🔹 One-hot encoded categorical features  
- 🔹 Scaled numerical features with **StandardScaler**  

---

## ✂️ Train-Test Split & Scaling
- 🔹 Split dataset into **train (80%) & test (20%)**  
- 🔹 Applied **scaling for numerical stability**  

---

## 🤖 Model Training
- 🔹 **Model used**: Random Forest Classifier  
- 🔹 **Hyperparameters**:  
  - `n_estimators = 300`  
  - `max_depth = 12`  
  - `random_state = 42`  

---

## 📈 Model Evaluation
- 🔹 Classification Report  
- 🔹 Confusion Matrix  
- 🔹 ROC Curve & AUC Score  

---

## 📊 Visualizations
📌 Loan Status Distribution  
📌 Income vs Default  
📌 DTI vs Default  
📌 Correlation Heatmap  
📌 Confusion Matrix (heatmap)  
📌 ROC Curve (AUC visualization)  
📌 Feature Importance (top predictors)  

---

## 💡 Business Insights
- 🔹 High **interest rates** & **DTI values** strongly predict default  
- 🔹 **Income-to-loan ratio** is a key risk indicator  
- 🔹 **Home ownership** lowers default risk  
- 🔹 Borrowers with **low income + high loan amount** are most vulnerable  

---

## 🚀 Conclusion
This project demonstrates how **Data Science & Machine Learning** can support **risk analytics in banking** by predicting potential loan defaulters.  

---

## 📦 Requirements
Add a file called **`requirements.txt`** with the following content:  
```txt
pandas
numpy
matplotlib
seaborn
scikit-learn

🏷️ Tags

#MachineLearning #DataScience #JPmorgan #Banking #RiskAnalytics #LendingClub #LoanPrediction
