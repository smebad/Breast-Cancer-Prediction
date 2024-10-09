# 🩺 Breast Cancer Prediction using Logistic Regression

Welcome to the **Breast Cancer Prediction** repository! This project leverages the **Breast Cancer Wisconsin (Diagnostic) Dataset** to build a classification model that predicts whether a breast tumor is **benign** or **malignant**. Using **Logistic Regression**, we aim to aid early detection of breast cancer, which is crucial for improving patient outcomes.

## 📂 Project Overview

This project includes:
- **Exploratory Data Analysis (EDA)** to understand the dataset and visualize feature correlations.
- **Data Preprocessing** steps to clean the data and prepare it for model training.
- Building a **Logistic Regression** model to classify tumors.
- Evaluating the model using **accuracy** and a **confusion matrix**.
- Testing the model on a **sample input** to predict tumor malignancy.

## 📊 Dataset

The dataset used is the **[Breast Cancer Wisconsin (Diagnostic) Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)**, which contains features computed from digitized images of fine needle aspirate (FNA) of breast masses, such as the radius, texture, perimeter, area, and smoothness of the cell nuclei.

---

## 🛠️ Tools and Libraries

- **Python** 🐍
- **Pandas** for data manipulation
- **NumPy** for numerical computations
- **Matplotlib** and **Seaborn** for data visualization
- **Scikit-learn** for model building and evaluation

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/smebad/breast-cancer-prediction.git
cd breast-cancer-prediction
```
## 🔍 Exploratory Data Analysis:

We begin by exploring the dataset to understand its structure and key features:

* Missing data is handled by removing unnecessary columns (id, Unnamed: 32).
* The target variable (diagnosis) is converted into numerical values:
  * 0 for Benign
  * 1 for Malignant
  
A heatmap visualizes correlations between features, helping us identify relationships between diagnostic measurements.

## ⚙️ Model Training and Evaluation:
Using Logistic Regression, we train the model on 80% of the data and test it on the remaining 20%. The model achieves:

* Training Accuracy: 96.92%
* Test Accuracy: 95.61%
* Confusion Matrix
The confusion matrix gives us insights into the model's performance, showing how well it distinguishes between benign and malignant tumors.

## 🧪 Sample Prediction:

You can test the model by providing custom input data, and it will predict whether the tumor is benign or malignant. Here's an example input:
``` input = (12.31, 16.52, 79.19, 470.9, 0.09172, 0.06829, 0.03372, 0.02272, 0.172, 0.05914, 
         0.2505, 1.025, 1.74, 19.68, 0.004854, 0.01819, 0.01826, 0.007965, 0.01386, 0.002304, 
         14.11, 23.21, 89.71, 611.1, 0.1176, 0.1843, 0.1703, 0.0866, 0.2618, 0.07609)
```
## 📈 Conclusion:

This project successfully built a Logistic Regression model that accurately predicts whether a tumor is benign or malignant. With over 95% accuracy, this model can aid in the early detection of breast cancer, potentially saving lives through timely diagnosis.

## ⭐️ If you found this project helpful or interesting, please give it a star!

