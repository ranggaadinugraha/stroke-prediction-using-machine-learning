# 🧠 Stroke Prediction Using Machine Learning

This project aims to predict the occurrence of **stroke** based on patient health data using machine learning techniques.  
Several preprocessing methods are applied to improve data quality, and multiple models are compared to evaluate performance.

---

## 📌 Project Objective
- To predict stroke occurrence using healthcare data
- To handle missing values and imbalanced classes
- To compare the performance of different classification models

---

## 🧰 Technologies & Libraries
- Python
- Google Colab
- Pandas & NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib & Seaborn
- Plotly
- Missingno

---

## 📂 Dataset
**Dataset:** Healthcare Stroke Dataset  
The dataset contains patient information such as:
- Age
- Gender
- BMI
- Average glucose level
- Work type
- Smoking status
- Residence type

**Target Variable:**
- `stroke = 1` → Stroke
- `stroke = 0` → Healthy

---

## ⚙️ Project Workflow
1. Load and explore dataset
2. Handle missing values using KNN Imputer
3. Encode categorical features
4. Scale numerical features using MinMaxScaler
5. Handle class imbalance using SMOTE
6. Split dataset into training and testing sets
7. Train machine learning models
8. Evaluate and compare model performance

---

## 🧠 Machine Learning Models
- **Multi-Layer Perceptron (MLP)**
- **K-Nearest Neighbors (KNN)**

Both models are evaluated using classification metrics.

---

## 📊 Model Evaluation
Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

A comparison table is generated to analyze the performance of each model.

---

## 📈 Results
- The dataset was highly imbalanced and successfully balanced using SMOTE.
- Both models performed well, with differences in precision and recall.
- Model comparison results were saved in CSV format for further analysis.

---

## ▶️ How to Run
1. Clone this repository
2. Install required dependencies
```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn plotly missingno pywaffle
