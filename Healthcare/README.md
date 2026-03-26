# Healthcare Appointment No-Show Prediction

## Project Overview
Missed medical appointments (no-shows) are a major challenge for healthcare providers as they lead to inefficient scheduling, revenue loss, and poor resource utilization.  

This project focuses on analyzing patient appointment data and building a machine learning model to predict whether a patient will miss an appointment. The project also includes a Power BI dashboard to visualize insights and support data-driven decision-making.

---

## Objectives
- Analyze factors influencing appointment no-shows  
- Identify high-risk patients using machine learning  
- Handle class imbalance using SMOTE  
- Build an interactive Power BI dashboard  
- Provide business insights to reduce missed appointments  

---

## Dataset
Healthcare appointment dataset containing:

- Gender  
- Age  
- Scholarship  
- Hypertension  
- Diabetes  
- Alcoholism  
- Handicap  
- SMS Received  
- Appointment Date  
- Waiting Days  

### Target Variable
`no_show`
- 0 → Patient attended  
- 1 → Patient missed appointment  

---

## Tools and Technologies

### Programming
- Python  
- Pandas  
- NumPy  

### Visualization
- Matplotlib  
- Seaborn  
- Power BI  

### Machine Learning
- Scikit-learn  
- Decision Tree  
- Random Forest  
- SMOTE (Imbalanced-learn)  

---

## Data Cleaning and Preprocessing
- Removed unnecessary columns  
- Handled missing values  
- Converted categorical and boolean variables to numeric  
- Created new features:
  - Waiting Days  
  - Age Group  
  - Appointment Weekday  
- Prepared dataset for machine learning  

---

## Exploratory Data Analysis (EDA)
- No-show distribution  
- Waiting days vs no-show analysis  
- SMS reminder impact  
- Age group analysis  
- Weekday analysis  

---

## Machine Learning Models

Models used:
- Logistic Regression  
- Decision Tree  
- Random Forest  

### Final Model
Random Forest with SMOTE

Evaluation metrics:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## Dashboard
An interactive Power BI dashboard was created with:

- Total Patients  
- Total No-Shows  
- No-Show Rate  
- Waiting Days Analysis  
- SMS Reminder Impact  
- Age Group Analysis  
- Weekday Trends  

---

## Key Insights
- Approximately **20% of appointments are missed**  
- Longer waiting times increase no-show probability  
- SMS reminders reduce missed appointments  
- Certain age groups are more likely to miss appointments  
- Weekday patterns influence attendance  

---

## Business Recommendations
- Reduce waiting time between scheduling and appointment  
- Implement strong reminder systems (SMS/Calls)  
- Focus on high-risk patient groups  
- Optimize scheduling based on trends  

---

## Conclusion
This project demonstrates how data analytics and machine learning can help predict appointment no-shows and improve healthcare efficiency. By identifying key factors and using predictive models, healthcare providers can reduce missed appointments and optimize resource utilization.

---
