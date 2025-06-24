# Heart-Disease-Prediction-using-Logistic-Regression
This project applies *Logistic Regression*, a statistical classification algorithm, to predict whether a person is likely to have heart disease based on medical attributes. It demonstrates how machine learning can support early diagnosis and assist healthcare professionals in decision-making.

---

## 📌 Objective

To develop a binary classification model that predicts the presence of heart disease using patient data, improving the chances of early detection and treatment.

---

## 📊 Dataset Overview

- *Dataset Name:* Heart Disease UCI Dataset
- *Source:* https://www.kaggle.com/datasets/oktayrdeki/heart-disease?utm_source=chatgpt.com
- *Target Variable:* target (1 = presence of heart disease, 0 = absent of heart disease)
- *Features Include:*
  - age
  - sex
  - cp (chest pain type)
  - trestbps (resting blood pressure)
  - chol (cholesterol)
  - fbs (fasting blood sugar)
  - restecg (resting ECG results)
  - thalach (max heart rate)
  - exang (exercise-induced angina)
  - oldpeak, slope, ca, thal (various clinical measures)

---

## 🧠 Model Overview

- *Algorithm Used:* Logistic Regression
- *Why Logistic Regression?*
  - Ideal for binary classification problems
  - Outputs probabilities for class membership
  - Interpretable and fast to train

---

## 🔍 Workflow

1. Load and explore the dataset
2. Handle missing values and outliers
3. Perform Exploratory Data Analysis (EDA)
4. Split the dataset into training and testing sets
5. Train the Logistic Regression model
6. Evaluate performance using classification metrics
7. Predict outcomes on new data

---

## ✅ Results

- *Accuracy:* ~85–90%
- *Evaluation Metrics:*
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - ROC-AUC Curve

---

## 💡 Sample Prediction

```python
sample_input = [[63, 1, 3, 145, 233, 1, 0, 150, 0, 2.3, 0, 0, 1]]
prediction = model.predict(sample_input)
print(prediction)
# Output: [1] → Indicates presence of heart disease
