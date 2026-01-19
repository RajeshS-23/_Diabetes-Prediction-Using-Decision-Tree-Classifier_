# Diabetes Prediction Using Decision Tree Classifier

This project uses a Decision Tree Classifier to predict whether a person has
diabetes based on medical attributes. Basic data analysis and visualization
are performed before training the classification model.

---

## Project Description

The diabetes dataset is analyzed to understand its structure and feature
distribution. After preparing the data, a Decision Tree classifier is trained
to classify diabetes outcomes. The trained decision tree is visualized to
clearly show how the model makes decisions.

---

## Dataset Information

- Dataset: Diabetes Dataset
- Target column: Outcome
  - 0 – No Diabetes
  - 1 – Diabetes
- Input features include age, BMI, glucose level, blood pressure, and other
medical attributes.

---

## Tools and Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Graphviz

---

## Workflow

1. Load the dataset
2. Perform basic data inspection
3. Visualize Age vs BMI
4. Separate features and target variable
5. Split data into training and testing sets
6. Train a Decision Tree Classifier
7. Predict test results
8. Visualize the decision tree

---

## Model Details

- Algorithm: Decision Tree Classifier
- Train–test split: 80:20
- Model output: Binary classification (Diabetes / No Diabetes)

---

## Results

The Decision Tree classifier successfully learns patterns from the dataset
and predicts diabetes outcomes. Tree visualization helps in understanding
feature-based decision rules.

---

## Visualization

- Bar chart for Age vs BMI
- Decision Tree structure using Graphviz

---

## How to Run the Project

1. Clone or download the repository
2. Install required libraries
   ```bash
   pip install pandas numpy matplotlib scikit-learn graphviz

