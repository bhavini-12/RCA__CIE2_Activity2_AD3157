# RCA__CIE2_Activity2_AD3157
# Activity 2: Binary Classification Using Logistic Regression

## 1. Project Title
**Breast Cancer Classification Using Logistic Regression**

## 2. Project Description
The objective of this project is to build a Binary Classification model using Logistic Regression to classify breast cancer tumours as Malignant or Benign.

The model uses numerical features extracted from breast cancer diagnostic data to predict the probability of a tumour being malignant or benign.

This project demonstrates data preprocessing, feature scaling, model training, probability prediction, classification evaluation and threshold comparison.

## 3. Dataset Information

- **Dataset Name:** Breast Cancer Wisconsin Diagnostic Dataset
- **Dataset Source:** Scikit-learn
- **Total Records:** 569
- **Total Features:** 30 numerical features
- **Target Variable:** Diagnosis (Binary Classification)

### Target Classes
- **1 – Malignant:** Cancerous tumour (positive class in this project).
- **0 – Benign:** Non-cancerous tumour (negative class in this project).

### Dataset Features
Some important features include:
- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Compactness
- Mean Concavity
- Mean Symmetry

The dataset contains 30 numerical input features.

**Dataset Source:** https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset

## 4. Work Completed

- Loaded the Breast Cancer Wisconsin Diagnostic dataset.
- Inspected the dataset and its statistical information.
- Checked missing values and duplicate records.
- Analysed the distribution of malignant and benign classes.
- Performed feature preparation and scaling using StandardScaler.
- Divided the dataset into 80% training data and 20% testing data using stratified splitting.
- Studied and visualised the Sigmoid function.
- Implemented Logistic Regression.
- Analysed the model intercept and coefficients.
- Predicted class probabilities and labels.
- Created and analysed the confusion matrix.
- Calculated Accuracy, Precision, Recall, Specificity and F1-score.
- Evaluated the model using ROC-AUC.
- Compared the model with a majority-class baseline.
- Compared decision thresholds of 0.3, 0.5 and 0.7.
- Created the ROC curve and decision behaviour plot.
- Predicted the class of a new example.

## 5. Model Evaluation Results

The Logistic Regression model was evaluated using the following classification metrics:

- **Accuracy:** [Enter actual value]
- **Precision:** [Enter actual value]
- **Recall:** [Enter actual value]
- **Specificity:** [Enter actual value]
- **F1-score:** [Enter actual value]
- **ROC-AUC:** [Enter actual value]

## 6. Threshold Comparison

The model was evaluated using three different decision thresholds:

- Threshold 0.3
- Threshold 0.5
- Threshold 0.7

The comparison helped understand the trade-off between precision and recall and select an appropriate decision threshold.

## 7. Conclusion

In this project, Logistic Regression was implemented to classify breast cancer tumours into malignant and benign categories.

The model was evaluated using different classification metrics, including accuracy, precision, recall, specificity, F1-score and ROC-AUC.

The threshold comparison helped understand how changing the decision threshold affects classification performance. Since false negatives can be particularly serious in cancer screening, recall for malignant cases is an important consideration.

The model provides probability-based predictions and should not be used as a replacement for professional medical diagnosis.

## 8. Faculty GitHub Profile

**Faculty GitHub ID:** [complexiota](https://github.com/complexiota)
