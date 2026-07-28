# Supervised-Machine-Learning-Regression-and-Classification
This repository contains Jupyter Notebooks from Course 1 of the DeepLearning.AI Machine Learning Specialization: "Supervised Machine Learning: Regression and Classification." It covers implementations of regression, classification, and gradient descent, building a core foundation for bioinformatics ML research workflows.

# Supervised Machine Learning: Regression and Classification
*Course 1: DeepLearning.AI Machine Learning Specialization*

## 📖 About This Repository

This repository contains completed coursework, lab assignments, and Jupyter Notebook implementations from **Course 1 of the DeepLearning.AI Machine Learning Specialization: Supervised Machine Learning: Regression and Classification**. 

It serves as a practical toolkit for understanding the mathematical foundations and programmatic execution of core machine learning algorithms. Beyond isolated coding exercises, these implementations establish the essential baseline for integrating intelligent algorithms into more complex, data-heavy research pipelines. Mastering these foundational supervised learning techniques is the critical first step toward building predictive models for high-dimensional datasets, enabling advanced downstream applications in computational workflows—such as analyzing microbial omics, evaluating complex data structures, and predicting novel biological interactions.

## 🗂️ Repository Contents

The notebooks are organized to reflect a structured progression from single-variable regression to complex classification decision boundaries, featuring both "from-scratch" mathematical builds and efficient library-based deployments.

**Fundamentals & Linear Regression**
* `MODEL REPRESENTATION.ipynb`: Introduction to mapping input features to continuous output targets.
* `COST FUNCTION.ipynb` & `Gradient_Descent.ipynb`: Implementing the squared error cost function and optimizing weights iteratively from scratch.
* `multiple linear regression.ipynb`: Expanding regression models to handle multiple input features simultaneously.
* `feature scaling.ipynb`: Normalizing array data to drastically improve gradient descent convergence speed.
* `Linear_regression_using_sklearn.ipynb`: Implementing regression efficiently for production using `scikit-learn`.

**Classification & Logistic Regression**
* `Classification.ipynb` & `Decision Boundary.ipynb`: Understanding binary classification and mapping spatial decision boundaries.
* `Sigmoid Function.ipynb`: Mathematical implementation of the sigmoid (logistic) activation function.
* `Logistic Regression, Logistic Loss.ipynb` & `Cost Function for Logistic Regression.ipynb`: Formulating the log-loss function for discrete classification tasks.
* `Gradient_descent_logistic.ipynb`: Optimizing parameters for binary classification models.
* `Logistic_reg_sklearn.ipynb`: Deploying logistic regression using `scikit-learn`.

**Advanced Concepts & Tuning**
* `Regularized_cost_and_gradient.ipynb`: Applying L2 regularization (Ridge) to penalize large weights and prevent model overfitting.

## 🛠️ Tech Stack & Tools

* **Language:** Python
* **Environment:** Jupyter Notebooks
* **Core Libraries:** NumPy, pandas, scikit-learn
* **Visualization:** Matplotlib (includes custom `deeplearning.mplstyle` formatting for standardized data visualization)

## 🚀 How to Use

To run these notebooks locally and explore the algorithmic implementations:
1. Clone the repository: 
   ```bash
   git clone [[your-repo-url-here]](https://github.com/Aayushib2002/Supervised-Machine-Learning-Regression-and-Classification.git)
