# 💳 Credit Card Customer Churn Prediction using Artificial Neural Network (ANN)

## 📌 Project Overview

This project predicts whether a credit card customer will leave the bank (churn) or continue using the bank's services. The model is built using an Artificial Neural Network (ANN) implemented with TensorFlow/Keras.

---

## 📂 Dataset

- Dataset: Churn_Modelling.csv
- Total Records: 10,000
- Features: 11
- Target Variable: Exited

Target:
- 0 → Customer Stays
- 1 → Customer Exits

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

---

## ⚙️ Project Workflow

1. Data Loading
2. Data Cleaning
3. Feature Selection
4. One-Hot Encoding
5. Train-Test Split
6. Feature Scaling (StandardScaler)
7. Build ANN Model
8. Model Training
9. Model Evaluation
10. Save Model
11. Prediction

---

## 🧠 ANN Architecture

Input Layer (11 Features)

↓

Dense Layer (3 Neurons, ReLU)

↓

Output Layer (1 Neuron, Sigmoid)

---

## 📊 Model Evaluation

Evaluation Metrics:

- Accuracy
- Binary Crossentropy Loss
- Confusion Matrix
- ROC Curve

---

## 📁 Project Structure

```
Credit-Card-Customer-Churn-Prediction/
│
│── Churn_Modelling.csv  
│
├── images/
│   ├── accuracy_curve.png
│   ├── loss_curve.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── model_architecture.png
│
├── models/
│   ├── churn_model.keras
│   └── scaler.pkl
│
├── Credit_Card_Customer_Churn_Prediction.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📷 Results

### Accuracy Curve

(Add accuracy_curve.png)

### Loss Curve

(Add loss_curve.png)

### Confusion Matrix

(Add confusion_matrix.png)

### ROC Curve

(Add roc_curve.png)

### Model Architecture

(Add model_architecture.png)

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Credit-Card-Customer-Churn-Prediction.git
```

Go to the project directory

```bash
cd Credit-Card-Customer-Churn-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

## 👨‍💻 Author

**Shubham Chauhan**

GitHub:
https://github.com/Shubhamspc90

---

## ⭐ If you found this project useful, don't forget to star the repository.