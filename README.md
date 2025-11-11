# 📊 Telco Customer Churn Prediction

This project focuses on predicting customer churn for a telecommunications company using Machine Learning and Deep Learning techniques. The goal is to identify customers likely to discontinue services, allowing the company to take proactive retention measures.

---

## 🧠 Project Overview

Customer churn is a critical problem in the telecom industry. Using the **Telco Customer Churn Dataset**, this project builds and evaluates predictive models to classify whether a customer will churn based on their service usage patterns, demographics, and account information.

---

## 🗂️ Dataset

- **Dataset Source**: [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Rows**: ~7,000 customers  
- **Columns**: 21 features (categorical and numerical)

### Key Features
- **Customer demographics**: gender, senior citizen, partner, dependents  
- **Account information**: contract type, payment method, tenure  
- **Services**: internet service, streaming, online security, etc.  
- **Target**: `Churn` (Yes/No)

---

## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Handling missing values and inconsistent entries  
   - Encoding categorical features  
   - Scaling numerical variables using `MinMaxScaler`

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn rates across demographics and service categories  
   - Identified key churn drivers using correlation analysis

3. **Model Building**
   - Implemented multiple classification models  
   - Final model: **Neural Network (Keras Sequential API)**  

4. **Model Evaluation**
   - Evaluated using **Accuracy**, **AUC-ROC**, **Precision**, **Recall**, and **F1-Score**
   - Visualized **Confusion Matrix** and **ROC Curve**

---

## ✨🧑‍💻 Author
**Rajeev Mishra**  
MBA in Data Science & Analytics | Data Analyst | Python | SQL | Power BI  
[LinkedIn](https://www.linkedin.com/in/rajeevmishra12/) | [Kaggle Profile](https://www.kaggle.com/rajeevmishraa)

             → Dense(32, ReLU)
             → Output Layer (Sigmoid)
