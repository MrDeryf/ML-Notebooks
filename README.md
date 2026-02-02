# Machine Learning Course Notebooks

This repository contains Jupyter notebooks created during the **Machine Learning** course at [MIREA – Russian Technological University](https://www.mirea.ru/) (2024–2025 academic year).

Each notebook corresponds to a practical assignment covering key topics in machine learning.

## 📁 Notebooks Content

1. **Exploratory Data Analysis**  
   Exploratory analysis of two datasets.

2. **Regression – Part 1**  
   Correlation and regression analysis of the Moscow flats dataset with `scikit-learn`.

3. **Regression – Part 2**  
   Implementation of gradient descent and comparison of Lasso and Ridge regression.

4. **Classification**  
   Classification of bananas using three models:
   - SVM
   - KNN
   - Logistic Regression

5. **Decision Trees**  
   Building a decision tree, tuning its hyperparameters, and comparing it to ensemble methods:
   - Random Forest
   - Gradient Boosting
   - Stacking

6. **Clustering**  
   Selecting the optimal number of clusters, drawing a dendrogram, and comparing three methods:
   - KMeans
   - Agglomerative Clustering
   - DBSCAN

7. **Feature Selection**  
   Selecting the most important features using different methods:
   - OLS coefficients
   - Sequential Feature Selector
   - Lasso
   - Ensemble feature importance
   - PCA and t-SNE


## 🛠️ Technologies Used


| Category       | Libraries                          |
|----------------|------------------------------------|
| Core           | Python 3.13, Jupyter Notebook      |
| Data & ML      | `pandas`, `numpy`, `scikit-learn`  |
| Visualisation  | `matplotlib`, `seaborn`            |

🔗 See [`pyproject.toml`](./pyproject.toml) for the complete dependency list.

## ▶️ How to Run
To run the notebooks locally, follow these steps:

1. Clone this repository:  
   ```bash
   git clone https://github.com/MrDeryf/ML-Notebooks
   ```
2. Install dependencies using [Poetry](https://python-poetry.org/):
    ```bash
   poetry install
   ```
3. Launch Jupyter Notebook:  
    ```bash
   jupyter notebook
   ```