# Prodigy Infotech – Data Science Internship  
## Task 03: Decision Tree Classification  

---

## 📌 Objective
The objective of this task is to build a **Decision Tree Classifier** to predict whether a customer will subscribe to a bank term deposit based on marketing data.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – data loading and manipulation  
- **NumPy** – numerical operations  
- **Scikit-learn** – machine learning model and evaluation  

---

## 📊 Dataset Information
- **Dataset Name:** Bank Marketing Dataset  
- **File Used:** `bank-additional.csv`  
- **Target Variable:** `y`  
  - `yes` → Customer subscribed  
  - `no` → Customer did not subscribe  

The dataset includes customer demographic details, campaign information, and economic indicators.

---

## 🧹 Data Preprocessing
The following preprocessing steps were applied:
- Checked dataset shape, structure, and class distribution
- Converted categorical (object) columns into numerical format using **Label Encoding**
- Separated features (`X`) and target (`y`)
- Split the dataset into training and testing sets (80% training, 20% testing)

---

## 🌳 Model Building
- Algorithm used: **Decision Tree Classifier**
- Splitting criterion: **Gini Index**
- Maximum depth: **5**
- Random state set for reproducibility

---

## 📈 Model Evaluation
The model was evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-score)

These metrics help assess how well the model predicts customer subscription behavior.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-link>
