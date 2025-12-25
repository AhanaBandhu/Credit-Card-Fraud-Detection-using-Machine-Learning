#  Credit Card Fraud Detection using Machine Learning

##  Project Overview
This project focuses on detecting fraudulent credit card transactions using supervised machine learning techniques. The system analyzes transaction patterns to classify transactions as **fraudulent** or **legitimate**, addressing real-world challenges such as data imbalance and financial risk mitigation.

---

##  Project Goals
- Build effective machine learning models for fraud detection  
- Compare the performance of multiple classification algorithms  
- Handle highly imbalanced transaction data  
- Gain practical exposure to real-world financial anomaly detection  

---

##  Algorithms Implemented
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  
- Support Vector Machine (SVM)  

Each algorithm is implemented in a separate Jupyter Notebook for clarity and comparison.

---


---

##  Dataset Description
Data Source
The dataset was retrieved from an open-source website, Kaggle.com. It contains data on transactions made in 2013 by European credit card users in two days only. Thedataset consists of 31 attributes and 284,808 rows. Twenty-eight attributes are numeric variables that, due to the confidentiality and privacy of the customers, have been transformed using PCA transformation; the three remaining attributes are ”Time”, which contains the elapsed seconds between the first and other transactions of each Attribute, ”Amount” is the amount of each transaction, and the final attribute “Class” which contains binary variableswhere “1” is a case of fraudulent transaction, and “0” is not as case of fraudulent transaction.
-DATASET- [Kaggle Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)


---

##  Project Workflow
1. Data loading and exploration  
2. Data preprocessing and feature scaling  
3. Model training and prediction  
4. Model evaluation and comparison  

---

##  Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

##  Technologies Used
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

##  Future Enhancements
- Implement ensemble models such as Random Forest and XGBoost  
- Apply advanced imbalance handling techniques (SMOTE)  
- Perform hyperparameter tuning  
- Deploy the model using Flask or FastAPI  

