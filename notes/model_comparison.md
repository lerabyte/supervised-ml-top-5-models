# Model Comparison Notes

## Linear Regression

**Best for:** Predicting numeric values.

**Main idea:** Learns a straight-line relationship between input features and a continuous target.

**Example output:** A predicted number.

**Strength:** Simple and easy to interpret.

**Limitation:** Works best when the pattern is close to linear.

---

## Logistic Regression

**Best for:** Binary classification.

**Main idea:** Predicts the probability that an example belongs to a class.

**Example output:** Class 0 or class 1.

**Strength:** Strong baseline model for classification and easy to explain.

**Limitation:** Can struggle with highly complex nonlinear patterns.

---

## k-Nearest Neighbors

**Best for:** Classification based on similarity.

**Main idea:** Looks at the closest examples in the training set and predicts based on their labels.

**Example output:** The most common class among nearby points.

**Strength:** Intuitive and easy to understand.

**Limitation:** Sensitive to feature scaling and can become slow on large datasets.

---

## Decision Tree

**Best for:** Rule-based classification.

**Main idea:** Splits data using feature-based questions until it reaches a prediction.

**Example output:** A class prediction based on a path through the tree.

**Strength:** Easy to visualize and interpret.

**Limitation:** Can overfit if the tree grows too deep.

---

## Random Forest

**Best for:** Stronger classification performance with less overfitting than a single tree.

**Main idea:** Trains many decision trees and combines their predictions.

**Example output:** A class prediction based on the votes of many trees.

**Strength:** Usually more stable and accurate than one decision tree.

**Limitation:** Less interpretable than a single tree.
