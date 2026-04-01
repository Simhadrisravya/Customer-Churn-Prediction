
# 📊 Customer Churn Prediction

## 📌 Project Overview
This project predicts whether a customer will churn (leave the service) using machine learning techniques.  
The goal is to help businesses identify at-risk customers and take preventive actions.


## 📂 Dataset
The dataset contains customer details such as:
- Gender
- Tenure
- Monthly Charges
- Contract Type
- Internet Services
- Payment Method


## 🧹 Data Preprocessing
- Handled missing values in `TotalCharges`
- Converted categorical variables using one-hot encoding
- Removed unnecessary columns (customerID)


## 📊 Exploratory Data Analysis (EDA)

### Key Insights:
- Customers with **month-to-month contracts** churn more
- Customers with **high monthly charges** have higher churn rate
- Customers with **low tenure** are more likely to churn


## 📈 Model Building
Models used:
- Logistic Regression
- Decision Tree
- Random Forest


## 📊 Model Performance
- Logistic Regression Accuracy: 0.80
- Random Forest Accuracy: 0.85
- AUC Score: 0.87


## 📉 ROC Curve
<img width="1920" height="929" alt="ROC Curve comparison" src="https://github.com/user-attachments/assets/d89f6b28-1ca2-4333-8bf1-5505a183775b" />


## 📊 Dashboard Insights

<img width="1911" height="709" alt="Screenshot" src="https://github.com/user-attachments/assets/cdec2a1a-0cb0-4e91-b63a-0503b351c535" />

<img width="1885" height="720" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/95cc52fa-5471-423a-9050-d67adaa1c50f" />


## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📊 Key Insights

- Customers with month-to-month contracts have higher churn rate
- High monthly charges increase churn probability
- Customers with low tenure are more likely to churn
- Long-term contract customers are more stable


## 🚀 Future Improvements
- Hyperparameter tuning
- Try advanced models (XGBoost)
- Deploy using Streamlit


## 📌 Conclusion
This project demonstrates how machine learning can be used to predict customer churn and generate actionable business insights.

