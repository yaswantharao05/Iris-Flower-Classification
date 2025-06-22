# 🌸 Iris Flower Classification

A simple machine learning project to classify the species of an iris flower using its petal and sepal dimensions. Built as part of a learning exercise to practice ML fundamentals using Scikit-learn.

---

## 📌 Project Overview

This project involves building a classification model using the **Iris dataset**, one of the most well-known datasets in the machine learning community. The goal is to predict the species of an iris flower (Setosa, Versicolor, Virginica) based on the following features:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

---
 
## 🧠 Algorithms Used

- K-Nearest Neighbours (KNN)  
- Decision Tree Classifier *(Optional comparison)*

---

## 🔧 Tech Stack

- Python  
- Scikit-learn  
- Pandas  
- Matplotlib / Seaborn *(for data visualization)*

---

## 📊 Steps Followed

1. **Loaded the Dataset:**  
   Used `sklearn.datasets.load_iris()` to load the Iris dataset.

2. **Data Exploration:**  
   - Plotted scatter plots and histograms to understand data distribution.
   - Checked correlations between features.

3. **Data Preprocessing:**  
   - Split the data into training and testing sets using `train_test_split`.

4. **Model Selection & Training:**  
   - Chose K-Nearest Neighbours as the baseline model.
   - Trained the model using the training set.

5. **Model Evaluation:**  
   - Tested the model on the test set.
   - Evaluated accuracy, confusion matrix, and classification report.

6. **Prediction on New Data:**  
   - Used the trained model to predict species based on user-input flower measurements.

---

## 📌 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/iris-flower-classification.git
   cd iris-flower-classification
