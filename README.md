
#**Heart Disease Prediction**

This project implements a machine learning model to predict the presence of heart disease using clinical data. The goal is to assist healthcare professionals in early diagnosis by leveraging predictive analytics and data science techniques.

**Project Overview**
Heart disease is a leading cause of death worldwide, making early detection critical for effective treatment. This project uses patient health metrics to build classification models that can predict the likelihood of heart disease.

**Features**

**Data Preprocessing:** Includes data cleaning, normalization, and encoding to prepare raw clinical data for modeling.

**Feature Selection:** Uses Boruta algorithm to identify important features affecting prediction accuracy.

**Modeling:** Compares several machine learning algorithms including Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Random Forest, and Artificial Neural Networks (ANN).

**Evaluation**: Models are evaluated using accuracy, precision, recall, F1-score, and confusion matrices to measure performance.

**Visualization:** Uses Matplotlib and Seaborn libraries for visual analysis of data distribution and model results.

**Dataset**
The model is trained on the well-known UCI Heart Disease Dataset, which includes patient clinical attributes such as age, blood pressure, cholesterol levels, and more.

**How to Use**
Load the dataset and perform necessary preprocessing steps.
Train multiple classification models and compare their performance.
Evaluate models using relevant metrics to select the best performing one.
Visualize the results to interpret model effectiveness.

**Technologies Used**
Python
Scikit-learn
Pandas
NumPy
Matplotlib
Seaborn
Keras / TensorFlow (for ANN)

**Outcome**
This project demonstrates the application of machine learning techniques in healthcare analytics, providing a foundation for predictive models that can support early diagnosis and treatment decisions.

