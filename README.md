# Breast Cancer Classification 🧬

This repository contains a complete machine learning pipeline in a Jupyter Notebook for classifying breast cancer tumors as **malignant** or **benign** using the **Breast Cancer Wisconsin (Diagnostic)** dataset. The project explores various ML models and evaluates their performance using accuracy, confusion matrix, and ROC-AUC.

---

## 📓 Notebook Overview

The notebook `Breast-Cancer-Classification.ipynb` includes:

- 📥 Data loading and preprocessing  
- 🔍 Exploratory Data Analysis (EDA)  
- 📐 Feature scaling and selection  
- 🧠 Training various classification models  
- 📈 Evaluating model performance  
- 🖼️ Visualizing confusion matrix and ROC curves  

---

## 📁 Dataset

- **Source:** [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))  
- **Samples:** 569  
- **Features:** 30 numeric features (mean, standard error, and worst of cell nuclei properties)  
- **Target:**  
  - `M` = Malignant  
  - `B` = Benign  

---

## 🧠 Models Used & Results

| Model                  | Accuracy (%) | 
|------------------------|--------------|
| Logistic Regression    | 97.37%       | 
| K-Nearest Neighbors    | 97.37%       | 
| Support Vector Machine | 96.49%       | 
| Naive Bayes            | 93.86%       | 
| Random Forest          | 94.74%       |

✅ **Best Performing Models:**  
- **K-Nearest Neighbors** and **Logistic Regression** — both achieving **97.37% accuracy**.

---

## 🖼️ Visual Outputs

The notebook includes rich visualizations to understand the data and model performance:

- 🔥 **Heatmap of Feature Correlation**  
  Shows relationships between all 30 features to identify multicollinearity and patterns.

- 📉 **Distribution Plots**  
  Histogram and KDE plots to compare feature distributions for benign and malignant tumors.

- 📊 **Boxplots & Violin Plots**  
  Visualize the spread and outliers of features across tumor classes.

- 💡 **Feature Importance Bar Charts**  
  Provided by tree-based models (like Random Forest and Gradient Boosting).

- 🧩 **Confusion Matrices**  
  For each model to visualize true/false positives and negatives.

- 📈 **ROC Curves**  
  One-vs-rest ROC curves for visual comparison of classification thresholds and AUC.

- 🔁 **Model Comparison Plot**  
  Bar chart comparing accuracies of all models used in the study.


