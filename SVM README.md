**Wine Quality Prediction using Support Vector Machines (SVM)**
This project aims to predict wine quality using various physiochemical properties of wine. It explores both classification and regression approaches with Support Vector Machines
(SVM) to determine the quality score of wine.

**Project Overview:**
Dataset: Utilizes the winequalityN.csv dataset, which contains attributes like fixed acidity, volatile acidity, citric acid, and alcohol content, among others, to predict a wine's quality score.
Data Preprocessing: Features are scaled using StandardScaler to ensure optimal model performance.
**Model Training:**
A Support Vector Classifier (SVC) with a linear kernel is trained for wine quality classification.
A Support Vector Regressor (SVR) with an RBF kernel is trained for predicting a continuous wine quality score.
Evaluation: The models' performances are evaluated using:
Classification metrics like accuracy_score and classification_report for the SVC model.
Regression metrics such as mean_squared_error and r2_score for the SVR model.
**Technologies Used:**
Python
pandas for data handling
scikit-learn for data splitting, scaling, and implementing SVM models (SVC, SVR) and evaluation metrics.
