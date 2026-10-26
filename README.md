# Machine Learning

A hands-on repository exploring Machine Learning through practical implementations, experimentation, and real-world datasets.

This repository documents my progress in understanding machine learning algorithms, implementing models, analyzing data, and evaluating model performance using Python and its machine learning ecosystem.

## 🎯 Objectives

- Understand the fundamental concepts behind machine learning algorithms.
- Implement mathematical concepts using Python and NumPy.
- Apply machine learning techniques to real-world datasets.
- Build, evaluate, and compare predictive models.
- Develop practical skills in data analysis, visualization, and model evaluation.

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
├── Projects/
│   └── Advertising_Linear_Regression/
│       └── advertising_linear_regression.ipynb
└── README.md
```

*The repository structure will evolve as new algorithms, experiments, and projects are added.*

## 📚 Implementations

### Week 1: Linear Regression

Exploring the fundamentals of linear regression through mathematical implementation and visualization.

**Topics covered:**
- Linear model representation using weights and bias
- Prediction and cost functions
- Mean squared error cost function
- Gradient descent
- Gradient computation and parameter updates
- Visualizing predictions

**Tools:** Python, NumPy, Matplotlib

### Week 2: Multiple Linear Regression

Exploring regression with multiple input features and experimenting with techniques that affect model training.

**Topics covered:**
- Multivariable linear regression
- Feature scaling
- Learning rate experimentation
- Linear regression using Scikit-learn

**Notebooks:**
- `Multivariable_linear_regression.ipynb`
- `Feature_scaling.ipynb`
- `Learning_rate.ipynb`
- `linear_regression_sklearn.ipynb`

**Tools:** Python, NumPy, Matplotlib, Scikit-learn

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

**Key observation:** The multiple-feature model achieved a higher R² score on the training data than the TV-only model. This demonstrates an improved fit to the training data, though performance on unseen data must be evaluated separately to assess generalization.

## 🔭 Future Scope

- Logistic Regression and classification
- Decision Trees and Random Forests
- K-Nearest Neighbors
- Data preprocessing and feature engineering
- Train-test splitting and model validation
- Evaluation on unseen data
- Additional machine learning projects using real-world datasets

## 📌 About

This repository is a continuous record of my machine learning practice, focusing on understanding algorithms, applying them to data, and developing practical skills through implementation and experimentation.


