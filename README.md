# 🧠 Machine Learning Foundations: Algorithms & Comparative Analysis

## 📌 Project Overview
This repository is a curated collection of foundational Machine Learning implementations. It explores the behavior, performance, and mathematical trade-offs of various algorithms across both classification and regression tasks. 

Instead of treating models as "black boxes," these notebooks focus on comparative analysis—evaluating how algorithm complexity affects training time, decision boundaries, and error rates.

## 🗂️ Datasets Utilized
* **Classification:** Iris Dataset (predicting species based on sepal/petal dimensions).
* **Regression:** Diabetes Dataset (predicting disease progression based on baseline metrics).

---

## 📓 Notebook Collection

### 1. Non-Linear Classification using SVM
* **File:** `Non_Linear_Classification_using_Polynomial_Kernal.ipynb`
* **Focus:** Support Vector Machines (SVM).
* **Key Insight:** Explores the "Kernel Trick" using a Polynomial Kernel (Degree 3) to map data into higher-dimensional spaces, allowing for complex decision boundaries on data that is not linearly separable.

### 2. Decision Tree Classification & Regression
* **File:** `Decision_Tree_Classification_and_Regression.ipynb`
* **Focus:** CART algorithms and hyperparameter tuning.
* **Key Insight:** Demonstrates the speed of standard Decision Trees compared to SVMs. It highlights a critical flaw in single Decision Trees for continuous regression data—the creation of "step-function" boundaries that result in high Mean Squared Error (MSE).

### 3. Ensemble Learning Mastery
* **File:** `Ensemble_Learning_Classification_and_Regression.ipynb`
* **Focus:** Random Forest, AdaBoost, and Gradient Boosting.
* **Key Insight:** Proves how combining multiple weak learners directly solves the variance and overfitting issues of the single Decision Tree. The Gradient Boosting Regressor drastically reduced the MSE compared to the standard tree, proving the power of ensemble architectures.

---

## 🤝 Author
**Mohamed Amgad** - AI Engineering
