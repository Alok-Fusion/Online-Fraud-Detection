# 💸 Online Payment Fraud Detection using Machine Learning in Python

> **Developed by:** Alok Kushwaha  
> **Last Updated:** 24 April, 2025

---

## 📥 Download Dataset

👉 [Click here to download the dataset](https://www.kaggle.com/datasets/alokkushwahajitendra/online-payment-fraud)  
(Hosted on Kaggle - Online Payment Fraud)

---

## 📘 Project Description

In the era of digital transformation, online payments are becoming the norm due to their speed and convenience. However, with this convenience comes risk — **fraudulent transactions** have become increasingly common across digital platforms.

This project presents an end-to-end solution for detecting online payment fraud using **Machine Learning in Python**. It is designed as a **Smart Education Guide** to not only build a predictive model but also to educate others on how such systems work in practice.

---

## 🧠 Goal

To accurately identify fraudulent transactions using historical transaction data, ensuring safer digital payment ecosystems.

---

## 📊 Dataset Overview

The dataset used in this project simulates real-world financial transactions and includes the following features:

| Column Name        | Description                                           |
|--------------------|-------------------------------------------------------|
| `step`             | Unit of time for transaction events                  |
| `type`             | Type of transaction (`TRANSFER`, `CASH_OUT`, etc.)   |
| `amount`           | Total amount transferred in the transaction          |
| `nameOrig`         | Sender's account name                                |
| `oldbalanceOrg`    | Sender's balance before the transaction              |
| `newbalanceOrig`   | Sender's balance after the transaction               |
| `nameDest`         | Receiver's account name                              |
| `oldbalanceDest`   | Receiver's balance before the transaction            |
| `newbalanceDest`   | Receiver's balance after the transaction             |
| `isFraud`          | Target label (1 = Fraud, 0 = Not Fraud)              |

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas & NumPy** – for data handling
- **Matplotlib & Seaborn** – for visual analysis
- **Scikit-learn** – for building and evaluating machine learning models
- **Jupyter Notebook** – for step-by-step development and explanation

---

## 📈 Project Workflow

1. **Data Preprocessing**
   - Encoding categorical features
   - Removing redundant columns
   - Handling missing values (if any)

2. **Exploratory Data Analysis (EDA)**
   - Visualizing transaction patterns
   - Understanding correlations and fraud distribution

3. **Model Building**
   - Training a `RandomForestClassifier` to detect fraud
   - Splitting the data into training and test sets

4. **Model Evaluation**
   - Confusion matrix
   - Classification report
   - Feature importance visualization

---

## 📌 Key Outcomes

- A machine learning model capable of detecting fraud with high accuracy.
- Identification of key features that contribute to fraud.
- A step-by-step explanation suitable for educational purposes and practical deployment.

---

## 📬 Author

**Alok Kushwaha**  
👨‍🎓 Master’s in Data Science — SIES College  
💡 Passionate about AI, security, and educational technology  
📫 [LinkedIn Profile](https://www.linkedin.com/in/akushwaha-j/)

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).
