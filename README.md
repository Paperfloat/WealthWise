# WealthWise

# NSAP Scheme Eligibility Prediction using Machine Learning

This project aims to automate the classification of applicants into appropriate sub-schemes of the **National Social Assistance Program (NSAP)** using **multi-class classification** techniques. It is built and deployed using **IBM Cloud services**.

---

## 🔍 Problem Statement

The National Social Assistance Program (NSAP) offers financial aid to elderly individuals, widows, and persons with disabilities from Below Poverty Line (BPL) households. Manually verifying applications and assigning schemes is time-consuming and prone to errors.

This project uses machine learning to **predict the correct NSAP scheme** for a given applicant based on socio-economic and demographic data.

---

## 🎯 Objectives

- Predict the most appropriate NSAP scheme for applicants  
- Automate and speed up the classification process  
- Ensure accurate and timely benefit distribution  
- Deploy the model on IBM Cloud for public service usage

---

## 🧠 Machine Learning Model

- **Type:** Multi-class Classification  
- **Algorithm Used:** Random Forest (best performer)  
- **Other Models Evaluated:** Logistic Regression, XGBoost

### 🔢 Input Features

- State Name  
- District Name
- Gender  
- Category (SC/ST/OBC/General)  

### 🛠️ Preprocessing

- Missing value handling  
- Label encoding of categorical variables  
- Normalization of numerical features  
- Train-test split (80/20)  

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision   
- Confusion Matrix

---

## 📊 Results

✅ **Confusion Matrix:**
confustion_matrix.png

✅ **Sample Predictions:**
Welfare_Wise _test_input

✅ **Results Sample Predictions:**
result_prediction.png

---

## 🚀 Deployment (IBM Cloud)

- Model trained and saved as `.pkl`  
- Hosted on **IBM Watson Studio**  
- Assets stored in **IBM Cloud Object Storage**  
- Deployed via REST API for real-time predictions




