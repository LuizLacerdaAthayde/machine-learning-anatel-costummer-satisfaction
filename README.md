#📊 Customer Satisfaction in Brazilian Mobile Telecom using Machine Learning
This project applies machine learning techniques to analyze customer satisfaction in Brazilian mobile telecommunications, using official data from ANATEL (Brazil’s National Telecommunications Agency). The study investigates which factors most influence satisfaction, focusing on users rated as "neutral" by the Net Promoter Score (NPS).

📁 Dataset
The dataset used is an ANATEL customer satisfaction survey, pre-processed and stored in an Excel file (BaseProcessadaNova.xlsx).

Main Features:
Brand (MARCA)

State (ESTADO)

Quality of Internet and Voice Services (QF1_2, QF1_3, QF1_5, QF2_1, QIC1)

Customer Experience (PU1 to PU4)

Satisfaction Indexes (P2, P2a, P4, P6)

Socioeconomic Data (ID1 to ID5)

Target variable: NPS

📌 Objectives
Identify the most important attributes affecting mobile telecom satisfaction.

Compare multiple classification models to predict NPS categories (Satisfied vs. Unsatisfied).

Analyze feature importance using decision trees and Random Forests.

⚙️ Technologies and Libraries
Python 3.x

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn (classification models, metrics, preprocessing, model tuning)

Missingno (missing data visualization)

🔍 Models Compared
Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Gaussian Naive Bayes

Support Vector Machine (SVM)

Random Forest

📈 Evaluation Metrics
Accuracy

Confusion Matrix

Classification Report

Cross-validation (10-fold)

GridSearchCV (hyperparameter tuning)

🧠 Key Findings
Random Forest achieved the best predictive performance.

Internet speed and stability were the most critical factors in customer satisfaction.

Neutral NPS users were important to analyze for better retention strategies.

📊 Visualizations
Feature importance via bar plots

Heatmaps of feature correlations

Histograms of feature distributions

Boxplots comparing model accuracy

▶️ How to Run
Clone the repository:

bash
Copiar
Editar
git clone https://github.com/yourusername/telecom-satisfaction-ml.git
cd telecom-satisfaction-ml
Install dependencies:

bash
Copiar
Editar
pip install -r requirements.txt
Run the Jupyter notebook or Python script.

📌 Notes
This project is focused on educational and exploratory purposes.

Data must be manually placed at the expected path (BaseProcessadaNova.xlsx).

📬 Contact
Feel free to reach out via LinkedIn or open an issue in the repository.

