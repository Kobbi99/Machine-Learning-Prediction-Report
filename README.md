# Machine-Learning-Prediction-Report
This project used machine learning to predict type 2 diabetes in Pima Indian women. A calibrated Random Forest model was chosen for its high recall (0.889) and strong clinical relevance. Key predictors matched known risk factors, highlighting ML's role in early, ethical diabetes detection.

Used a cleaned version of the Pima Indians Diabetes dataset (768 patients, 8 health metrics) to predict Type 2 diabetes. After exploratory data analysis and preprocessing (imputation, scaling), several classification models were tested. A calibrated Random Forest model was selected for its high recall (0.889), helping minimize false negatives — critical in a medical context.

Key performance metrics:

Recall: 0.889

Precision: 0.552

Accuracy: 0.708

ROC-AUC: 0.832

Brier Score: 0.180 (calibrated)

Top predictors: Glucose, BMI, Age, Pregnancies, and Pedigree Function.

Additional work included hyperparameter tuning, ROC analysis, confusion matrix visualization, and feature importance ranking.

Compared models: Logistic Regression, SVM, XGBoost, KNN, and Naïve Bayes.

This project demonstrates the application of interpretable machine learning in healthcare and highlights the importance of recall and calibration for ethical decision-making.
