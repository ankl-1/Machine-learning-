# Machine Learning

A hands-on repository exploring Machine Learning through mathematical implementations, experimentation, data visualization, and practical projects.

This repository documents my progress in understanding machine learning algorithms, implementing them using Python and NumPy, and applying machine learning techniques to datasets using Scikit-learn.

## 🎯 Objectives

- Understand the fundamental concepts behind machine learning algorithms.
- Implement mathematical concepts and algorithms using Python and NumPy.
- Visualize model behavior, predictions, and decision boundaries.
- Apply machine learning techniques to real-world datasets.
- Build, evaluate, and compare predictive models.
- Develop practical skills in data analysis, preprocessing, and model evaluation.

## 🛠️ Tech Stack

- **Language:** Python
- **Numerical Computing:** NumPy
- **Data Analysis:** Pandas
- **Data Visualization:** Matplotlib
- **Machine Learning:** Scikit-learn
- **Development Environment:** Google Colab

## 📂 Repository Structure

```text
ML/
├── Week-1-Linear-Regression/
│   └── model_prediction.ipynb
├── Week-2-Multiple-Linear-Regression/
│   ├── Feature_scaling.ipynb
│   ├── Learning_rate.ipynb
│   ├── Multivariable_linear_regression.ipynb
│   └── linear_regression_sklearn.ipynb
├── Week-3-Classification/
│   ├── Descision_boundry.ipynb
│   ├── Logistic_cost.ipynb
│   ├── Logistic_gradient_descent.ipynb
│   └── Sigmoid_function.ipynb
├── Projects/
│   └── Advertising_Linear_Regression/
│       └── advertising_linear_regression.ipynb
└── README.md
```

*The repository structure will evolve as I explore additional algorithms, experiments, and projects.*

## 📚 Implementations

### Week 1: Linear Regression

Exploring the fundamentals of linear regression through mathematical implementation and visualization.

**Topics covered:**

- Linear model representation using weights and bias
- Prediction using a linear model
- Cost function and mean squared error
- Gradient computation
- Gradient descent and parameter updates
- Visualizing predictions

**Tools:** Python, NumPy, Matplotlib

### Week 2: Multiple Linear Regression

Exploring regression with multiple input features and experimenting with techniques that affect model training.

**Topics covered:**

- Multivariable linear regression
- Feature scaling and standardization
- Learning rate experimentation
- Training models using Scikit-learn
- Comparing model predictions and performance

**Notebooks:**

- `Multivariable_linear_regression.ipynb`
- `Feature_scaling.ipynb`
- `Learning_rate.ipynb`
- `linear_regression_sklearn.ipynb`

**Tools:** Python, NumPy, Matplotlib, Scikit-learn

### Week 3: Classification and Logistic Regression

Exploring binary classification through the mathematical implementation of logistic regression, from probability estimation to gradient descent and decision boundary visualization.

**Topics covered:**

- Binary classification and class labels
- Sigmoid function and probability estimation
- Logistic regression cost function
- Gradient computation for logistic regression
- Gradient descent for optimizing model parameters
- Decision boundaries and classification regions
- Visualizing data points belonging to different classes

**Notebooks:**

- `Sigmoid_function.ipynb`
- `Logistic_cost.ipynb`
- `Logistic_gradient_descent.ipynb`
- `Descision_boundry.ipynb`

**Tools:** Python, NumPy, Matplotlib

**Implementation approach:** Implementing the sigmoid function, logistic cost, and gradient descent using NumPy, with Matplotlib for visualization.

## 🚀 Projects

### Advertising Sales Prediction Using Linear Regression

**Objective:** Develop a machine learning model to predict product sales based on advertising expenditure across different marketing channels.

**Dataset:** Advertising dataset containing TV, radio, and newspaper advertising expenditures alongside sales figures.

**Models implemented:**

- **Simple Linear Regression:** Uses TV advertising expenditure as the input feature.
- **Multiple Linear Regression:** Uses TV, radio, and newspaper advertising expenditures as input features.

**Key activities:**

- Loading and exploring a real-world dataset using Pandas
- Visualizing relationships between advertising expenditure and sales
- Training regression models using Scikit-learn
- Generating predictions
- Comparing single-feature and multiple-feature models
- Interpreting model coefficients
- Evaluating models using MSE, RMSE, and R²

**Evaluation metrics:**

| Metric | Purpose |
|---|---|
| MSE | Measures the average squared prediction error |
| RMSE | Measures prediction error in the target's original units |
| R² Score | Measures how well the model explains variation in the target |

**Key observation:** The multiple-feature model achieved a higher R² score on the training data than the TV-only model. This demonstrates a better fit to the training data, although performance on unseen data must be evaluated separately to assess generalization.

## 🔭 Future Scope

- Complete logistic regression and classification experiments
- Explore regularization in logistic regression
- Implement decision trees and random forests
- Explore K-nearest neighbors
- Practice data preprocessing and feature engineering
- Learn train-test splitting and model validation
- Evaluate models on unseen data
- Build additional machine learning projects using real-world datasets

## 📌 About

This repository is a continuous record of my machine learning practice, focusing on understanding the mathematics behind algorithms, implementing them from scratch where appropriate, visualizing their behavior, and applying them to practical problems.


