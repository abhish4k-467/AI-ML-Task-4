# AI-ML-Task-4

## By Abhishek Mitra

# 🧠 Logistic Regression on Breast Cancer Dataset

## 📊 Libraries Used

- `pandas` for data manipulation
- `scikit-learn` for ML model and metrics
- `matplotlib` for plotting the ROC curve

This project demonstrates how to build and evaluate a **Logistic Regression** model on a standardized version of the Breast Cancer dataset.

## 📁 Dataset

The dataset used is a pre-processed (standardized) version of the **Breast Cancer Wisconsin Diagnostic Dataset**, with 30 numeric features and a binary target:
- `diagnosis` = 1 → Malignant
- `diagnosis` = 0 → Benign

## 🧪 Steps Followed

### 1. Data Preparation
- Loaded standardized dataset from CSV.
- Split into **training** (80%) and **test** (20%) sets.

  ![image](https://github.com/user-attachments/assets/62e98cd4-4e07-4576-bd8c-8432f229b250)

  ![image](https://github.com/user-attachments/assets/94fd1d38-1347-43ef-adc7-bc3343338418)



### 2. Model Training
- Used `LogisticRegression` from `sklearn`.
- Trained the model on training data.

  ![image](https://github.com/user-attachments/assets/f8b3e339-91ed-4c67-9d24-27ed8ed48511)


### 3. Evaluation
Evaluated model performance using:
- **Confusion Matrix**
- **Precision**
- **Recall**
- **ROC-AUC Score**
- **ROC Curve Visualization**
![image](https://github.com/user-attachments/assets/aa58052f-3ea8-4a41-8e10-cbb371183f5c)

![image](https://github.com/user-attachments/assets/5176d4f1-f05e-4127-86d7-cda36672593c)

### 4. Threshold Tuning
- Threshold - 0.4
  
  ![image](https://github.com/user-attachments/assets/5bd64647-085c-4a10-adf1-48855c953e85)


### 5. Sigmoid Function Explanation
Logistic Regression uses the sigmoid function:

![image](https://github.com/user-attachments/assets/3baf0c61-9ede-456a-9dab-32897cdb959e)

This function maps real-valued inputs to a range between 0 and 1, representing the predicted probability of the positive class.
