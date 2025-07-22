Customer Satisfaction in Brazilian Mobile Telecom using Machine Learning
This project analyzes customer satisfaction in Brazil's mobile telecommunications sector using machine learning techniques and data from ANATEL (National Telecommunications Agency). The goal is to identify key factors that influence customer satisfaction, especially among "neutral" users according to the Net Promoter Score (NPS).

Dataset
The dataset used in this project is a pre-processed customer satisfaction survey provided by ANATEL and stored in BaseProcessadaNova.xlsx.

Objectives
Predict customer satisfaction based on survey responses.

Compare multiple classification algorithms.

Identify the most important factors affecting satisfaction.

Focus on the role of internet speed and stability in user experience.

Models Used
Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Gaussian Naive Bayes

Support Vector Machine (SVM)

Random Forest

Evaluation
Accuracy Score

Confusion Matrix

Classification Report

10-fold Cross-validation

Hyperparameter tuning using GridSearchCV

Key Findings
The Random Forest algorithm showed the best predictive performance.

Internet quality (speed and stability) is the most critical factor in customer satisfaction.

Analyzing neutral NPS users can provide insights for improving service retention.

Visualizations
Feature importance graphs

Correlation heatmaps

Histograms of variables

Boxplots for model comparison

How to Run
Clone the repository

Place the dataset in the specified path

Run the Jupyter Notebook or Python scripts in your environment

Dependencies
pandas

numpy

matplotlib

seaborn

scikit-learn

missingno

Author
Developed by Luiz Gonzaga Lacerda de Ataíde Neto
For educational and research purposes.
