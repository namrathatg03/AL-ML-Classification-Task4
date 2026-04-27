# 🧠 AI/ML Task 4: Classification Models & Evaluation

## 📌 Overview

This project demonstrates a binary classification system using the Breast Cancer dataset.
It focuses on evaluation metrics, ROC curve, and handling class imbalance.

## 📊 Dataset

* Breast Cancer Dataset (scikit-learn)
* 569 samples
* 30 features
* Target:

  * 0 → Malignant
  * 1 → Benign

## ⚙️ Models Used

* Logistic Regression (Baseline)
* Logistic Regression (Balanced)
* Decision Tree Classifier

## 📈 Evaluation Metrics

* Confusion Matrix
* Precision, Recall, F1-score
* ROC Curve & AUC

## 🚀 Results

* Logistic Regression performed best overall
* F1-score provided better evaluation than accuracy
* ROC-AUC showed strong model performance

## ⚖️ Handling Imbalance

Used:

class_weight = 'balanced'

## 📊 Outputs

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

### ROC Curve

![ROC Curve](images/roc_curve.png)

## 📂 Project Structure

├── AI_ML_Task4_Classification.ipynb
├── Task4_Report.pdf
├── images/
│   ├── confusion_matrix.png
│   └── roc_curve.png

## 🧠 Key Learnings

* Accuracy is not enough for imbalanced data
* Recall is critical in medical diagnosis
* ROC-AUC is a strong performance indicator

## 🔧 Tools Used

* Python
* scikit-learn
* pandas, numpy
* matplotlib
* 
## 👨‍💻 Author

Your Name
Namratha T G
