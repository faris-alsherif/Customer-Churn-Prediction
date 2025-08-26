# Customer Churn Prediction (Classification)

## 📌 Project Overview
This project focuses on predicting whether a customer will leave a telecom service (churn) or not.  
Customer churn prediction is a classic **binary classification problem**, which is very important in business analytics to help companies retain their customers.

## 📂 Dataset
We used the **Telco Customer Churn Dataset** from Kaggle.  
[🔗 Kaggle Link: Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)

## 🎯 Objectives
- Predict customer churn (Yes/No).  
- Explore relationships between customer features (e.g., contract type, internet service, monthly charges) and churn.  
- Build and evaluate classification models to find the most effective one.  

## 🛠️ Key Steps
1. **Load & Explore**  
   - Analyzed the dataset.  
   - Checked churn rate and data balance.  
   - Explored relationships between features and target variable (`Churn`).  

2. **Clean & Prepare**  
   - Handled missing values.  
   - Converted categorical features into numerical values (e.g., Yes=1, No=0).  
   - Scaled numerical features such as `tenure` and `MonthlyCharges`.  

3. **Preprocessing**  
   - Applied feature encoding and scaling.  
   - Prepared the dataset for model training.  

4. **Build & Train Models**  
   We trained two classification models:  
   - **Logistic Regression Model**  
   - **Random Forest Model**  

5. **Evaluate & Compare**  
   - Used **Confusion Matrix, Accuracy, Precision, Recall** for evaluation.  
   - Since churn is a rare event, **Recall** was considered very important.  
   - Compared both models to determine the better performer.  

## 📊 Results
- Logistic Regression and Random Forest were compared.  
- Random Forest generally performed better in terms of capturing churners (higher recall).  
- Key predictors included **Contract Type, Internet Service, Tenure, and Monthly Charges**.  

## 📓 Notebook
The full implementation, including data exploration, preprocessing, model training, and evaluation, can be found in the notebook:  
[🔗 Project Notebook](https://github.com/faris-alsherif/Customer-Churn-Prediction/blob/main/Project_Customer_Churn_Prediction.ipynb)

## 👥 Team Members
This project was completed by **6 team members**:  

- Member 1: Faris Sherif Taha  
- Member 2: Fahd Sherif Taha
- Member 3: Mahmoud Waheed Mahmoud
- Member 4: Shahd Elsayed Hosney
- Member 5: Shahd Moatasem
- Member 6: Belal Adel Hassan

---
