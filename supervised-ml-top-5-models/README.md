# Supervised ML: Top 5 Models

Companion code for my Udemy course, **Supervised Machine Learning Explained: The Top 5 Models**.

This repository contains beginner-friendly notebook examples for five foundational supervised machine learning models: linear regression, logistic regression, k-nearest neighbors, decision trees, and random forests. Each notebook follows the same basic ML workflow: prepare the data, split into training and testing sets, train the model, evaluate performance, and interpret what the model is doing.

## Models Covered

| Notebook | Model | Type | Main idea |
|---|---|---|---|
| `01_linear_regression.ipynb` | Linear Regression | Regression | Predicts a numeric value by learning a line of best fit |
| `02_logistic_regression.ipynb` | Logistic Regression | Classification | Predicts a class using probability |
| `03_k_nearest_neighbors.ipynb` | k-Nearest Neighbors | Classification | Predicts based on the most similar nearby examples |
| `04_decision_tree.ipynb` | Decision Tree | Classification | Learns a sequence of feature-based decision rules |
| `05_random_forest.ipynb` | Random Forest | Classification | Combines many decision trees to make more reliable predictions |

## Project Goal

The goal of this project is to make supervised machine learning easier to understand by showing clear, small examples of each model. Instead of only explaining the theory, each notebook demonstrates what the model does in actual Python code.

## What This Repository Demonstrates

- Basic supervised machine learning workflows
- Train/test splitting
- Model training with scikit-learn
- Evaluation using accuracy, precision, recall, confusion matrices, and mean squared error
- Feature scaling for distance-based and linear classification models
- Comparing simple models vs more flexible models
- Beginner-friendly code organization and comments

## Repository Structure

```text
supervised-ml-top-5-models/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   ├── 01_linear_regression.ipynb
│   ├── 02_logistic_regression.ipynb
│   ├── 03_k_nearest_neighbors.ipynb
│   ├── 04_decision_tree.ipynb
│   └── 05_random_forest.ipynb
├── notes/
│   └── model_comparison.md
└── datasets/
    └── README.md
```

## How to Run

1. Clone this repository.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open the notebooks in Jupyter Notebook, JupyterLab, VS Code, or Google Colab.
4. Run each notebook from top to bottom.

## Dataset Note

Most examples use built-in scikit-learn datasets or small synthetic datasets, so no large external dataset is required to run the notebooks.

## Tech Stack

- Python
- NumPy
- pandas
- scikit-learn
- Jupyter Notebook

## What I Learned

Through building these examples, I learned how different supervised machine learning models approach prediction problems in different ways. Linear regression fits a numeric pattern, logistic regression estimates class probabilities, k-nearest neighbors compares similarity, decision trees create rule-based splits, and random forests combine many trees for stronger generalization.

## Course Connection

This repository was created as the companion codebase for my supervised machine learning course. It is designed to help beginners move from concept-level understanding to actually running and modifying ML code.
