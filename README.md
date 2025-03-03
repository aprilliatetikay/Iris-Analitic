# 🌸 Iris Data Analysis with KNN & Linear Regression

## 📌 Project Overview

This project explores the application of **K-Nearest Neighbors (KNN) Classification** and **Linear Regression** on the well-known **Iris dataset**. The objective is to classify flower species and analyze relationships between features using these machine learning techniques.

### 🔍 Key Components:
- **Exploratory Data Analysis (EDA)** to understand dataset patterns.
- **KNN model** for species classification.
- **Linear Regression** for analyzing numerical feature relationships.
- **Implementation in Python using Jupyter Notebook.**

---

## 📂 The Iris Dataset

The **Iris dataset** consists of **150 observations** of iris flowers, categorized into three species:

- **Setosa**
- **Versicolor**
- **Virginica**

### 🌿 Features in the Dataset:
| Feature Name  | Description                          |
|--------------|----------------------------------|
| Sepal Length | Length of the sepal in cm       |
| Sepal Width  | Width of the sepal in cm        |
| Petal Length | Length of the petal in cm       |
| Petal Width  | Width of the petal in cm        |
| Species      | Class label (Setosa, Versicolor, Virginica) |

---

## 🤖 K-Nearest Neighbors (KNN) Model

### 🔹 How KNN Works:
- KNN is a **supervised learning algorithm** for classification.
- It classifies a data point based on the majority class of its **K** nearest neighbors.
- Distance metrics (e.g., **Euclidean distance**) measure proximity between points.

### 🔹 Application in This Project:

✅ The KNN model is trained using **Sepal and Petal dimensions** to classify Iris species.

✅ **Hyperparameter K** is optimized for better accuracy.

✅ Model evaluation using **accuracy score** and **confusion matrix**.

---

## 📈 Linear Regression Model

### 🔹 Why Use Linear Regression?
- Helps identify relationships between numerical variables.
- Predicts one feature based on another (e.g., **Petal Length vs. Petal Width**).

### 🔹 Application in This Project:

✅ **Simple Linear Regression** analyzes relationships between petal/sepal dimensions.

✅ The model estimates **regression coefficients** (slope & intercept).

✅ Performance is evaluated using **Mean Squared Error (MSE)** and **R² score**.

---

## 🛠️ How to Run the Jupyter Notebook

### 🔹 1. Install Dependencies
Ensure you have the required Python libraries installed:
```sh
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 🔹 2. Run the Notebook
Open Jupyter Notebook and execute the project step by step:
```sh
jupyter notebook
```
Load **MPML_20221_672020021.ipynb** and run all cells.

---

## 📊 Key Insights from the Analysis

✅ **KNN achieves high accuracy** in classifying Iris species, with an optimized K value.

✅ **Petal dimensions** have strong correlations, making them reliable predictors.

✅ **Linear Regression effectively models** relationships between petal/sepal features.

✅ **Setosa is the most distinct species**, while Versicolor and Virginica have overlapping feature distributions.

These insights demonstrate the power of machine learning in **pattern recognition** and **predictive modeling**.

---

## 📌 Conclusion

This project showcases the application of **KNN Classification** and **Linear Regression** in analyzing and modeling the **Iris dataset**. By understanding these fundamental ML techniques, we gain valuable skills in **data-driven decision-making** and **predictive analytics**.

🚀 **Explore the notebook and dive into the world of machine learning!**
