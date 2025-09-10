 Diabetes Prediction
- Objective

The goal of this project is to predict whether a person has diabetes based on medical attributes using machine learning models. Different regression and ensemble algorithms were trained, tuned, and compared to achieve the best prediction accuracy.

- Dataset Information

Total Rows (after preprocessing): 639

Attributes:

Pregnancies – Number of pregnancies

Glucose – Plasma glucose concentration

BloodPressure – Diastolic blood pressure (mm Hg)

SkinThickness – Triceps skin fold thickness (mm)

Insulin – 2-Hour serum insulin (mu U/ml)

BMI – Body mass index (weight/height²)

DiabetesPedigreeFunction – Family history score

Age – Age of the patient

Outcome – Target (1 = Diabetic, 0 = Non-Diabetic)

- Key Steps

Data Cleaning & Outlier Removal (IQR method)

Exploratory Data Analysis (EDA)

Model Training: Decision Tree, Random Forest, Gradient Boosting, XGBoost

Performance Evaluation with MAE, MSE, R²

-Results

Ensemble models (Random Forest, Gradient Boosting, XGBoost) performed better than single decision trees, giving higher R² scores and lower errors.

-Tech Stack

Python · Pandas · NumPy · Scikit-learn · XGBoost · Matplotlib · Seaborn
