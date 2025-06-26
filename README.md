# Heart_Disease_Prediction
# ❤️ Heart Disease Prediction using Machine Learning

This project predicts the likelihood of heart disease using various machine learning algorithms. It uses patient medical attributes like age, cholesterol, blood pressure, etc., to classify whether the patient is likely to have heart disease.

## 📁 Dataset

The dataset is available.  
It contains features like:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- Rest ECG
- Max heart rate
- Exercise-induced angina
- ST depression
- Slope of ST segment
- Number of major vessels
- Thalassemia

The target variable indicates the presence (1) or absence (0) of heart disease.

---

## 📊 Models Used

The following machine learning models were implemented and compared:

- ✅ Logistic Regression
- ✅ Random Forest Classifier
- ✅ Gradient Boosting 

Hyperparameter tuning was done using Grid Search and cross-validation.

---

## 🔍 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Curve

---

## 📌 Results

| Model              | Best Parameters                                                                         | CV Score | Test Accuracy |
|--------------------|-----------------------------------------------------------------------------------------|----------|---------------|
| Logistic Regression| `{'C': 0.01, 'penalty': 'l2', 'solver': 'lbfgs'}`                                       | 81.93%   | **82.07%**    |
| Random Forest      | `{'max_depth': 10, 'min_samples_leaf': 2, 'min_samples_split': 5, 'n_estimators': 100}` | 83.02%   | **84.78%**    |
| Gradient Boosting  | `{'learning_rate': 0.01, 'max_depth': 3, 'n_estimators': 200, 'subsample': 1.0}`        | 81.79%   | **84.78%**    |

---



