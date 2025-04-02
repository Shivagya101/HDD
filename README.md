# HDD

📌 Overview
This project predicts the presence of heart disease using machine learning. It is based on the Kaggle Heart Disease UCI dataset. The model takes patient health parameters as input and determines the likelihood of heart disease.

## 📂 Dataset
The dataset consists of 303 records with 14 clinical features, including age, cholesterol levels, blood pressure, and chest pain type. The target variable (target) indicates the presence (1) or absence (0) of heart disease.

## 🛠️ Approach <br>
Exploratory Data Analysis (EDA):

Visualized feature distributions

Identified correlations and outliers

Handled missing values

Feature Engineering:

Scaled numerical features

Encoded categorical variables <br>

## Model Selection & Training:

Evaluated multiple classifiers: Logistic Regression, Random Forest, XGBoost, etc.

Used GridSearchCV for hyperparameter tuning

Assessed models using accuracy, precision, recall, and F1-score

after hyperparameter tuning improved scores---- <br>
KNN: 0.639344262295082 to 0.6885245901639344
<br> LGR': 0.9016393442622951 to 0.9016393442622951(no improvement)
<br> RFC: 0.8688524590163934 to 0.9508196721311475

