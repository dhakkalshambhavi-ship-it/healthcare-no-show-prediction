# healthcare-no-show-prediction
Explainable machine learning model to predict healthcare appointment no-shows and analyze access inequality
# AI-driven Analysis of Healthcare Access Inequality

 📌 Overview
Missed medical appointments reduce healthcare efficiency and delay critical diagnoses. This project builds a machine learning model to predict patient no-shows and identify key factors contributing to healthcare access inequality.



 🎯 Problem Statement
Healthcare systems face significant inefficiencies due to patient no-shows. This project aims to:
- Predict whether a patient will miss an appointment
- Identify key drivers behind no-shows
- Provide actionable insights for healthcare improvement



 📊 Dataset
- Source: Kaggle Medical Appointment Dataset
- Records: ~110,000 appointments
- Features include:
  - Age, Gender
  - Scholarship (socioeconomic indicator)
  - Medical conditions (diabetes, hypertension)
  - SMS reminders
  - Appointment scheduling details



 🛠️ Methodology

 1. Data Cleaning
- Removed irrelevant identifiers
- Converted categorical variables to numerical
- Handled inconsistencies in target variable

 2. Feature Engineering
- Created `waiting_days` feature (time between scheduling and appointment)

 3. Exploratory Analysis
- Identified trends in no-show behavior
- Observed impact of SMS reminders and socioeconomic factors

 4. Model Building
- Algorithm: Random Forest Classifier
- Handled class imbalance using weighted training



 📈 Model Performance

- **ROC-AUC Score:** 0.73  
- **Recall (No-show):** 82%  

The model effectively identifies high-risk patients, making it useful for healthcare intervention strategies.



 🔍 Key Insights

- Waiting time is the strongest predictor of no-shows
- Younger patients are more likely to miss appointments
- Socioeconomic factors influence healthcare access
- SMS reminders are associated with higher no-show rates (likely targeted intervention)



 🏥 Practical Implications

- Hospitals can identify high-risk patients in advance
- Reduce missed appointments through targeted interventions
- Optimize scheduling systems to minimize waiting time



⚠️ Limitations

- Lack of behavioral and geographic data
- Model does not capture patient motivation or accessibility barriers



 🚀 Future Improvements

- Incorporate location-based features
- Use advanced models like XGBoost
- Deploy as a web application using Streamlit



 🧠 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn



## 👩‍💻 Author

- SHAMBHAVI DHAKAL
