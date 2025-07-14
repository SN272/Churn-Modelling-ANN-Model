# 🧠 Bank Customer Churn Prediction using ANN

This project uses an **Artificial Neural Network (ANN)** to predict whether a bank customer is likely to **churn (leave the bank)** based on personal and transactional attributes. Developed as part of the **"Python for Deep Learning"** course, this model was built from scratch using **Python**, **TensorFlow**, and **scikit-learn**, and run on **Google Colab**.

---

## 🚀 Overview

Customer churn is a key concern for businesses in banking and finance. By analyzing historical customer data, this model classifies customers as likely to **stay** or **leave** using a supervised learning approach.

---

## 🧩 Dataset

The dataset used in this project comes from the [Churn Modelling dataset on Kaggle](https://www.kaggle.com/datasets/shubhendra7/customer-churn-prediction) and contains the following features:

- Credit Score  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- Number of Products  
- Has Credit Card  
- Is Active Member  
- Estimated Salary  
- Exited (Target variable)

---

## 🛠️ Technologies Used

- **Python**  
- **TensorFlow / Keras**  
- **NumPy**  
- **Pandas**  
- **Matplotlib / Seaborn**  
- **scikit-learn**  
- **Google Colab / Jupyter Notebook**

---

## 📈 Model Architecture

The ANN consists of:

- Input layer: 11 input features  
- 2 Hidden layers with ReLU activation  
- Output layer with sigmoid activation (for binary classification)

---

## 📊 Evaluation Metrics

- Accuracy  
- Confusion Matrix  
- Precision, Recall, F1-Score  
- ROC-AUC Curve

---

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SN272/Churn-Modelling-ANN-Model.git
