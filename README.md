# Task 4: Logistic Regression Classification

## Objective

Build a Logistic Regression model for binary classification and evaluate its performance using standard machine learning metrics.

---

## Dataset

**Breast Cancer Wisconsin Dataset**

* Records: 569
* Features: 30
* Target Classes:

  * 0 = Malignant
  * 1 = Benign

Dataset Source:
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

---

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Missing Value Analysis
4. Correlation Analysis
5. Feature Scaling using StandardScaler
6. Train-Test Split
7. Logistic Regression Model Training
8. Prediction
9. Model Evaluation
10. ROC Curve Analysis
11. Sigmoid Function Visualization
12. Threshold Tuning
13. Feature Importance Analysis

---

## Model Performance

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 98.25% |
| Precision | 98.61% |
| Recall    | 98.61% |
| ROC-AUC   | 99.54% |

---

## Visualizations

* Target Distribution
* Correlation Heatmap
* Confusion Matrix
* ROC Curve
* Sigmoid Function
* Feature Importance Chart

---

## Key Insights

* Logistic Regression achieved excellent classification performance.
* ROC-AUC close to 1 indicates strong class separation.
* Precision and Recall are balanced, minimizing classification errors.
* Feature importance analysis highlights the most influential predictors.
* The model successfully distinguishes malignant and benign tumors.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Repository Structure

```text
Task-4-Logistic-Regression/
│
├── task4_logistic_regression.ipynb
|__README.md

```

---

## Author

Sonali Gupta

Implemented Logistic Regression for breast cancer classification with comprehensive evaluation and visualization.

