💳 **Credit Scoring Model using Random Forest**

This project builds a machine learning model to predict an individual's creditworthiness using historical financial data from the **German Credit dataset**.

📌 **Objective**

Classify whether a person is **creditworthy** based on features like **income, debts, and payment history**.

🧠 **Approach**

**Preprocessing**
  - One-hot encoding of categorical variables  
  - Train-test split (80/20)  
 **Model**
  - Random Forest Classifier with 100 estimators  
**Evaluation**
  - Classification report (Precision, Recall, F1-Score)  
  - ROC-AUC Score  
  - Feature importance analysis 

📁 **Dataset**
- **Source:** `german.csv` (semicolon-separated)  
- **Target Variable:** `Creditability` (1 = creditworthy, 0 = not creditworthy)  
- **Features:** Demographic and financial attributes  

🧪 **Features**
- One-hot encoded categorical variables  
- Random Forest model trained on 80% of the data  
- Top 5 most influential features identified 

📊 **Results**
- **Classification Report:**
<img width="628" height="256" alt="image" src="https://github.com/user-attachments/assets/1c14c7fd-b9fc-45e7-baae-749c28f75d4c" />

- **ROC-AUC Score:** `0.7633`  

**Top Risk Factors:**  
- Credit_Amount — 0.136  
- Account_Balance — 0.106  
- Age_years — 0.104  
- Duration_of_Credit_monthly — 0.104  
- Payment_Status_of_Previous_Credit — 0.065  

🧰 **Libraries Used**
- `pandas`, `numpy`, `matplotlib`  
- `sklearn` for modeling and evaluation  

🚀 **How to Run**
1. Clone the repo  
2. Install dependencies:  
   pip install -r requirements.txt  
3. Run the script:  
   python credit_scoring.py
    
