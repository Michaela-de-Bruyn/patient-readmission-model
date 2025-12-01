# 🧠 Patient Readmission Prediction Using Machine Learning
### 📌 1. Business Problem

Hospital readmissions within 30 days are costly, reduce hospital efficiency, and signal potential complications in patient care. Being able to predict which patients are likely to be readmitted enables hospitals to:
🧠 Patient Readmission Prediction Using Machine Learning
📌 1. Business Problem

Hospital readmissions within 30 days are costly, reduce hospital efficiency, and signal potential complications in patient care. Being able to predict which patients are likely to be readmitted enables hospitals to:

* Improve discharge planning
* Allocate resources more effectively
* Prioritize high-risk patients
* Reduce avoidable readmission costs

### Business Question:

Can we use patient demographic, clinical, and admission-related data to predict the likelihood of hospital readmission within 30 days?

### 🎯 2. Project Objectives

* Perform exploratory data analysis (EDA) to understand patient characteristics
* Investigate which factors influence readmission risk
* Build multiple machine learning models and compare their performance
* Identify the best-performing model for predicting readmission
* Document insights and recommendations for hospital decision-makers

### 📊 3. Dataset Overview

The dataset contains patient-level records, including:

* Demographics: Age, Gender
* Admission details: Admission Type, Length of Stay
* Clinical indicators: Blood Pressure, Sugar Levels
* Outcome: Readmitted (Yes/No)
* The dataset used in this project is synthetic and does not contain real patient information.

### 🔍 4. Exploratory Data Analysis (EDA)

* Admission Type Analysis
* Gender Distribution
* Correlation Between Clinical Features
* Clinical Indicators
* Readmission Patterns

### 🛠️ 5. Data Preparation & Feature Engineering

Key steps included:

* Handling missing values
* Encoding categorical features
* Standardizing numerical features
* Creating new derived features
* Train–test split (80/20)

### 🤖 6. Machine Learning Models Built

The following models were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* Support Vector Classifier (SVC)
* K-Nearest Neighbors (KNN)
* Naive Bayes

Each model was evaluated using accuracy, confusion matrices, and classification reports.

### 📈 7. Model Evaluation

* Confusion Matrices for Models
* Logistic Regression
* Random Forest
* Decision Tree
* Gradient Boosting
* K-Nearest Neighbors
* Support Vector Classifier
* Naive Bayes

### 🏆 8. Best Model & Key Insights

Based on accuracy, precision, recall, and confusion matrix interpretation, the top-performing model was:

⭐ Random Forest Classifier

Key predictive insights:

* Certain admission types were strongly associated with higher readmission risk
* Abnormal blood pressure and sugar levels indicated potential complications
* Length of hospital stay played a significant role in readmission likelihood
* Gender and age groups showed differing readmission patterns

### 🚧 9. Limitations

* Dataset is synthetic; may not fully represent real hospital scenarios
* No diagnosis codes or comorbidity indicators included
* Some clinical features were simplified
* No hyperparameter tuning applied yet

### 🚀 10. Future Improvements

* Add real clinical variables (diagnosis, comorbidities, procedures)
* Implement Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
* Add ROC curves and AUC scores
* Build a full end-to-end MLOps pipeline
* Deploy the model with a simple API or Streamlit interface


### 🏥 10. Ethical Note

This project uses synthetic patient data for educational purposes.
No real patient information is used or stored.

### 🙌 11. Acknowledgements

_This project was completed as part of the BrightLight ML Bootcamp._


