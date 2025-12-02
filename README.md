Fuzzy-Based Digestive Risk Prediction System
This project predicts digestive health risk (Low, Medium, High) using a hybrid approach of Fuzzy Logic and Machine Learning.
It analyzes lifestyle factors such as meal frequency, water intake, sleep, stress, and food habits.

Features
Fuzzy membership functions for lifestyle parameters
Expert-based fuzzy rules for digestive risk scoring
Machine Learning (Random Forest) for improved accuracy
Handling of missing values and imbalanced data
Feature engineering for enhanced prediction performance
Hyperparameter tuning using GridSearchCV
Dataset
Collected using Google Forms.
Includes:

Meal frequency
Food risk score
Water intake
Sleep hours
Stress level
Activity level
Engineered features (meal × risk, stress × sleep, water-per-meal)
Fuzzy Logic
Triangular & trapezoidal membership functions
Linguistic labels: Low, Medium, High
Fuzzy rules inspired by lifestyle-health relationships
Defuzzification produces a digestive risk score
Machine Learning Pipeline
SimpleImputer
RandomOverSampler
StandardScaler
RandomForestClassifier
GridSearchCV for tuning
Results
Balanced classes after fuzzy tuning
Improved accuracy and F1-score
Better interpretability compared to threshold-based systems
Technologies Used
Python
NumPy
Pandas
Scikit-learn
Scikit-fuzzy
Google Colab
GitHub
How to Run
Clone the repository
Open the .ipynb file in Google Colab or Jupyter Notebook
Install required libraries
Run all cells
View digestive risk output
Author
R Vignesh
Department of Computer Science and Engineering

License
This project is for academic and research purposes.
