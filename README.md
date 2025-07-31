# 🏦 Home Credit Risk Prediction

This project focuses on predicting whether a loan applicant will be able to repay the loan or not, based on historical customer data provided by Home Credit.

---

## 🎯 Project Objective

The main goal is to build a classification model that predicts the repayment ability of a customer:

- `Target = 1`: The customer **will not be able to repay** the loan (default).
- `Target = 0`: The customer **will repay** the loan on time.

---

## 📊 Dataset

The dataset contains a wide range of features including personal information, financial background, credit history, and more.

Due to its large size, the dataset is stored externally and can be accessed here:

👉 [Download Dataset from Google Drive]((https://drive.google.com/drive/folders/1ARxmp9kHHeS6L5pRewyljzNqjwGYiGFk?usp=drive_link))

---

## 🧹 Data Preprocessing & Analysis

- Handled missing values and outliers.
- Performed EDA (Exploratory Data Analysis) to understand patterns and distributions.
- Found the dataset to be **imbalanced**, so used **SMOTE** to oversample the minority class.

---

## 🧠 Models Trained

1. **Decision Tree**
   - Resulted in overfitting.

2. **Random Forest**
   - Improved accuracy and generalization.

3. **XGBoost**
   - Gave the best performance.
   - Evaluated using **ROC Curve** for visualizing model capability.

---

## 📈 Evaluation

- ROC-AUC was used as a primary metric.
- Accuracy, Precision, and Recall were also considered.
- XGBoost outperformed other models on validation data.

---

## 📝 Notes

- The project is a great example of handling **imbalanced classification**, **data preprocessing**, and model evaluation.
- You can find the full notebook and code in this repository.

---

## 📁 Project Structure

```plaintext
├── HomeCreditProject.ipynb
├── README.md
└── data (not uploaded – see Google Drive link)

